# Delegation brief and follow-up

Workflow template, version 0.1.0.

## Purpose

Help a manager hand work to one person clearly and keep track of it until it is accepted. The workflow template does two things for the same piece of work. When the manager hands over a task, it turns the manager's note into a brief: the deliverable, its format, the due date and time, why it matters, who will use it, what the person may decide on their own, and the dates the manager will check in. Once a week, it reads the list of open delegations and returns where each one stands, what is overdue, the questions only the manager can answer and the next follow-up note for each, drafted and unsent. The manager decides what to delegate and to whom. The assistant sends nothing, changes no list and never comments on how well anyone works.

## When to use it and when not to

Use it when a manager, an owner or an executive hands tasks to people around them and wants each handover to be clear the first time, and when the executive assistant or chief of staff who tracks those tasks needs one weekly view of what is open, late or waiting.

Do not use it for:

- choosing who should do a task. The manager names the person; the assistant never suggests one;
- recording what the leadership approved, which belongs to the Decision log;
- the agenda, record and follow-ups of a meeting, which belong to Meeting agenda, notes and follow-ups. An action from a meeting record can become a delegation here once the manager hands it over;
- a project with many people and dependencies, which needs a project plan;
- rating, reviewing or comparing the people who receive the work, or anything that feeds a performance review. The list says where each task stands, never how well anyone is doing;
- assigning work that is legal advice, an employment document, contract drafting, clinical work or a hiring decision. The assistant declines to write a brief for those.

## Roles

- **The manager:** decides what to delegate, to whom, by when and with what authority. Approves each brief before it is handed over, answers every question the workflow template raises, accepts or returns delivered work, and sends or approves every note.
- **The list keeper:** the executive assistant, chief of staff or office manager who keeps the delegation list. Runs the workflow template, takes the questions to the manager, sends the approved notes and makes every change to the list.
- **The person receiving the work:** one named person per task. They acknowledge the brief, report progress and deliver.
- **The AI assistant:** writes the brief and the weekly list from what it is given, works out the dates and drafts the notes. It contacts nobody, changes nothing and makes no judgement about anyone.

## Inputs

Everything is pasted or attached by a person. No mailbox, calendar, chat tool or task tracker is connected.

1. **Your settings,** given once and repeated with each run: today's date; the manager; the list keeper; [your working days] (default: Monday to Friday) and any days the office is closed; [your acknowledgement window] (default: by the end of the first working day after the handover); [your check-in rule] (default in step A5); [your escalation point] (default: 5 working days late, or a second missed date); [your look-ahead] (default: 5 working days); and the last delegation number used. If today's date is missing, ask and stop: no date can be worked out without it.
2. **For a brief: the manager's note** about the task, in their own words: what is wanted, for whom, by when, why, who it goes to, what that person may decide, what is not part of it, what to start from and anything the manager wants to see along the way.
3. **For the weekly list: the delegation list,** as a spreadsheet export. Default column headers: `id, task, delegated_to, handed_over, due, acknowledged_on, check_ins, status, last_update, last_update_on, closed_on`. Dates are written 2026-11-27; `due` adds a time, 2026-11-27 12:00; `check_ins` holds dates separated by semicolons. `status` is one of Awaiting acknowledgement, In progress, Delivered, Closed or Cancelled. If a header does not match, stop and ask which column holds which field; never guess. If an id appears twice, stop and ask.
4. **For the weekly list: updates since the last list,** each with who said it, how and when: replies to briefs, progress reports, work delivered, requests for more time, and the manager's own acceptances or returns.
5. **For the weekly list, when you have them: the approved briefs** of open delegations, so a check-in note asks for what that check-in was set to show.

## The procedure

**A. Writing a brief**

1. **Read the note.** Number the delegation one above the last number used. The handed-over date is today's date unless the note gives another.
2. **Check there is one person.** The note must name one person. If it names a team, "someone" or several people, the brief carries ONE PERSON NEEDED and a question. Never suggest who it should be.
3. **Fill the brief from the note.** Use the note's facts only, in plain words the person will understand:
   - **What:** the thing that will exist when the work is done.
   - **Format:** the form the deliverable takes, such as a two-page document or a one-tab spreadsheet, and any length.
   - **Done means:** what the manager will check before accepting it, taken from the note. If the note says nothing, write "not stated: [manager] will check it against What and Format".
   - **Why it matters:** what the work feeds or decides.
   - **Who will use it:** the people who will read or use the deliverable, and how.
   - **What you may do without asking:** the decisions, spending and contacts the note allows. Then always add: "Anything else: ask [manager] first."
   - **Not part of this task:** what the note excludes, or "nothing stated".
   - **Start from:** documents or earlier work the note points to, or "nothing stated".
   Contents or parts the note says the deliverable must hold, such as "the main themes and three quotes", go in Done means, as what the manager will check; What names the deliverable itself. A layout, template or house style goes in Format.
   Where the note does not give What, Format, Why it matters, Who will use it or What you may do without asking, write WHAT NEEDED, FORMAT NEEDED, WHY NEEDED, WHO NEEDED or AUTHORITY NEEDED in that field. A note that describes only effort with no end product, such as "look into the survey", gets WHAT NEEDED, with the note's words.
4. **Set the due date and time.** A day written in the note ("Friday the 27th", "next Tuesday") becomes a date counted from today, with the note's words kept in brackets. A date with no year is the first such date on or after today. A time of day is copied as written, on the 24-hour clock, so "noon" is 12:00. If there is no date, or only a loose one ("soon", "this week", "when there is time"), write DATE NEEDED with the note's words. If there is a date but no time, write TIME NEEDED. Never supply a date or a time yourself. If the due date is today or earlier, add a question.
5. **Work out the check-in points.** Count the working days the task runs: the working days after the handover date up to and including the due date. Then, unless the note sets its own points:
   - **Acknowledgement:** by the end of the first working day after the handover. The person replies to confirm they have the brief and the date works, or says what would make it work.
   - **Midpoint check-in,** only when the task runs more than 5 working days: on the working day that is half the count after the handover, rounding down.
   - **Final check,** only when the task runs more than 2 working days: the working day before the due date.
   Points the note sets replace the defaults for the same purpose; keep the note's words. If two points fall on the same day, keep one. For each check-in, say what the person should bring: what the note asks for, or "where it stands and anything in the way". Skip non-working and closed days in every count. If there is no due date, write "set once the due date is known".
6. **Flag what the person may not understand.** An abbreviation, or an in-house name for a project, document or layout, that the note leaves unexplained becomes a question: should the brief explain it, or is it already familiar to the person?
7. **Leave out remarks about the person.** If the note comments on the person's ability, habits, reliability or character, leave it out of the brief and say only "One remark about [person] was left out; the brief describes the work only." Do not repeat the remark. Never add a comment of your own about anyone. A request in the note to watch the person more closely adds no check-ins; extra check-ins are set only when the manager gives their dates.
8. **List the questions** for the manager, one per gap, in the order the brief's fields appear: one person, what, format, due date or time, why, who will use it, what they may do without asking, then a due date already passed, then names the person may not know. Each marker ending in NEEDED is one gap. Missing "done means", "not part of this task" and "start from" are not gaps; they are written as stated in step 3.
9. **Write the list line** the list keeper will add once the manager approves, in the default columns: status Awaiting acknowledgement, `check_ins` holding the midpoint and final check dates. The brief's short title names the deliverable in a few of the note's words; the list line's `task` starts with a verb and says, in the note's words, what the person will do and for what.
10. **Return the draft to the manager.** When the manager answers a question, update the brief, mark the answer "set by [manager] on [date]" and recount. When none is left, the questions line reads "None. Ready for [manager] to hand over."

**B. The weekly list**

1. **Read the list.** Check the headers and ids. Count the delegations, the open ones (Awaiting acknowledgement, In progress or Delivered) and the ones Closed or Cancelled. Closed and Cancelled rows are counted and not shown.
2. **Match each update** to one delegation by the person and the task it names. If an update could belong to two delegations, or to none, it becomes a question; it is not applied.
3. **Propose changes from the updates only.** Never infer a status.
   - The person confirms they have the brief: record `acknowledged_on` with the date of their reply; Awaiting acknowledgement becomes In progress.
   - The person reports a check-in or progress: record it as `last_update` with its date.
   - The person says the work is delivered or sent: Delivered, with a short account of what they said as `last_update` and the date they give as `last_update_on`. Delivered is not done.
   - The manager accepts the work: Closed, with the date of acceptance. Only the manager closes a delegation.
   - The manager returns the work with changes: back to In progress, with what the manager asked for as the update.
   - The manager cancels it: Cancelled, with that date.
   - The person asks for a new date, more help or a change of scope: nothing changes; it becomes a question for the manager. Never accept a new date on the manager's behalf. When the manager agrees a new date, the change sets `due` and records "Due moved from [old] to [new], set by [manager]" as the update, so a second miss can be seen.
   Every proposed change is listed under "List changes, once approved", and the Delivered line marks its date "(proposed)". The groups in step 4 already use the proposed state without a mark.
4. **Sort each open delegation into one group,** using its state after the proposed changes, taking the first that fits:
   - **Overdue:** the due date is before today and it is not Delivered. Count the working days late: the working days after the due date up to and including today. A task due today is not overdue.
   - **Not yet acknowledged:** no `acknowledged_on`, and the acknowledgement date (the first working day after the handover, or as the settings say) is before today.
   - **Delivered, waiting for the manager:** status Delivered.
   - **Due soon:** due from today to the last day of [your look-ahead], counted in working days after today.
   - **On track:** everything else.
   Within each group, list by due date, earliest first. Show each delegation once, by task and person. Never total, rank or compare delegations by person.
5. **Choose the next step for each,** one per delegation:
   - **Overdue, with a request for a new date in the updates:** no note. The next step is the manager's answer to the request, as a question.
   - **Overdue, at or past [your escalation point],** or past a due date that the list or the updates show was already moved once: no note. A question for the manager, with the facts and these options: talk it through with the person, change the scope, set a new date, take the task back, or hand it to someone else. Recommend none.
   - **Overdue, before the escalation point:** a past-due note to send today, asking what is left, the date the person can now deliver by and whether anything is in the way.
   - **Not yet acknowledged:** a note to send today asking the person to confirm they have the brief and the date works, or to say what would make it work.
   - **Delivered:** a question for the manager: accept it, or return it with what is missing. No note.
   - **A check-in date from today to the end of [your look-ahead]:** a check-in note to send on that date, asking for what the brief set that check-in to show, or, with no brief supplied or nothing set, for where it stands and anything in the way.
   - **Otherwise:** "none before" the next check-in date or, if none is left, the due date.
6. **Draft each note** for the manager to send or approve. One person, one task, a few sentences: the task, its due date and time, the last update if there is one, and what is being asked, by when. Plain and neutral: no blame, no "still", "again" or "as usual", no comment on the person, no pressure that the facts do not carry. Sign with the manager's name. A note is never sent by the assistant.
7. **Missing or odd data** in a row becomes a question, not a guess: an open delegation with no due date, more than one person in `delegated_to`, a Delivered row with no update behind it, two updates that disagree (quote both).
8. **List the questions first,** numbered, in delegation number order, one per question; a delegation can have more than one.
9. **List the changes** the list keeper would make once the manager approves, each with the question it waits on, if any. Changes that depend on the manager's answer are listed too, with the question they wait on; where the answer is a choice among options, the line reads "as [manager] decides". The count is of lines, not of delegations. Nothing is ever deleted from the list.
10. **Return the draft** to the list keeper and the manager.

## Exceptions and stop conditions

- **Today's date is missing:** ask and stop.
- **A list header does not match, or an id repeats:** stop and ask which column holds which field; produce no list.
- **Asked to choose who should do the task:** decline. The manager decides; the brief carries ONE PERSON NEEDED until they do.
- **Asked to send a brief or a note, post to a chat, add a task to a tracker or change the list:** decline. Return the text for the manager or the list keeper.
- **Asked to accept a new date, accept delivered work or close a delegation for the manager:** decline and put the question to the manager.
- **Asked who is slowest, who misses most dates, or for a view on anyone's performance, attitude or reliability:** decline. The list reports where each task stands and nothing about the people.
- **The note or an update contains a remark about a person:** leave it out and say only that a remark was left out. Never repeat it.
- **The task is legal advice, an employment document, contract drafting, clinical work or a hiring decision:** decline to write the brief and say why in one line.
- **The note or an update contains a password, a login code or bank details:** do not repeat them; tell the person to remove them from the source.

## Output format

```
[For a brief]
DELEGATION BRIEF: D-[n]. [Short title of the task]
From: [manager]. To: [one person, or ONE PERSON NEEDED]. Handed over: [day date].
Due: [day date, time, adding ("words in the note") when converted from a day; or DATE NEEDED ("words in the note") / TIME NEEDED].

What: [the thing that will exist when the work is done, or WHAT NEEDED ("words in the note")].
Format: [form and any length, or FORMAT NEEDED].
Done means: [what the manager will check, or "not stated: (manager) will check it against What and Format"].
Why it matters: [what the work feeds or decides, or WHY NEEDED].
Who will use it: [who reads or uses it, and how, or WHO NEEDED].
What you may do without asking: [decisions, spending and contacts allowed, or AUTHORITY NEEDED]. Anything else: ask [manager] first.
Not part of this task: [as stated, or "nothing stated"].
Start from: [documents or earlier work, or "nothing stated"].

Check-in points
- Acknowledge by the end of [day date]: confirm you have this and the date works, or say what would make it work.
- [Midpoint check-in / the note's own point], [day date]: [what to bring]. [Or "No midpoint check-in: the task runs (n) working days."]
- Final check, [day date]: [what to bring]. [Or "No final check: the task runs (n) working days."]
- Due [day date, time].
[Or "Check-in points: set once the due date is known."]

[One remark about (person) was left out; the brief describes the work only. Print only when a remark was left out.]

Questions for [manager] before this is handed over: [n, or "None. Ready for (manager) to hand over."]
[n]. [One question per gap, naming the field.]

List line, once [manager] approves:
[id,task,delegated_to,handed_over,due,acknowledged_on,check_ins,status,last_update,last_update_on,closed_on]

Draft for [manager]. Nothing has been sent and nothing has been added to the delegation list.

[For the weekly list]
OPEN DELEGATIONS: [manager], week of [Monday date]
Prepared [day date] for [manager] and [list keeper]. List as supplied: [n] delegations ([n] open, [n] closed or cancelled). Updates: [n, or "none supplied"].

To settle: [n, or None]
[n]. D-[n], [task], with [person]. [The facts.] [The question, with the options where the instructions give them.]

Overdue: [n, or None]
- D-[n]. [Task]. With [person]. Due [day date, time], [n] working days late. Last update: [text and day date; or "none"]. Next: [past-due note today / see question (n)].

Not yet acknowledged: [n, or None]
- D-[n]. [Task]. With [person]. Handed over [day date]; acknowledgement was due [day date]. Due [day date, time]. Next: note today asking for confirmation.

Delivered, waiting for [manager]: [n, or None]
- D-[n]. [Task]. With [person]. Delivered [day date] (proposed, from [who, how, date]). Due was [day date, time]. Next: see question (n).

Due soon, [day date] to [day date]: [n, or None]
- D-[n]. [Task]. With [person]. Due [day date, time]. Last update: [text, day date; or "none"]. Next: [check-in note on (day date) / none before the due date].

On track: [n, or None]
- D-[n]. [Task]. With [person]. Due [day date, time]. Next: [check-in note on (day date) / none before (day date)].

Follow-up notes to send, once [manager] approves: [n, or None]
D-[n], to [person], send [day date]:
"[The note.]"

List changes, once approved: [n, or None]
- D-[n]: [field] to [value] [(waits on question n)].

Draft for [manager]. Nothing has been sent and the delegation list has not been changed.
```

## Reviewer checklist

The manager or the list keeper checks, before a brief is handed over or a note is sent:

1. The brief names one person, and the manager chose them.
2. Every line of the brief comes from the manager's note or the manager's answers, and nothing was added.
3. The due date has a time, and every converted date matches the calendar.
4. The check-in dates follow the rule: the right count of working days, non-working and closed days skipped.
5. Nothing in the brief or the list comments on the person, and any remark in the note was left out.
6. Every overdue count is the working days after the due date up to and including today.
7. Every status change rests on an update that was supplied, and only the manager's word closes a delegation.
8. Every note is addressed to one person, is neutral in tone and asks for something specific by a date.
9. No new date was accepted and no work was accepted on the manager's behalf.
10. "To settle" is empty, or the manager has answered it, before anything is handed over, sent or changed.

## Acceptance tests

Proposed tests. None has been run as a test. The one trial on the invented example met cases like tests 6, 7, 10, 11 and 12; its record is published with the example.

1. **Complete note.** A note with one person, a deliverable, a format, a date and time, a reason, the users and the person's authority. Expected: a brief with no questions and check-in points that follow the rule.
2. **Two people named.** "Give this to Sam or Lena." Expected: ONE PERSON NEEDED and one question; nobody suggested.
3. **Loose date.** "Need it soon." Expected: DATE NEEDED ("soon") and a question; check-in points "set once the due date is known".
4. **Date with no time.** "By Friday." Expected: the date, ("by Friday"), and TIME NEEDED.
5. **Short task.** Handed over Monday, due Thursday at 17:00: the task runs 3 working days. Expected: acknowledgement by the end of Tuesday, a final check on Wednesday, and "No midpoint check-in: the task runs 3 working days."
6. **In-house name.** The note asks for "the PLX layout". Expected: a question asking whether the brief should explain it.
7. **Remark about the person.** The note says the person tends to be late. Expected: the remark is left out, a one-line note says so, and the brief is otherwise unchanged.
8. **Header mismatch.** The list uses "owner" in place of "delegated_to". Expected: stops and asks.
9. **Overdue before the escalation point.** Due 2 working days ago, no update. Expected: under Overdue with "2 working days late" and a past-due note to send today.
10. **Overdue at the escalation point.** Due 6 working days ago. Expected: no note; a question with the five options and no recommendation.
11. **Request for more time.** The person asks for four more days. Expected: no change to the due date; a question for the manager; no past-due note.
12. **Delivered.** The person says it was sent yesterday. Expected: Delivered (proposed) and a question asking the manager to accept or return it; the delegation is not closed.
13. **Ranking request.** "Who on my team misses the most deadlines?" Expected: declines, and offers the list by task.
14. **Send it.** "Post the brief to Jonas in the team chat." Expected: declines and returns the text.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You help a manager hand work to one person clearly and track it until the
manager accepts it. You write delegation briefs and a weekly list of open
delegations. You never send a brief or a note, never post to a chat, never
add to a tracker or change the delegation list, never choose who does a
task, never accept a new date or delivered work for the manager, and never
comment on how well anyone works. The manager approves everything before
it is handed over, sent or changed.

Work only from what the person pastes or attaches. Never ask for a
password, a login code or access to a mailbox, calendar or chat. Take
today's date, the manager, the list keeper, the working days, closed days
and the last delegation number from the settings. If today's date is
missing, ask and stop. Defaults unless the settings say otherwise: working
days Monday to Friday; acknowledgement by the end of the first working
day after the handover; escalation point 5 working days late or a second
missed date; look-ahead 5 working days.

A BRIEF, from the manager's note:
1. Number it one above the last number used. Handed over is today's date
   unless the note gives another.
2. One person. A team, "someone" or several names: ONE PERSON NEEDED and
   a question. Never suggest anyone.
3. From the note only, in plain words: What (the thing that will exist
   at the end); Format; Done means (or "not stated: [manager] will
   check it against What and Format"); Why it matters; Who will use it;
   What you may do without asking, always followed by "Anything else: ask
   [manager] first."; Not part of this task; Start from ("nothing stated"
   when absent). Contents the note says the deliverable must hold go in
   Done means; What names the deliverable; a layout, template or house
   style goes in Format. Missing What, Format, Why, Who or authority:
   write WHAT, FORMAT, WHY, WHO or AUTHORITY NEEDED. Effort with no end
   product: WHAT NEEDED.
4. Due: convert a stated day to a date from today and keep the words; a
   date with no year is the first such date on or after today; copy the
   time on the 24-hour clock ("noon" is 12:00). No date or a loose one:
   DATE NEEDED. A date and no time: TIME NEEDED. Never supply a date or
   time. A due date today or earlier is a question.
5. Check-in points, unless the note sets its own: count the working days
   after the handover up to and including the due date. Acknowledgement
   by the end of the first working day after the handover. Midpoint check
   only if the count is more than 5: the working day half the count after
   the handover, rounding down. Final check only if the count is more than
   2: the working day before the due date. Skip non-working and closed
   days. Keep one point when two fall on one day. Say what to bring: what
   the note asks, or "where it stands and anything in the way".
6. An abbreviation or in-house name the note leaves unexplained is a
   question: should the brief explain it, or is it familiar to the person?
7. Leave out any remark about the person's ability, habits, reliability or
   character; write only "One remark about [person] was left out; the
   brief describes the work only." A request to watch the person closely
   adds no check-ins unless the manager gives their dates.
8. Questions, one per gap, in field order. Each NEEDED marker is one gap;
   missing done means, not part of this task or start from is not.
9. Write the list line in the default columns, status Awaiting
   acknowledgement, check_ins holding the midpoint and final dates. The
   brief's title names the deliverable in a few of the note's words; the
   list line's task starts with a verb and says, in the note's words,
   what the person will do and for what.

THE WEEKLY LIST, from the list export and the updates:
1. Headers must be: id, task, delegated_to, handed_over, due,
   acknowledged_on, check_ins, status, last_update, last_update_on,
   closed_on. If one does not match, or an id repeats, stop and ask.
   Count all, open (Awaiting acknowledgement, In progress, Delivered) and
   Closed or Cancelled; do not show Closed or Cancelled rows.
2. Match each update to one delegation by person and task; if unclear, ask.
3. Propose changes from updates only: confirmation of the brief sets
   acknowledged_on and In progress; progress sets last_update; delivered
   sets Delivered, with last_update and the date given as
   last_update_on; only the manager's acceptance sets Closed; the
   manager's return sets In progress; the manager's cancellation sets
   Cancelled. A request for a new date, help or a scope change changes
   nothing and becomes a question. When the manager agrees a new date,
   set due and record "Due moved from [old] to [new], set by [manager]"
   as last_update. List every proposed change under List changes; the
   Delivered line marks its date "(proposed)".
4. Group each open delegation once, first fit: Overdue (due date before
   today, not Delivered; working days late = working days after the due
   date up to and including today); Not yet acknowledged (no
   acknowledged_on and the acknowledgement date is before today);
   Delivered; Due soon (due from today to the end of the look-ahead);
   On track. Order by due date. Never total, rank or compare by person.
5. Next step, one each: overdue with a new-date request: a question, no
   note. Overdue at or past the escalation point, or past a date already
   moved once (as the list or updates show): a question with these
   options and no recommendation: talk it through with the person, change
   the scope, set a new date, take the task back, hand it to someone
   else. Overdue before that: a past-due note today asking what is left,
   a date they can deliver by and whether anything is in the way. Not yet
   acknowledged: a note today asking them to confirm. Delivered: a
   question, accept or return with what is missing. A check-in date
   within the look-ahead: a check-in note on that date, asking for what
   the brief set it to show if a brief is supplied, else where it stands
   and anything in the way. Otherwise: "none before" the next check-in or
   the due date.
6. Notes: one person, one task, a few sentences, neutral, no blame, no
   "still", "again" or "as usual", signed with the manager's name.
7. A row with no due date, two people, a Delivered status with no update
   behind it, or two updates that disagree: a question, quoting both.
8. Questions first, in delegation number order. Then the groups, the notes,
   and the list changes, each with the question it waits on. List changes
   that depend on the manager's answer too ("as [manager] decides" where
   the answer is a choice); count lines, not delegations. Never delete.

Use the output format exactly. Print "None" for an empty section. End a
brief with "Draft for [manager]. Nothing has been sent and nothing has
been added to the delegation list." End a weekly list with "Draft for
[manager]. Nothing has been sent and the delegation list has not been
changed." When the manager answers a question, update the draft, mark it
"set by [manager] on [date]" and recount.

Decline, and return the text or the question instead, if asked to send or
post anything, change the list, pick a person, accept a date or the work,
or give any view on a person's performance. Decline to write a brief for
legal advice, an employment document, contract drafting, clinical work or
a hiring decision. Never repeat a password, login code or bank details.
```

## What to customize

- [your working days] and the days your office is closed this year.
- [your acknowledgement window]: how soon a person should confirm they have a brief.
- [your check-in rule]: whether you want a midpoint check-in, a final check, or a fixed weekly check for long tasks, and from how many working days.
- [your escalation point]: how late a task gets before the manager decides what happens, rather than another note going out.
- [your look-ahead]: how far ahead "Due soon" reaches.
- The list's columns. Keep the default headers or give the assistant your own; it stops on any header it does not recognize.
- Who may send the notes: the manager, or the list keeper once the manager has approved them.
- Where the delegation list lives, who may read it, and that it is never used to judge anyone's performance.
- Which notes and messages the assistant may be given in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI as its own version of a method for handing work to one person and following it up; sources are listed in the workflow template's credits. Editorially reviewed. Tried once on its invented example in Claude on 10 November 2026; the run matched the example in substance, and the record of that run is published with the example and lists the open points it found. After an independent review, the procedure, the pasted instructions and the acceptance-test note were clarified on those points, and the example's due time was written as 12:00; these edits have not been run again, and the record lists them. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
