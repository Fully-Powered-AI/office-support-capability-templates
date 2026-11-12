# Shared folder filing plan

Workflow template, version 0.1.0.

## Purpose

Prepare one filing plan for a shared folder from an export of its contents and the company's approved filing conventions: a proposed folder structure, a list of file moves with each document's owner named, the duplicates to resolve, the access questions that must be answered first, and every file the rules do not cover. The plan is built only from file names, paths, sizes, dates, owners and sharing lists. The assistant prepares; the coordinator approves the plan, each document's owner approves the moves of their own documents, and a named holder confirms any restricted record. The assistant never moves, renames, deletes, shares or re-permissions anything, and never opens a file.

## When to use it and when not to

Use it when a shared folder needs tidying: before a move to a new drive, after a reorganization, or as a yearly clean-up. It suits a folder of up to a few hundred files, run one top-level folder at a time.

Do not use it for:

- capturing what a leaving colleague knows; departing employee knowledge capture covers that;
- deciding which documents are out of date or wrong. The plan sorts by name, path and date only; it does not judge content;
- deleting, destroying or retaining records. The plan proposes no deletion. What must be kept, and for how long, is for the person who holds each restricted category to say;
- writing staff announcements about the new layout; staff newsletter and FAQ roundup and internal change announcement cover those;
- setting up the drive's permissions. The plan only raises questions where a file's current sharing and its new folder's audience differ.

## Roles

- **Runs it:** the office manager, office coordinator or executive assistant, called the coordinator here.
- **Approves the plan:** the coordinator, before it goes to anyone else.
- **Owns each document:** the person named in the `owner` column. Approves the move of their own documents and answers questions about them.
- **Holds a restricted category:** the person the conventions name. Confirms the moves of those records.
- **Makes the changes:** the document owner or the coordinator, in the drive, after approval. The assistant does not.
- **The AI assistant:** prepares the plan. It contacts nobody and has no access to the drive.

## Inputs

Everything is pasted or attached by a person. No drive, file server or mailbox is connected.

1. **The settings.** The folder being tidied, today's date and the coordinator (name and role). If any is missing, stop and ask. Also, if you want one: a batch size other than the default of 200 rows.
2. **The folder inventory,** exported from the folder the coordinator is authorized to see, with these column headers: `path`, `name`, `size_kb`, `modified`, `owner`, `shared_with`, `link_shared`.
   - `path` is the folder the file sits in. `name` is the file name with its extension. `size_kb` is a whole number. `modified` is the last modified date as YYYY-MM-DD.
   - `owner` is one person's name; blank means no owner is recorded.
   - `shared_with` lists the people or groups with access, separated by semicolons; blank means nobody besides the owner.
   - `link_shared` is "yes" or "no". Any other value counts as "yes".
   - Rows are numbered from 1 in the order supplied, not counting the header. If a header does not match, stop and ask which column holds what; never guess. If there are more rows than the batch size (200 rows unless the settings give another), stop and ask for one top-level folder at a time. If there are no rows, stop.
3. **The filing conventions,** approved by a named person, with three parts:
   - **Destination folders,** numbered in the order they should print, each with its full path and its audience: the people or groups who may see it, separated by semicolons.
   - **Filing rules,** numbered R1, R2 and so on. Each says "if [condition], file in [destination folder]". A condition is one of: the name contains a word or phrase; the name starts with a word or phrase; the path begins with a stated path; the file was modified more than a stated number of months before today. Name and path conditions ignore capital letters, so "invoice" matches "Invoice". "More than n months before today" means the modified date is earlier than today's date minus n months, keeping the same day of the month (or the last day of that month if it has no such day); a file modified exactly on that date is not older. Today's date may be written in any form in the settings; use its YYYY-MM-DD form for this test. A rule may join two conditions with "or". The first rule that matches decides.
   - **Restricted records,** if any: which files count, and the person who holds them and confirms before they move. A restriction may be written by file (a name or path condition, with capital letters ignored) or by destination folder (every file filed there counts).
   If the conventions have no destination folders or no rules, stop: the plan cannot invent them.

## The procedure

1. **Check the inputs.** Confirm the settings, the column headers, the row count against the batch size and the conventions. Stop where the inputs section says to.
2. **Find incomplete rows.** A row needs a path, a name, a size and a modified date. A row missing any of them is not planned. List it under "Not planned" and raise one question for its owner, or for the coordinator if no owner is recorded.
3. **Find duplicates.** Among the complete rows, group rows whose names are the same ignoring capital letters. Compare whole names only; near matches such as "(1)" or "copy of" are not found. A group holds two or more rows. If every row in a group has the same size it is "likely copies"; if sizes differ it is "possible versions". The assistant cannot tell a copy from a different document that happens to be the same size, and says "likely". Every row in a group is kept out of the moves and the stays. Raise one question for all the owners in the group, naming the coordinator too if an owner is blank. State where the rules would file the group if it is kept, using the first row of the group in the order supplied; if no rule matches, say so.
4. **Apply the rules.** For each remaining row, test the rules in order and take the first that matches. Name and path conditions ignore capital letters, and the modified-date condition counts from today's date as defined under Inputs. The destination is that rule's folder. If no rule matches, the row goes under "Not planned" with one question for the coordinator: which folder, or should a rule be added. Never invent a folder, and never choose a destination because it seems sensible.
5. **Sort moves from stays.** If the row's path is exactly its destination folder, the file stays; list it under "Files that stay". Otherwise it is a move. A file that stays is not checked for owner, shared link or access; those checks are for files that would move.
6. **Check each move,** in this order, raising one separate question for each check that fails. A move with any open question is held.
   1. **Owner:** `owner` is blank. Ask the coordinator who owns it. Never name an owner from the path, the file name or the sharing list.
   2. **Shared link:** `link_shared` is "yes" (or anything other than "no"). Ask the owner whether the link should keep working after the move. If the owner is blank, address the question to the coordinator to put to the owner once the owner question is answered.
   3. **Access:** compare the file's `shared_with` entries with the destination's audience, entry by entry, word for word. If the two sets are not identical, ask the owner, naming the entries only on the file and the entries only on the folder (write "none" where there are none). The assistant does not know who is inside a group, and does not know how your drive treats a file moved into a folder; the owner and the coordinator do.
   4. **Restricted records:** the file matches a restriction in the conventions, either by its name or path or because its destination folder is a restricted one. Ask the holder to confirm the move.
7. **Set each move's status.** "Ready for owner approval" when nothing is open. Otherwise "Held until Question [n] is answered", or "Held until Questions [n] and [n] are answered" when more than one is open, naming every open question. The approver is the owner, or NOT RECORDED when there is none, plus the holder for restricted records.
8. **Build the folder structure.** List every destination folder in the conventions' order with its count of planned files: files to move plus files already there, held or not. Duplicates and rows not planned are not counted in a folder; state them on one line below.
9. **Group the ready moves by owner,** owners in the order they first appear in the move list.
10. **Order and number.** Moves go in the conventions' folder order, then by row number. Number the questions in order of the lowest row number each one involves, and for one row in the order of the checks above.
11. **Check the counts.** Rows supplied must equal moves plus stays plus rows in duplicate groups plus rows not planned. If they do not, find the row that was lost before returning anything.
12. **Return the plan** to the coordinator only. Update it and recount when answers come back, marking each answered question "settled by [name]".

## Exceptions and stop conditions

- **A column header does not match the defaults:** stop and ask which column holds what.
- **No conventions, or no destination folders, or no rules:** stop and ask for them. The plan does not invent a structure.
- **More rows than the batch size:** stop and ask for one top-level folder at a time.
- **Asked to move, rename, delete, share or re-permission anything,** or to produce commands or scripts that do so: decline. Return the plan for people to carry out.
- **Asked to say which duplicate to keep, or to propose deleting anything:** decline. The owners decide.
- **Asked to guess an owner, or to judge a file by what it appears to contain:** decline. The plan works from the export only.
- **Asked to add a folder or a rule the conventions do not hold:** decline and list the row under "Not planned"; the coordinator may add the rule and run again.
- **Asked for a password, a sharing link or a login code,** or offered one: do not ask for one; if one is pasted in, do not repeat it and tell the coordinator to remove it from the export.
- **A file name looks like a personal or sensitive record** (a payslip, a medical note): treat it by the rules like any other, and never repeat anything about it beyond the name already in the export.
- **A folder ends up with no planned files:** say nothing about removing it. Whether to delete a folder is for the coordinator.

## Output format

```
FILING PLAN: [folder being tidied], prepared [today's date, written as the settings give it]
For: [coordinator (role)]. The coordinator approves this plan first; each owner approves the moves of their own documents.
Prepared from [n] inventory rows, [n] filing rules and [n] destination folders. Nothing has been moved, renamed, deleted or re-shared.
Rows [n] = to move [n] + stay [n] + in duplicate groups [n] + not planned [n].
Moves: [n] ready for owner approval, [n] held.

Proposed folder structure
[Destination folder] ([n] files: [n] to move, [n] already there)
Waiting on a duplicate decision: [n] rows in [n] groups, not counted above.
Not planned: [n] rows, not counted above.

Files to move: [n, or None]
Row [n]: [file name], from [path] to [destination folder] (rule [n]). Owner: [name / NOT RECORDED]. Approves: [owner / NOT RECORDED][; also holder (role) for restricted records]. Status: [Ready for owner approval / Held until Question n is answered / Held until Questions n and n are answered].

Ready moves by owner: [Owner: rows n, n; Owner: row n, or None]

Files that stay: [n, or None]
Row [n]: [file name] is already in [path] (rule [n]).

Duplicates to resolve: [n groups, or None]
[Likely copies / Possible versions]: "[file name]", rows [n and n].
Row [n]: [path], [size] KB, modified [date], owner [name / NOT RECORDED]. [One line for each row in the group.]
If kept, rule [n] files it in [destination folder] [or: no rule matches]. See Question [n].

Not planned: [n, or None]
Row [n]: [file name or NO NAME], [no filing rule matches / incomplete row: (field) missing]. See Question [n].

Questions to settle: [n, or None]
Question [n] [duplicate / access / shared link / owner / restricted record / no rule / incomplete row]. Row [n]. [The facts.] [One question, for one or more named people. Where the person who must answer is not yet known, name the person who will put it to them.]

Nothing has been moved, renamed, deleted or re-shared. Approvals still to come: the coordinator, for this plan; [each owner], for their own moves.
```

## Reviewer checklist

1. The counts tie: rows supplied equal moves plus stays plus duplicate rows plus rows not planned. (Coordinator)
2. Every destination comes from the first matching rule in the conventions, and no folder appears that the conventions do not name. (Coordinator)
3. Every owner is the one in the export; none was guessed. (Coordinator)
4. Every access question names the right entries on each side. (Coordinator, then the owner)
5. Every file shared by link, with no owner or in a restricted category is held, and no held move shows as ready. (Coordinator)
6. Every duplicate group is listed as a question for its owners, with no choice made. (Coordinator)
7. The plan proposes no deletion, rename or change of sharing. (Coordinator)
8. Each owner has checked their own moves against the drive before anyone acts. (Owners)

## Acceptance tests

Proposed tests. Tests 1 to 11 were exercised together, once, on the invented example (see the trial record); tests 12 to 14 have not been run.

1. **Ordinary file.** A file whose name matches rule R3, sitting elsewhere, with sharing identical to the destination's audience and an owner recorded. Expected: a move, ready for owner approval.
2. **First match wins.** A file whose name matches R4 and whose date also matches an archive rule listed later. Expected: filed by R4.
3. **No rule.** A file matching nothing. Expected: under "Not planned" with a question for the coordinator; no folder invented.
4. **Already in place.** A file whose path equals its destination. Expected: under "Files that stay".
5. **Likely copies.** Two rows with the same name and size in different folders. Expected: one group, both rows held out of the moves, a question for both owners, no keeper chosen.
6. **Possible versions.** Same name, different sizes. Expected: a group marked "possible versions", with the question and no judgment on which is newer or better.
7. **No owner.** A file with a blank owner. Expected: held, with a question for the coordinator and approver NOT RECORDED; no owner suggested.
8. **Shared link.** A file with `link_shared` set to "yes". Expected: held, with a question whether the link should keep working.
9. **Access mismatch.** A file shared with an extra group that the destination does not include, and another file whose destination includes a group it is not shared with. Expected: a question for each, naming the entries only on the file and only on the folder.
10. **Restricted record.** A file the conventions mark as restricted. Expected: held, with a question for the holder and the holder named under the approver.
11. **Incomplete row.** A row with no file name. Expected: not planned, with a question for the owner.
12. **Header mismatch.** The export has `folder` where `path` should be. Expected: stops and asks which column holds what.
13. **Asked to move files.** "Go ahead and move the ready ones." Expected: declines; returns the plan.
14. **Asked which copy to delete.** Expected: declines; the owners decide.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You prepare one filing plan for a shared folder, for the coordinator. You
prepare; the coordinator approves the plan, each document's owner approves
the moves of their own documents, and a named holder confirms restricted
records. You never move, rename, delete, share or re-permission anything,
never contact anyone, never change any record, and never open a file. You
never ask for a password, a sharing link, a login code or access to the
drive.

Work only from what the person pastes or attaches: the settings (the
folder being tidied, today's date, the coordinator), the folder inventory
and the filing conventions. If a setting is missing, stop and ask. Echo
today's date in the plan's heading as the settings write it, and use its
YYYY-MM-DD form for any date test.

The inventory has the headers path, name, size_kb, modified, owner,
shared_with, link_shared. If a header does not match, stop and ask which
column holds what. Never guess. If there are no rows, stop. If there are
more rows than the batch size (200 rows unless the settings give another),
stop and ask for one top-level folder at a time. Number the rows from 1 in
the order supplied, not counting the header. shared_with entries are
separated by semicolons; a blank owner means none is recorded; any
link_shared value other than "no" counts as "yes".

The conventions must hold destination folders (each with its audience),
numbered filing rules and any restricted records with their holders. If
there are no destination folders or no rules, stop and ask. Never invent a
folder or a rule.

1. A row missing its path, name, size or modified date is not planned: one
   question for its owner, or for the coordinator if no owner is recorded.
2. Group complete rows whose names are the same ignoring capital letters,
   whole names only. Equal sizes: "likely copies". Different sizes:
   "possible versions". Keep every row of a group out of the moves and the
   stays, ask all its owners one question (naming the coordinator too if
   an owner in the group is blank), and say where the rules would file the
   first row of the group, or that no rule matches. Never say which row to
   keep.
3. For each remaining row, test the filing rules in order and take the
   first that matches. Name and path conditions ignore capital letters. A
   modified-date condition "more than n months before today" is true when
   the modified date is earlier than today's date minus n months, same day
   of the month (the last day of the month if it has no such day); exactly
   that date is not older. No match: "Not planned", with one question for the coordinator.
4. If the row's path is exactly its destination, it stays. Otherwise it is
   a move. A file that stays is not checked for owner, link or access.
5. For each move, in this order, raise one separate question per failed
   check: (a) no owner: ask the coordinator who owns it, and never infer an
   owner; (b) shared link: ask the owner whether the link should keep
   working after the move, or, if there is no owner, ask the coordinator to
   put it to the owner once the owner question is answered; (c) access:
   compare shared_with with the destination's audience, entry by entry,
   word for word, and if the sets differ ask the owner, naming the entries
   only on the file and the entries only on the folder; (d) restricted
   record, whether the conventions restrict the file by name or path or its
   destination folder: ask the holder to confirm. A move with any open
   question is held and says which questions hold it. Otherwise it is
   "Ready for owner approval". The approver is the owner (NOT RECORDED if
   there is none), plus the holder for a restricted record.
6. Count the planned files for each destination folder in the conventions'
   order, group the ready moves by owner, order the moves by the
   conventions' folder order and then by row number, and number the
   questions by the lowest row each involves.
7. Rows supplied must equal moves plus stays plus duplicate rows plus rows
   not planned. Find any lost row before you answer.
8. Use the output format exactly. Print "None" where a section is empty.
   End with the line saying nothing has been moved, renamed, deleted or
   re-shared.

If asked to move, rename, delete or share anything, or to write commands
that do, decline and return the plan. If asked which duplicate to keep, to
propose a deletion, to guess an owner, to judge a file by what it seems to
contain, or to add a folder or rule the conventions do not hold, decline
and say who decides. If a password, link or code appears in the inputs, do
not repeat it; tell the coordinator to remove it. When answers come back,
update the plan, mark each answered question "settled by [name]" and
recount.
```

## What to customize

- Your destination folders, in the order they should print, and who may see each, written exactly as your drive lists people and groups.
- Your filing rules and their order; the first match wins, so put the specific ones first and the age rule last.
- The age after which untouched files go to an archive folder, if you want one.
- Your restricted records and the person who confirms each.
- The batch size, if you want one other than 200 rows.
- The column headers of your drive's export, if they differ, changed in both the inputs and the instructions.
- Which inputs the assistant may be given in ChatGPT, Claude, Copilot or Gemini, and how it should write today's date.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI from its own map of office filing work. Editorially reviewed. Tried once on its invented example, in Claude on 10 November 2026, not fully blind (see the trial record); not yet tested in a client environment.
