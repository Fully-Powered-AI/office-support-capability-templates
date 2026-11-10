# Meeting agenda, notes and follow-ups: one trial on its invented example

- **Product:** Claude Code
- **Model:** Claude Fable 5.2
- **Date:** 2026-11-09
- **Runs:** one, on the instructions as they now stand

The inputs are the invented example published with this template. The company, its people, its figures and its jobs are invented, and no client data was used. This is a record of one run on that example. It is not a test in any company's environment.

An earlier run on the same day, on an earlier wording of the instructions, came out differently from the published example in several places. The instructions and the example were corrected afterwards, and the template was run again. This page records the second run. What the first run found, and what was changed, is at the end.

## Inputs used

Exactly what Priya supplies in [the example](example.md), and nothing else:

- before the meeting: the basics (today's date, the meeting's name, date, start and length, the five people), her five topics as she typed them, and the three open actions from 27 October;
- after the meeting: the agenda she sent, with her answer on parts returns ("agree who owns returns and what the process is"), and her notes of 3 November with that day's date;
- the settings: reading goes out one working day before, a 5-minute read-back, the follow-up to everyone invited, and the default held-back subjects.

Each part was run in a new session of Claude Code, started with no files and given one message: the template's instructions for an AI assistant as written, the template's output format, and the inputs for that part. The session was not shown the example's output.

## What came out

Both parts ran to the end. Nothing in the instructions told the assistant to stop. The complete output follows, as returned.

### Before the meeting

```
DRAFT AGENDA: Weekly operations meeting
Tue 3 Nov 2026, 9:00 to 9:45 (45 minutes). Run by: Priya (ops manager).
Invited: Marcus (service manager), Elena (install manager), Tom (warehouse lead), Jo (office manager).

To settle before this goes out: 3
1. The agenda runs over. Topics total 45 minutes and the read-back takes 5, which makes 50 against a length of 45: 5 minutes over. The agenda below shows my proposal: take "Install backlog update" (Inform, 10 min) off the agenda and have Elena send it in writing, which leaves 5 minutes spare. Do you accept this, or would you rather make a different change?
2. New scheduling software has no lead, no minutes and no outcome, so it is not on the timed agenda. Who leads it, how many minutes does it get, and what should the meeting settle? Under the proposal above only 5 minutes are spare.
3. Parts returns: what should the meeting settle? It is on the agenda as "Discuss: [outcome needed]" with Tom as lead, from your note that Tom wants to talk about it.

Read before the meeting, sent by Mon 2 Nov 2026:
- Install backlog update, in writing (Elena). Taken off the timed agenda under the proposal in question 1.

1. 9:00 to 9:15 (15 min). Winter on-call rota. Decide: pick between 1-week and 2-week rotations. Lead: Marcus.
2. 9:15 to 9:25 (10 min). Van 7. Decide: repair or replace; the quote is $6,200 to repair. Lead: Tom.
3. 9:25 to 9:35 (10 min). Parts returns. Discuss: [outcome needed]. Lead: Tom.
   9:35 to 9:40 (5 min). Spare.
4. 9:40 to 9:45 (5 min). Read-back. Each decision and action said back to the room
   with who owns it and when it is due, then the open actions below.
   Lead: Priya.

Open from last time (27 Oct 2026):
- Send revised call-out price sheet to dispatch. Owner: Jo. Due 30 Oct 2026.
- Confirm crane date for the Larch Street job. Owner: Elena. Due 2 Nov 2026.
- Order two CO monitors. Owner: Marcus. Due 6 Nov 2026.

Note-taking key: D decision. A action, owner and due date. P parked. Q question. F fact.

Draft for Priya. Nothing has been sent and no invitation has been changed.
```

### After the meeting

```
MEETING RECORD: Weekly operations meeting
Tuesday 3 November 2026. Run by: Priya. Present: Marcus, Elena, Tom. Absent: Jo.
Source: Priya's notes, supplied Tuesday 3 November 2026.

To settle before this goes out: 5
1. A2, the lease quote for van 7: the notes say "someone needs to get a lease quote". Who owns it, and by what date?
2. A3, the parts returns process: the notes name both Tom and Marcus. Which one owns it, and by what date? The agenda also asked who owns returns, and the notes do not say.
3. A4, Tom's call to the supplier: the notes say "this week". What date?
4. Q1, a second dispatcher for winter: who finds out, and by when?
5. The revised call-out price sheet (Jo, due 30 October): the notes say "don't know if sent". Was it sent? This is a question for Jo.

Decisions
D1. The winter on-call rota runs on two-week rotations, starting 16 November. Decided by: not stated in the notes.
D2. Install techs on the rota cover weekends only, to be revisited after January. Decided by: not stated in the notes ("agreed").

Actions
A1. Publish the winter on-call rota. Owner: Marcus. Due: Friday 6 November 2026 ("by Fri").
A2. Get a lease quote to compare with the van 7 repair quote. Owner: OWNER NEEDED. Due: DATE NEEDED.
A3. Produce a parts returns process ("sort out a process"). Owner: ONE OWNER NEEDED: Tom, Marcus. Due: DATE NEEDED.
A4. Call the supplier and report what unreturned parts it will still take back. Owner: Tom. Due: DATE NEEDED ("this week").

Parked
P1. Van 7: repair or replace. Not decided: the repair quote went up, and there is no replacement price to compare it with. Comes back when: the replacement price is in hand (see A2; no date stated).

Open questions
Q1. Do we need a second dispatcher for winter? Who finds out: NEEDED. By when: NEEDED.

Open from last time (27 October)
- Send revised call-out price sheet to dispatch. Owner: Jo. Due 30 October. Not known: "Jo not here, don't know if sent". Due date passed.
- Confirm crane date for the Larch Street job. Owner: Elena. Due 2 November. Done: "Elena confirmed, 12 Nov".
- Order two CO monitors. Owner: Marcus. Due 6 November. Done: "Marcus ordered, arriving next week".

For the record
- The meeting started at 9:05 (agenda: 9:00).
- Van 7 repair quote: "went up to 6,800 after they opened it up", per Tom (agenda: $6,200).
- Parts returns: "$4k of unreturned parts sitting in the warehouse, some past the supplier's 30 day window".
- Install backlog, per Elena: 23 jobs, 3 waiting on permits.
- Crane date for the Larch Street job: 12 November.
- CO monitors: ordered, arriving next week.
- Two-week on-call rotations start 16 November.

Held back: one item, the reason for a person's absence (health), for Priya only.

Next meeting
Date: not stated in the notes. Proposed topics: van 7, repair or replace, with the lease quote (P1, A2); the parts returns process and what the supplier will take back (A3, A4); a second dispatcher for winter (Q1); the published on-call rota (A1); the revised call-out price sheet (open from last time).

FOLLOW-UP DRAFT. NOT READY TO SEND: 5 gaps.
To: Marcus, Elena, Tom, Jo
Subject: Weekly operations meeting, Tuesday 3 November 2026: decisions and actions

Decided:
- The winter on-call rota runs on two-week rotations, starting 16 November.
- Install techs on the rota cover weekends only. We revisit this after January.

Actions:
- Marcus: publish the winter on-call rota by Friday 6 November.
- [OWNER AND DATE NEEDED]: get a lease quote to compare with the van 7 repair quote.
- [ONE OWNER NEEDED, Tom or Marcus, AND DATE NEEDED]: produce a parts returns process.
- Tom: call the supplier and report what unreturned parts it will still take back by [DATE NEEDED: "this week"].

Not decided: Van 7, repair or replace. The repair quote went up to 6,800 (it was $6,200 on the agenda), and we need a replacement price to compare. It comes back when we have that price.
Still open:
- Do we need a second dispatcher for winter? [WHO FINDS OUT AND BY WHEN NEEDED]
- [Jo: was the revised call-out price sheet, due 30 October, sent to dispatch?]

From last time: the crane date for the Larch Street job is confirmed for 12 November. The CO monitors are ordered and arrive next week.

If any of this is not what you agreed to, tell Priya today.

Draft for Priya. Nothing has been sent and no record has been changed.
```

## What was observed

Every required part was produced: the agenda with its "To settle" list first, the timed topics, the spare line, the read-back, the open actions and the note-taking key; then the record with decisions, actions, parked items, open questions, last time's actions, the facts, the held-back line, the next meeting and the follow-up draft headed "NOT READY TO SEND". No owner and no date was supplied by the assistant. The one stated day ("by Fri") became Friday 6 November with the words kept. The figure that changed ($6,200 on the agenda, $6,800 in the notes) is shown both ways. The reason for Jo's absence appears only as a held-back item. Nothing was sent.

Against the reviewer checklist: items 2, 3, 4, 5, 6 and 8 hold for this output. Item 1 does not hold yet (one topic has no outcome) and item 7 does not hold yet (five gaps are open). Both are the intended state of a first draft: the person who runs the meeting settles them. The second half of the work, updating the record once the gaps are answered, was not run, because the example's inputs do not include the answers.

Where this run agrees with the published example: the meeting's name; the timed agenda with the proposal applied, 5 minutes spare and the backlog update as the only reading; the three questions before the meeting; the person who runs the meeting named under "Run by" only; two decisions, each with its own "Decided by"; four actions with the same owners, dates and missing pieces; one parked item; one open question; five gaps; the price sheet marked "Not known" and "due date passed"; the held-back item; and the recipients of the follow-up.

Where it differs from the published example:

- **Order and numbering.** The two questions about topics come in the other order. The parts returns process is A3 and Tom's call is A4; the example has them the other way round.
- **Wording.** The run keeps more of the person's words ("pick between 1-week and 2-week rotations", "install techs") and quotes the notes in several lines. The example rewords them.
- **Dates.** The agenda's dates are written as the person typed them ("Tue 3 Nov 2026"). The example writes them out in full.
- **For the record.** The run lists seven facts, three of which repeat what is already under decisions or last time's actions. The example lists four.
- **The follow-up draft.** The run adds a short "From last time" paragraph, which the output format does not have. It writes the missing owners and dates in capitals inside the brackets; the example uses lower case.
- **Next meeting.** The run also proposes the published rota (A1) as a topic.
- **The agenda's aim for parts returns.** The agenda asked the meeting to agree who owns returns, and the notes show no owner agreed. The run mentions this inside the question about A3. The example does not mention it.

Where the instructions were still unclear, or the assistant had to guess:

1. The inputs never say outright who runs the meeting. The assistant took it to be Priya because she wrote "Me" and supplied the topics.
2. "Parts returns - Tom wants to talk about it" gives no lead in so many words. The assistant showed Tom as lead and asked.
3. "Revisit after January" is a loose return point attached to a decision. The rule for loose dates covers actions, and the return-point rule covers parked items. The run kept the words as a condition of the decision and raised no gap.
4. On the agenda, "due date passed" is judged against today's date. Jo's action was due on the day the agenda was drafted, so it carries no mark, though it would be overdue by the meeting.
5. Nothing says where to note a difference between the agenda's aim and what the notes show, when no figure is involved.
6. Nothing says how many facts belong under "For the record", or whether a fact already shown elsewhere is repeated there.
7. The output format wraps its long lines; the run did not wrap all of its own. Nothing says which is wanted.
8. The style of dates is left to the company's house style, which this run was not given.

None of these stopped the run. Each is a place where two careful runs could come out differently.

## The earlier run, and what was changed

The first run, on the earlier wording, differed from the example as it then stood in ways that mattered. Each was dealt with before the second run:

- The example applied its own time proposal and the run kept the times as given, ending at 9:50. The instructions now say the timed agenda shows the proposal applied and that the question says so.
- The example listed a repair quote as reading that nobody had supplied. That line was removed from the example, and the instructions now say to list only reading the person supplied or a topic the proposal turned into reading.
- The example called the meeting "Weekly operations meeting" when Priya had typed "Ops meeting". Her input now gives the full name, and the instructions say to keep the person's own name for the meeting.
- The run listed Priya among those invited, present and receiving the follow-up; the example did not. The instructions now say the person who runs the meeting is named under "Run by" only.
- The run entered Tom's call to the supplier as an action and again as an open question. The instructions now say to enter each thing once.
- The run held back the reason for Jo's absence and the example said nothing was held back. The instructions now name the reason for an absence as a held-back subject, and the example shows it held back.
- The run gave "Decided by" under each decision and the example gave it once. The instructions and the output format now ask for it under each decision.
- The instructions did not say which kind of topic one with no outcome is, how to count an item missing both an owner and a date, or that the output format has to be pasted with the instructions. All three are now stated.
- The notes carried no date of their own. Priya's notes now give the day's date, and the instructions say to take today's date from the person.
