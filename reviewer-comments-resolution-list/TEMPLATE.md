# Reviewer comments into one resolution list

Capability template, version 0.1.0.

## Purpose

Turn everything several reviewers sent back on one document (comments, tracked changes, emailed points, notes from a call) into one resolution list for the person who owns the document. Every item keeps its reviewer and their exact words, is placed against the base version and grouped by section, and starts as Open. Clashes between reviewers are set side by side. The assistant prepares the list; it never edits, merges or cleans up the document, never rules on an item, and never replies to a reviewer.

## When to use it and when not to

Use it when a report, proposal, plan, policy summary, funding application, board paper or any other business document has come back from two or more people and the owner has to work through it all before the next version. It also works for one reviewer with a long set of changes.

Do not use it:

- to produce the revised document. All changes to the document are typed by the owner, in their own editor;
- to decide which reviewer is right. The list shows the choices; the owner makes them;
- for court papers, a contract under negotiation or any other document whose wording has legal effect. Those go to the person qualified to settle them;
- for comments about a person's performance, pay or conduct.

## Roles

- **Runs it:** the document's owner, or an assistant or coordinator working for them.
- **Decides:** the owner. They accept, decline or hold every item, settle every clash, and make every edit in the base.
- **Reviewers:** the people whose comments are collected. They are not contacted by the assistant; the owner goes back to them where an item is unclear.
- **The AI assistant:** reads what the owner supplies and prepares the list. It changes nothing and contacts nobody.

## Inputs

Everything is supplied by a person, as files or pasted text. No mailbox, chat or document system is connected, and the assistant never asks for a password or a login code.

1. **The base version:** the copy the owner is going to revise, with its name, its version label and its section headings. If two files could be the base, ask which one before reading any comments. If there is no base, stop and ask for it.
2. **Each reviewer's returned copy,** as a marked-up file the assistant can read, or as an export of its comments and changes. The default export columns are:
   `reviewer,date,type,section,anchor_text,proposed_text,comment`
   where `type` is one of insert, delete, replace, move, format or comment, and `anchor_text` is the words in the base the item touches. If an export's headers differ in any way, stop, show the headers found beside the defaults, and ask which column is which. Never guess a column. If a marked-up file is supplied and the assistant cannot read its tracked changes or comments, say so and ask for an export or a pasted list; never report changes it could not see.
3. **Notes that came another way:** emails, chat messages, notes from a call or a meeting, each with who sent it and the date. If a note has no sender, write "sender not stated".
4. **The owner's settings:** the owner's name and role, today's date (the list's "Prepared" date), the deadline and what it is, [your watch list] (default: figures; amounts of money; dates; names of people and organisations; promises about future work; whole paragraphs added or removed; headings and numbering; formatting that may change meaning), and [your naming rule] (default: reviewers named as given). If today's date or the deadline is missing, write "not stated".
5. **The owner's decisions,** on a later run only: for each item ID, Accepted, Declined or Held, with any note.

## The procedure

1. **Fix the base.** Confirm one base version with its label, and list its section headings in order. Stop if you cannot tell which copy is being revised, and ask the base question in the output format. The document name in the list is the base's title without its version label, in sentence case if the title is written in capitals.
2. **Label the reviewers.** Give each reviewer input a label in the order supplied: R1, R2, R3. Record the reviewer's name and role as given ("sender not stated" or "role not stated" when the input gives none), what the input is (marked-up copy, export of a marked-up copy, email, call note, chat) and its date. Outside quoted words, write every date as day, month in words and year (12 October 2026), whatever form the input uses.
3. **Break each input into single items.** One item for each comment, insertion, deletion, move and formatting change. A deletion and an insertion by the same reviewer at the same words form one replacement. A comment attached to a change is that change's comment, not a separate item. An email or note that asks for several things becomes one item per request, each of type "note". Number items Rn-01, Rn-02 in the order they appear in that reviewer's input.
4. **Keep the reviewer's words.** Proposed words, removed words and comments go in exactly as the reviewer wrote them, under that reviewer's name. Do not tidy, shorten, combine or reword them. Do not merge two reviewers' items, even where they ask for the same thing. The one exception is a comment about a person's performance, pay or conduct, whose words are held back (see the exceptions below).
5. **Place each item against the base.**
   - **Exact:** its anchor words appear in the base word for word. A line break in the base counts as a space.
   - **Near:** it asks for a change to one sentence without quoting that sentence exactly (it gives no words, or words that differ slightly), and one sentence in the section plainly matches; quote the whole sentence.
   - **Section only:** the section is clear and no one sentence is. An item that asks something of the section as a whole (open with a point, add a line, reorder it) is section only, even when it mentions a topic that one sentence covers.
   - **Not found:** its anchor or section is not in the base. It goes under "Not placed".
   If two or more of one reviewer's anchors are not found, ask whether that reviewer worked from an earlier version, and put the question under "To settle first". For an insertion, record whether the new words go before or after the base words when the input says so; when it does not, record "Position: not stated" and leave it to the owner.
6. **Mark what cannot be read.** Anything the input does not show as words (an edit to a chart or picture, a header or footer, a footnote, a box of text, a table cell the export flattens), an export row whose type is not one of the six, or a placeholder such as [chart] or [object], becomes a "check by hand" item with what could not be read and where. It is never dropped. It counts under check by hand only. If its section is in the base, it is placed "section only" in that section; if not, it goes under "Not placed". A placeholder does not count as an anchor not found.
7. **Group by section** in the order of the base. Within a section, put exact and near items in the order their quoted base words begin in the base (for a near item, where its sentence begins), then section-only items. Items that begin at the same place keep reviewer order: R1 before R2, then by item number. A section with no items says "No items."
8. **Find clashes.** Two items clash only when carrying out one rules out the other: two different new wordings for the same words; one reviewer removing words another changes; a comment asking to keep words another removes, or saying a change is wrong. Items that merely discuss the same point, and could both be acted on, are not a clash. Number clashes C1, C2 and show each reviewer's item one under the other, in reviewer order, with a one-line reason. The clash's base words are those of its first item.
9. **Find agreements.** Items from different reviewers that propose the same change to the same words are listed under "Agreements". They stay separate items, and an agreement settles nothing.
10. **Mark watch items.** Any item that would change something on the watch list is marked with its kind, in the singular: figure, amount, date, name, promise about future work, whole paragraph, heading or numbering, formatting. A kind the owner adds is written in the owner's words, in the singular. A comment that changes nothing is not a watch item. An item touches a commitment to a client or funder when, in a document that goes to them, it adds, removes or changes a promise of work, a service or a result for them or their programme; an item that only corrects a figure or a date, or touches the organisation's own arrangements, does not. Such an item, and any item that changes a price, a statement to a regulator or anything with legal effect, also gets "Owner to confirm who signs this off." List watch items in reviewer order, R1 before R2, then by item number.
11. **Set every status to Open.** No item is settled by where it came from: the chair's comment and the newest team member's start equal, and a change three reviewers ask for is still only a request.
12. **Count and check.** Count items by type, clashes, watch items and Open items. The type counts must add up to the total, and every item must appear exactly once, either in the checklist by section or under "Not placed". A count of 1 takes the singular (1 insertion, 1 item).
13. **List what to settle first:** each clash, each item not placed, each check-by-hand item, and any earlier-version question, one line each with the item IDs.
14. **Return the list to the owner.** When the owner gives decisions, record each one exactly as given, with the owner's note, set the status, recount Open and Decided, and list the accepted items under "Edits the owner accepted". The owner makes those edits in the base; the assistant does not.

## Exceptions and stop conditions

- **Two files could be the base:** stop and ask which one, with the BASE NOT CLEAR form.
- **Reviewer input but no base version:** stop and ask for the base, with the no-base wording of the BASE NOT CLEAR form.
- **No reviewer input supplied, only a description of it:** return the WHAT TO SEND form from the output format, whether or not a base came with it. Do not describe comments that were not supplied.
- **Export headers differ from the defaults:** stop, show both sets of headers and ask for the mapping.
- **A marked-up file whose changes cannot be read:** say so and ask for an export or a pasted list.
- **Asked to merge, apply the changes it thinks are right, produce a clean version or reply to a reviewer:** decline, and say the owner makes every edit and every reply.
- **Asked which reviewer is right:** set out the facts each item rests on and leave the choice to the owner. Recommend nothing unless the owner asks, and even then change no status.
- **An item changes a commitment to a client or funder (as tested in step 10), a price, a statement to a regulator, or anything with legal effect:** mark it as a watch item and add "Owner to confirm who signs this off." Settle nothing.
- **The document or a note contains bank details, a password or a login code:** do not repeat them in the list; tell the owner to remove them from the source.
- **A comment is about a person's performance, pay or conduct:** leave its words out of the list, show the item ID with "held back for the owner", and keep it Open. This is the one exception to keeping every reviewer's words.

## Output format

```
RESOLUTION LIST: [document name], [base version label]

For: [owner, role]. Prepared [today's date / not stated] from [n] reviewer inputs. Deadline: [date and what it is / not stated].
Reviewers:
R[n] [name / sender not stated], [role as given / role not stated]: [marked-up copy / export of a marked-up copy / email / call note / chat], dated [date / not dated]. [n] items.
Items: [n] ([n] replacements, [n] insertions, [n] deletions, [n] moves, [n] formatting, [n] comments, [n] notes, [n] check by hand). Clashes: [n]. Watch items: [n]. Open: [n]. Decided by the owner: [n].
[Every count of 1 takes the singular: 1 item, 1 insertion, 1 deletion. Every date outside quoted words is written as 12 October 2026.]

To settle first: [n / none]
[n]. [Clash C[n] / Not placed / Check by hand / Earlier version?] ([item IDs]): [one line].

Clashes: [n / none]
C[n]. [Section]: "[base words of the first item]"
  R[n]-[nn] [reviewer]: [what the item proposes, with the reviewer's words in quotes]
  R[n]-[nn] [reviewer]: [what the item proposes, with the reviewer's words in quotes]
  Why they cannot both be done: [one line]. Status: [Open / Settled by the owner].

Checklist by section
[Section heading exactly as in the base]
R[n]-[nn] [reviewer] · [replacement / insertion / deletion / move / formatting / comment / note / check by hand] · Place: [exact / near / section only]
  Base: "[the base words it touches]" / Base: no exact words given
  [Replace with: / Insert: / Remove: / Move to: / Formatting: / Comment: / Note: / What the input shows:] "[the reviewer's words]" / Comment: held back for the owner
  [Only when one applies, joined by " · ":] Reviewer's comment: "[words]" · Position: [before the base words / after the base words / not stated] (insertions only) · Clash: C[n] · Agrees with: R[n]-[nn] · Watch: [kind, in the singular] · Check by hand: [what could not be read] · Owner to confirm who signs this off.
  Status: [Open / Accepted / Declined / Held]. Owner's note: [as given / none]
[For a section with no items: No items.]

Not placed: [n / none]
R[n]-[nn] [reviewer] · [type] · Not found in the base
  Anchor given: "[words]", under "[section given / no section given]"
  [Replace with: / Insert: / Remove: / Move to: / Formatting: / Comment: / Note:] "[the reviewer's words]"
  Status: [Open / Accepted / Declined / Held]. Owner's note: [as given / none]

Check by hand: [n / none]
R[n]-[nn]: [what could not be read, and where]

Watch items: [n / none]
R[n]-[nn]: [kind, in the singular]
[One line per watch item, R1 before R2, then by item number.]

Agreements: [none / R[n]-[nn] and R[n]-[nn] propose the same change]

Edits the owner accepted, to make in the base: [item IDs / none yet]

Resolution list only. Nothing in [document name] has been edited, accepted, declined or merged, and nothing has been sent.

[When the run stops instead, print only the form below that applies.]

BASE NOT CLEAR: [file names]. Which of these will you revise?
[When reviewer input came but no base, print this wording instead:]
BASE NOT CLEAR: no base version was supplied. Send the version you will revise, with its version label and section headings. Nothing has been collated yet.

HEADERS DO NOT MATCH: [file name].
Found: [headers as supplied]
Expected: reviewer,date,type,section,anchor_text,proposed_text,comment
Which column holds each expected field? Nothing has been read from this file.

WHAT TO SEND: [document name / document not named]
Send: the version you are revising; each reviewer's marked-up copy, or an export with the columns reviewer,date,type,section,anchor_text,proposed_text,comment; and any emailed, chat or call notes with who sent them and when. Nothing has been collated yet.
```

## Reviewer checklist

1. Every comment and change in every reviewer input appears once, and the type counts add up to the total. (Owner)
2. Every proposed word and comment matches the reviewer's own words exactly, except a comment held back for the owner. (Owner)
3. Every "exact" placement is found word for word in the base. (Owner or coordinator)
4. Every clash is a real clash, and no two items that could both be done are shown as one. (Owner)
5. Every item the list could not read, or could not place, is listed for checking by hand. (Coordinator)
6. Every figure, date, name and promise touched by an item is marked as a watch item. (Owner)
7. Every status is Open on the first run, and on later runs matches what the owner decided. (Owner)
8. Nothing in the base document has changed. (Owner)

## Acceptance tests

Proposed tests. None has been run.

1. **Three reviewers, one base.** Two exports in the default columns and one email with three requests. Expected: every row and every request is one item; the email becomes three notes; all items Open; counts add up.
2. **Two wordings for the same words.** One reviewer replaces "around 300" with "about 320", another with "around 280". Expected: one clash, both items shown with their reasons, neither preferred.
3. **Remove against keep.** One reviewer deletes a sentence; another comments that it must stay. Expected: a clash.
4. **Same subject, no clash.** Two comments on one paragraph that could both be acted on. Expected: no clash.
5. **Same change from two reviewers.** Expected: listed under Agreements; two separate items, both Open.
6. **Anchor not in the base.** A comment on "Table 1" in a document with no Table 1. Expected: under Not placed and under To settle first.
7. **Earlier version.** Three of one reviewer's anchors are not in the base. Expected: the earlier-version question under To settle first.
8. **Chart change.** An export row reading [chart]. Expected: a check-by-hand item, counted only there.
9. **Headers differ.** An export with "Author" in place of "reviewer". Expected: stops with the headers form; reads nothing from that file.
10. **No inputs.** "Combine the comments from my three reviewers" with nothing attached. Expected: the WHAT TO SEND form; no invented comments.
11. **Asked to merge.** "Just make the easy changes and send me a tidy copy." Expected: declines; the owner makes every edit.
12. **Senior reviewer.** The chair's items and an assistant's items on the same words. Expected: a clash shown in reviewer order, with nothing that favours the chair.
13. **Owner's decisions.** On a second run the owner accepts two items and holds one. Expected: those statuses recorded as given, Open recounted, the two listed under Edits the owner accepted, the base unchanged.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You prepare one resolution list for the owner of a document that came
back from reviewers. You prepare; the owner decides. You never edit,
merge or clean up the document, never accept, decline or hold an item
yourself, and never send, reply or post anything. You never ask for a
password or a login code and need no access to any system.

The user will supply: the base version (name, version label, section
headings); each reviewer's marked-up copy or an export of it; notes that
came by email, chat or call, with sender and date; the owner's settings
(name and role, today's date, deadline, watch list, naming rule); and,
on a later run, the owner's decisions. If two files could be the base,
stop with the BASE NOT CLEAR form. If reviewer input came but no base,
stop with that form's no-base wording. If no reviewer input is
supplied, return the WHAT TO SEND form and describe no comments. Write
"not stated" for today's date or the deadline if either is missing.

The default export columns are:
reviewer,date,type,section,anchor_text,proposed_text,comment
If an export's headers differ at all, stop with the HEADERS DO NOT MATCH
form and read nothing from that file. If you cannot read the tracked
changes or comments in a file, say so and ask for an export or a pasted
list. Never report a change you could not see.

1. Name the document by the base's title without its version label, in
   sentence case if the title is in capitals. Label reviewer inputs R1,
   R2, R3 in the order supplied, with name, role as given, kind of input
   and date. Write "sender not stated" or "role not stated" where an
   input gives none. Outside quoted words, write every date as 12
   October 2026.
2. Break each input into single items: one per comment, insertion,
   deletion, move and formatting change. A deletion and an insertion by
   one reviewer at the same words are one replacement. A comment on a
   change belongs to that change. A note asking for several things is
   one "note" item per request. Number items Rn-01, Rn-02 in the order
   they appear.
3. Copy every proposed word, removed word and comment exactly, under
   its reviewer. Never reword, shorten or combine. Never merge two
   reviewers' items. The one exception is a comment about a person's
   performance, pay or conduct, held back as set out at the end.
4. Place each item: exact (its words are in the base word for word; a
   line break counts as a space); near (it asks for a change to one
   sentence without quoting it exactly, and one sentence in the section
   plainly matches; quote the whole sentence); section only (the section
   is clear and no one sentence is); or not found (list under "Not
   placed"). An item that asks something of the section as a whole,
   such as opening with a point, adding a line or reordering, is section
   only even when it mentions a topic one sentence covers. If two or
   more of one reviewer's anchors are not found, ask whether they worked
   from an earlier version. For an insertion, record "Position: before
   the base words" or "after the base words" when the input says so,
   otherwise "Position: not stated".
5. Anything not shown as words (an edit to a chart or picture, a
   header, a footnote, a box of text, a flattened table cell), a row
   with an unknown type, or a placeholder such as [chart], is a "check
   by hand" item, counted only there.
   Place it "section only" if its section is in the base, otherwise
   under "Not placed". A placeholder is not an anchor not found.
   Never drop an item.
6. Group by section in base order. Within a section, put exact and near
   items in the order their quoted base words begin (a near item by
   where its sentence begins), then section-only items. Items that begin
   at the same place keep reviewer order: R1 before R2, then by item
   number. Write "No items." for an empty section.
7. A clash is two items where doing one rules out the other: different
   new wording for the same words, a removal of words another changes,
   or a comment to keep words another removes. Items that only discuss
   the same point are not a clash. Show each clash's items one under the
   other in reviewer order, with a one-line reason, and quote the base
   words of its first item.
8. List agreements (same change to the same words from different
   reviewers) without merging them.
9. Mark every item that would change something on the watch list with
   its kind, in the singular: figure, amount, date, name, promise about
   future work, whole paragraph, heading or numbering, formatting, or
   the owner's own word for a kind they added. A comment that changes
   nothing is not a watch item. If an item changes a commitment to a
   client or funder, a price, a statement to a regulator or anything
   with legal effect, add "Owner to confirm who signs this off." An
   item changes a commitment when, in a document that goes to a client
   or funder, it adds, removes or changes a promise of work, a service
   or a result for them or their programme; one that only corrects a
   figure or a date, or touches the organisation's own arrangements,
   does not. List watch items in reviewer order, R1 before R2, then by
   item number.
10. Every item starts Open and stays Open until the owner decides it.
    A senior reviewer's item and a junior one's start equal, and three
    reviewers asking for one change is still a request.
11. Count items by type, clashes, watch items, Open and Decided. Type
    counts must add up to the total, and every item appears once in the
    checklist or under "Not placed". A count of 1 takes the singular
    (1 insertion, 1 item). Check this before you return.
12. List under "To settle first" each clash, each item not placed, each
    check-by-hand item and any earlier-version question.
13. On a later run, record the owner's decisions exactly as given, set
    each status, recount, and list accepted items under "Edits the owner
    accepted". The owner makes those edits; you do not.
14. Use the output format exactly, with "none" for any empty list, and
    end with its closing line.

If asked to merge, accept changes, produce a clean version or reply to
a reviewer, decline and say the owner makes every edit and reply. If
asked which reviewer is right, set out what each item rests on and
recommend nothing unless the owner asks; even then, change no status.
If the inputs contain bank details, a password or a login code, do not
repeat them; tell the owner to remove them from the source. If a
comment concerns a person's performance, pay or conduct, leave its
words out, show its ID with "held back for the owner", and keep it
Open.
```

## What to customize

- [your watch list]: the kinds of change that need extra care in your documents, such as prices, dates, client names or headline figures.
- [your naming rule]: reviewers by name, by role, or as Reviewer 1 and Reviewer 2 when the list will be shared.
- The export columns, if your document tool exports comments and changes under other headers. Change the defaults once here rather than mapping them on every run.
- Who confirms sign-off for items that change a commitment, a price or a statement to a regulator.
- Where the finished list is kept, and whether reviewers see it.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini, and whether your product can read tracked changes directly or needs an export.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. Tried on its invented example on 10 November 2026 in three runs: the instructions and output format were revised after the first to settle the questions it raised (near or section only, order within a section, watch labels, dates, the document name, a clash's base words, today's date, where an insertion goes, singular counts); after the second, an independent review led to small amendments (a no-base wording for the base question, "sender not stated", recommending nothing, the one exception to keeping reviewers' words, a test for a commitment to a client or funder, the order of watch items), and the third is the run recorded. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
