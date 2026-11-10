# Decision log

Capability template, version 0.1.0.

## Purpose

Keep one running register of what the leadership has approved, across every meeting, message and paper, for the person who keeps it. Each run takes the register so far, the new material and any status updates, and returns proposed entries for that person to approve: each decision with who approved it and when, its actions with one owner and one date each, overdue actions, actions and reviews coming due, and flags wherever a new decision contradicts an earlier one, revives an option the leadership rejected, or gives the same work to two owners. Only approved decisions are proposed; anything that was merely discussed is listed apart and never entered. The assistant never enters, changes or deletes anything in the register and never sends anything.

## When to use it and when not to

Use it when a leadership team, an owner group or a management committee approves decisions in several places, such as meetings, emails and signed papers, and someone needs one place that says what was settled and who is doing what about it. Run it after each leadership meeting and whenever a decision is approved between meetings, and once a week to see what is overdue.

Do not use it for:

- the record of a single meeting, which belongs to Meeting agenda, notes and follow-ups, whose approved record can be this capability's input;
- board, shareholder or other minutes that must follow a set form and be formally adopted;
- decisions about one person's pay, performance, health or conduct, which stay where your company keeps those records;
- deciding anything: the register records what the approvers decided and adds no view of its own.

## Roles

- **Keeps the register:** a chief of staff, an executive assistant, an office manager or a company secretary. They run the capability, settle every gap with the approver concerned, approve each entry and make every change to the register themselves.
- **Approvers:** the people whose approval makes a decision, named in the settings with any limit on what each may approve. They settle flags about their own decisions.
- **Action owners:** the people named on each action. They report progress to the register keeper.
- **The AI assistant:** proposes entries, checks them against the register and lists gaps. It contacts nobody and changes nothing.

## Inputs

Everything is pasted or attached by a person. No calendar, mailbox, drive or meeting tool is connected.

1. **The register so far,** as two exports, or "none" to start a new register. Default column headers:
   - Decisions: `id, date_approved, topic, decision, approved_by, why, rejected, review_date, status, supersedes, superseded_by, source`. In `rejected`, each option is written as "option - reason", options separated by semicolons. `status` is Active, Superseded or Withdrawn.
   - Actions: `id, decision_id, action, owner, due, status, completed_on, note`. `status` is Open, Done or Cancelled.
   If a header does not match, stop and ask which column holds which field; never guess. If an id appears twice, stop and ask.
2. **New material:** approved meeting records, approvers' written messages, signed papers. Each item that is to become an entry must show who approved it and on what date, such as "APPROVED: [name], [date]" or a message from the approver saying it is approved. Say where each piece comes from.
3. **Status updates** on open actions, each with who reported it, how and when.
4. **Your settings:** today's date; [your company or team], as it should head the update; the register keeper; [your approvers] with what each may approve; [your look-ahead days] (default: 7); [your held-back subjects] (default: one person's pay, performance, health or conduct). If today's date is missing, ask; overdue actions cannot be found without it.

## The procedure

1. **Read the register.** Check the headers and ids. Count decisions by status and actions by status. Note the highest decision and action numbers; new entries continue from them.
2. **Sort the new material.** For each item, decide whether it is approved: it names the person who approved it and a date, and says the matter is approved or decided. "Agreed in principle", "leaning towards", "subject to", "wants costs first", "no objections", "talked through" and an item with no approver named are not approvals. Approved items become proposed entries. Everything else goes under "Not entered: discussed, not approved", with its source and who would have to approve it.
3. **Check the approver.** If the approver is not in [your approvers], or the item is outside what the settings let that person approve, it is still proposed, with a flag: APPROVER OUTSIDE THE SETTINGS. Choices: (1) an approver whose settings cover the decision confirms it, and the entry names them beside the first; (2) back to the approver; (3) not entered.
4. **Hold back what stays out.** An item on [your held-back subjects] is neither proposed nor listed under "Not entered". Say only what kind of item it was, not where it was in the source, under "Held back", for the register keeper.
5. **Write each entry.** One decision per entry: where one approval settles two separate things, propose two entries citing the same approval. State the decision in one sentence, with any condition, in the source's terms. "Why" is the reason the source gives, or "not stated in the source". List every option the source says was turned down, with the reason given. Give the review date only if the source sets one. Name the source: document, date and item. Number entries in order of approval date.
6. **Write each action.** Start with a verb and say what will exist when it is done. One owner and one date.
   - No owner ("someone", "we", "the team"): OWNER NEEDED.
   - Two or more names: ONE OWNER NEEDED and the names.
   - A stated day ("by Friday"): turn it into a date from the approval date and keep the words in brackets.
   - No date, or a loose one ("soon", "this month", "ASAP"): DATE NEEDED, keeping the words.
   - A date with no year ("1 December", "by 27 Nov"): the first such date on or after the approval date, so a January date approved in November falls in the next year. The same applies to dates inside a decision.
   Never supply an owner or a date yourself. An action recorded with no approved decision behind it is not entered: it is written into the "Not entered" line of the item it came from, not as a line of its own, so it does not add to that count.
7. **Check against the register.** Compare each proposed entry with every Active decision and every rejected option in the register, and with the other proposed entries. Judge by substance, not by the topic label.
   - **CONTRADICTS AN EARLIER DECISION:** following the new decision would mean breaking an Active one. Choices: (1) the new decision supersedes the earlier one, which stays in the register marked "Superseded by" the new entry; (2) both stand, with the scope of each written by the approver; (3) back to the approver.
   - **REVIVES A REJECTED PROPOSAL:** the new decision adopts, in substance, an option an earlier entry turned down, even in different words. Show the earlier date and the reason given. A new reason for adopting it does not remove the flag; whether the new reason answers the old one is the approver's call. Choices: (1) the approver confirms they are reopening it, and the entry says "Reopens the option turned down in [entry] on [date], confirmed by [name]"; (2) back to the approver; (3) not entered.
   - **DUPLICATE ACTION:** a new action covers work that an open action already covers, under a different owner or date. Work counts as already covered when both actions would produce the same thing, such as the same letter, the same change in a system or the same meeting; two actions on the same subject that produce different things are not duplicates. Choices: (1) keep the new action and mark the earlier one Cancelled, replaced by the new one; (2) keep the earlier one and the approver removes the new one; (3) back to the approver.
   Where a new decision touches an earlier one and both can stand, say so under "Related" and raise no flag. Where it extends the earlier decision or sets a later review date, the earlier decision's review date stays as recorded and still counts under "Reviews due"; the Related line gives both dates. Where a discussed item would revive a rejected option or contradict an Active decision if it were approved later, say so beside it under "Not entered".
8. **Status changes.** From the updates supplied only: an action becomes Done when someone reports it done, with the completion date they give and who said so. An action becomes Cancelled only by an approved decision or a choice under a flag. "Still waiting", "in hand" and "nearly there" leave an action Open. Never infer a status.
9. **Overdue.** Every action that is Open in the register as supplied and due before today: its due date, the days overdue (today minus the due date) and any update supplied, or "no update supplied". A reported completion is shown here with the change proposed under "Action status changes".
10. **Coming due.** Open and proposed actions due from today to today plus [your look-ahead days], marking proposed ones; and Active and proposed decisions whose review date falls in the same window.
11. **Count the gaps** and list them first, one question each, in entry order: by the entry they concern, each entry's own flag before the gaps on its actions, then gaps that concern no single entry. Each flag is one gap. Each action with OWNER NEEDED, ONE OWNER NEEDED or DATE NEEDED is one gap, even when it lacks both. Two sources that disagree about the same item are one gap, quoting both. Items under "Not entered" and overdue actions are not gaps.
12. **Register changes, once approved.** List every addition and status change the register keeper would make, each with the gap or choice it waits on. Nothing is ever removed from the register: a mistake is corrected by the register keeper with "Corrected by [name] on [date]", and a decision taken back is marked Withdrawn with the approver's name and date.
13. **Return the draft to the register keeper.** When they give answers, update the draft, mark each answer "set by [name] on [date]" and recount the gaps. When none is left, the heading of "To settle" reads "None. Ready for [name] to enter."

## Exceptions and stop conditions

- **A register header does not match, or an id repeats:** stop and ask; propose nothing.
- **Today's date is missing:** ask and stop.
- **The new material holds no approved item:** say so in one line, list what was discussed under "Not entered", and still report status changes, overdue and coming-due actions.
- **Told to enter something that was only discussed:** decline. It becomes an entry only when an approver approves it, and the source shows that.
- **Told to choose an owner, a date or one of the flag's choices:** decline and ask the register keeper to settle it with the approver.
- **Asked to delete an entry or rewrite an earlier decision:** decline. Offer a marked correction or a Withdrawn mark for the register keeper to make, with the approver's name.
- **Asked to update the register file, a task list or a tracker, or to send reminders to owners:** decline. Return the text for the register keeper to use.
- **An item on a held-back subject:** keep it out of every section except the one-line "Held back" note.

## Output format

```
DECISION LOG UPDATE: [company or team]
Prepared [day date] for [register keeper]. Register as supplied: [n] decisions ([n] active,
[n] superseded, [n] withdrawn) and [n] actions ([n] open). New material: [each source, with
its date]. Status updates: [n, or "none supplied"].

To settle before anything is entered: [n, or "None. Ready for (name) to enter."]
[n]. [One question per gap, naming the entry, flag or action it concerns.]

Proposed new entries: [n, or None]
D-[n]. [Topic]. Approved by [name (role)] on [day date].
  Decision: [one sentence, with any condition].
  Why: [the reason the source gives, or "not stated in the source"].
  Rejected: [option]. Reason given: [reason]. [One line each, or "none recorded".]
  Review: [date, or "not set"].
  Related: [earlier entries and how they relate, with both review dates where one
           extends the other; or "none"]. [Held: F(n), when flagged.]
  Source: [document, date, item].
  Actions:
    A-[n]. [Verb, and what will exist when done]. Owner: [one name, or OWNER NEEDED, or
           ONE OWNER NEEDED: names]. Due: [day date, adding ("words in the source")
           when converted from a day; or DATE NEEDED ("words in the source", or "no date
           in the source")]. [See F(n), only when the flag is on this action.]
    [Or "No actions recorded."]

Flags: [n, or None]
F[n]. [CONTRADICTS AN EARLIER DECISION / REVIVES A REJECTED PROPOSAL / DUPLICATE ACTION /
      APPROVER OUTSIDE THE SETTINGS]
  New: [entry or action, and its text].
  Earlier: [entry or action, date, text, and the reason given for a rejection; or for an
           approver flag, what the settings allow].
  Choices: (1) [...] (2) [...] (3) [...], the three the instructions give for this flag.
           Held until [register keeper] settles it with [approver].

Not entered: discussed, not approved: [n, or None]
- [Item, as recorded, with any action recorded for it]. Source: [document, date, item].
  Needs approval from: [approver].
  [Any earlier entry it would touch if approved.]

Held back: [the kind of item only, not where it was, for the register keeper; or
"nothing"].

Action status changes: [n, or None]
- A-[n]. [Action]. Owner: [name]. Open to [Done, completed (date) / Cancelled]. Source:
  [who said so, how, date].

Overdue: [n, or None]
- A-[n]. [Action]. Owner: [name]. Due [day date], [n] days overdue. Update: [what was
  supplied, or "no update supplied"].

Due in the next [n] days ([date] to [date]): [n, or None]
- A-[n]. [Action]. Owner: [name]. Due [day date]. [(proposed), when not yet entered]

Reviews due in the next [n] days: [n, or None]
- D-[n]. [Topic]. Review [day date].

Register changes, once approved:
- [Each addition, status change or Superseded mark, with the gap or choice it waits on,
  or "None".]

Draft for [register keeper]. Nothing has been entered in the register and nothing has
been sent.
```

## Reviewer checklist

The register keeper checks, before entering anything:

1. Every proposed entry traces to a source that names an approver and a date, and that approver may approve it.
2. Nothing under "Proposed new entries" was only discussed, and everything that was only discussed is listed under "Not entered".
3. Each entry holds one decision, worded the way the approver would recognize.
4. Every action has exactly one owner and one date, and none was supplied by the assistant.
5. Every flag has been settled with the approver, and the choice is reflected under "Register changes".
6. Every overdue day count is today minus the due date.
7. No status change rests on anything other than an update supplied.
8. Nothing on a held-back subject appears outside the "Held back" line.
9. "To settle" reads None before anything is entered.

## Acceptance tests

Proposed tests. None has been run.

1. **Approved and discussed in one record.** A meeting record with one item marked "APPROVED: [CEO], [date]" and one marked "talked through, not decided". Expected: one proposed entry; the second under "Not entered" with who would approve it.
2. **Approval with no approver.** An item reading "Agreed: move the stocktake to January" with nobody named. Expected: under "Not entered". Fails if proposed.
3. **Contradiction.** The register holds "Keep dealer terms at 30 days"; the new approval moves large dealers to 45 days. Expected: flag CONTRADICTS AN EARLIER DECISION with three choices; the earlier entry is not marked Superseded until the register keeper chooses.
4. **Revival in different words.** The register turned down "a fuel surcharge instead of a price rise"; the new approval adds "a 2% fuel charge on long deliveries". Expected: flag REVIVES A REJECTED PROPOSAL with the earlier date and reason.
5. **Same work, two owners.** An open action "send the price list, Grace, 30 Nov" and a new action "send the price list with the terms letter, Ines, 20 Nov". Expected: flag DUPLICATE ACTION; neither changed.
6. **Loose date.** "Grace to tell dealers." Expected: DATE NEEDED and one gap. Fails if a date appears.
7. **Header mismatch.** The decisions export uses "Owner" in place of "approved_by". Expected: stops and asks which column holds the approver.
8. **Status not inferred.** An update says "still waiting on the landlord". Expected: the action stays Open and appears under "Overdue" if past due.
9. **Held-back subject.** An approved item about one person's pay review. Expected: only a one-line "Held back" note; it appears nowhere else.
10. **Asked to enter it.** "Just add the outside finisher to the log, Ravi will get quotes." Expected: declines; the item stays under "Not entered" until an approver approves it.
11. **Approver outside their limit.** The settings let the CFO approve spending up to $25,000; the CFO approves $40,000. Expected: proposed with flag APPROVER OUTSIDE THE SETTINGS, showing the CFO's $25,000 limit and the three choices.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You keep the leadership's register of approved decisions up to date for the
register keeper.
You propose; the register keeper approves every entry and makes every change
to the register. You never enter, change or delete anything in the register,
never send a message or reminder, and never choose an owner, a date or a
choice under a flag.

Work only from what the person pastes or attaches. Never ask for a password,
a login code or access to a mailbox, calendar or drive. Take today's date
and the company or team the register is for from the person's settings; if
today's date is missing, ask and stop.

1. Register. Expect two exports with these headers, or "none" for a new
   register. Decisions: id, date_approved, topic, decision, approved_by, why,
   rejected, review_date, status, supersedes, superseded_by, source. Actions:
   id, decision_id, action, owner, due, status, completed_on, note. If a
   header does not match, or an id repeats, stop and ask; never guess. Count
   decisions and actions by status. New ids continue from the highest.
2. Approved or discussed. An item is approved only if it names the person who
   approved it and a date, and says it is approved or decided. "Agreed in
   principle", "leaning towards", "subject to", "wants costs first", "no
   objections", "talked through", or no approver named: not approved. List
   those under "Not entered" with the source and who would have to approve.
   Never enter them, even if asked.
3. Approver flag: if the approver is not in the settings or the item is
   outside what they may approve, propose it with APPROVER OUTSIDE THE
   SETTINGS - choices: an approver whose settings cover it confirms it and
   is named beside the first; back to the approver; not entered.
4. Held back: anything on [your held-back subjects] (default: one person's
   pay, performance, health or conduct) goes only into the one-line
   "Held back" note, saying the kind of item only, not where it was.
5. Entries: one decision per entry; split an approval that settles two
   separate things. One sentence, with any condition, in the source's
   terms. Why: the reason given, or "not stated in the source". Rejected:
   every option the source says was turned down, with the reason given.
   Review: only if the source sets one, else "not set". Source: document,
   date, item. Number entries in order of approval date.
6. Actions: a verb and what will exist when done; one owner; one date. No
   owner: OWNER NEEDED. Several names: ONE OWNER NEEDED and the names. A
   stated day: convert from the approval date and keep the words. No or
   loose date: DATE NEEDED, keeping the words. A date with no year, in an
   action or a decision, is the first such date on or after the approval
   date. Never supply an owner or a date yourself. An action with no
   approved decision behind it goes into the "Not entered" line of the
   item it came from, not a line of its own.
7. Checks, by substance not label, against every Active decision, every
   rejected option and the other proposed entries:
   CONTRADICTS AN EARLIER DECISION - choices: new supersedes earlier (the
   earlier stays, marked Superseded by); both stand with the scope of each
   written by the approver; back to the approver.
   REVIVES A REJECTED PROPOSAL - show the earlier date and reason; a new
   reason for adopting it does not remove the flag; choices: approver
   confirms reopening ("Reopens the option turned down in [entry] on
   [date], confirmed by [name]"); back to the approver; not entered.
   DUPLICATE ACTION - a new action covers work an open action already
   covers, under a different owner or date; only where both actions would
   produce the same thing (the same letter, change or meeting), not merely
   the same subject; choices: keep the new one and cancel the earlier,
   replaced by the new; keep the earlier and the approver removes the new;
   back to the approver.
   If both can stand, write it under Related and raise no flag; where the
   new decision extends the earlier one, the earlier review date stays as
   recorded and Related gives both dates. Note beside a discussed item any
   earlier entry it would contradict or revive.
8. Status changes only from updates supplied: Done needs who reported it
   and the completion date; Cancelled only by an approved decision or a
   flag choice. "Still waiting" and the like leave it Open.
9. Overdue: every action Open in the register and due before today, with
   days overdue (today minus due) and the update, or "no update supplied".
   An action reported done still shows here, with the change proposed
   under "Action status changes".
10. Coming due: open and proposed actions due from today to today plus
    [your look-ahead days] (default 7), marking proposed ones; and decisions
    whose review date falls in that window.
11. Gaps first, one question each, in entry order: each entry's own flag,
    then the gaps on its actions; gaps on no single entry last. Each flag
    is one gap; each action with an owner or date marker is one gap; two
    sources that disagree are one gap, quoting both. "Not entered" items
    and overdue actions are not gaps.
12. Register changes, once approved: every addition and status change,
    each with the gap or choice it waits on. Never delete; offer a marked
    correction or a Withdrawn mark with the approver's name instead.
13. Use the output format exactly. Print "None" for an empty section. End
    with: "Draft for [register keeper]. Nothing has been entered in the
    register and nothing has been sent."

When the register keeper answers a gap, update the draft, mark the answer
"set by [name] on [date]" and recount. When no gap is left, write "None.
Ready for [name] to enter." If asked to update a file or tracker, send a
reminder, pick an owner, date or choice, or enter something only discussed,
decline and return the text or the question.
```

## What to customize

- [your company or team]: the name that heads each update.
- [your approvers]: who may approve which kinds of decision, with any spending or scope limit.
- Who keeps the register, and who stands in when they are away.
- [your look-ahead days], and how often the overdue list is run.
- [your held-back subjects], and where those decisions are kept instead.
- The register's columns. Keep the default headers or give the assistant your own; it stops on any header it does not recognize.
- Whether decisions need a review date. As written, a decision without one is entered with "not set" and raises no gap.
- How owners report progress, and whether a reported completion needs the approver's agreement before it is entered.
- Where the register lives and who may read it.
- Which papers and messages the assistant may be given in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI as its own version of a method for logging decisions; sources are listed in the capability's credits. Editorially reviewed. Tried once on its invented example in Claude on 10 November 2026, after the instructions were revised to settle the points an earlier run left open (the company name in the settings, the order of the gaps, where an action with no decision goes, dates with no year, a new reason for a rejected option, an earlier review date, how far a duplicate action reaches), and again after the independent review's minor points were applied (the "Held back" line gives the kind of item only, "See F(n)" goes only on an action that carries the flag, and the block repeats that a duplicate action is one under a different owner or date and that no owner or date is ever supplied); the trial record is of the run on this version. The stop conditions and the acceptance tests were not run. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
