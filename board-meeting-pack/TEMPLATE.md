# Board meeting pack

Workflow template, version 0.1.0.

## Purpose

Prepare one board meeting's papers for the CEO. Before the meeting: a pre-read that opens on the one decision the board is asked to make, the three messages behind it and the evidence for each, a standing page of figures against plan, the risks, a timed agenda kept mostly for discussion, the questions directors are likely to ask and who the CEO should speak to beforehand. After the meeting: a draft record of what was decided, who owns each action and by when, and what directors were promised. Every figure comes from a report the person supplies and names that report. The CEO chooses the ask and decides what goes to directors. The assistant never sends anything, never changes a record and never chooses the decision.

## When to use it and when not to

Use it for a regular or special meeting of a company's board, or of a nonprofit's board of trustees, where the CEO or executive director presents and the board can decide something. Start it ten days to two weeks before the meeting, once the period's management reports are final, and run it again with the meeting notes on the day the meeting ends.

Do not use it for:

- the formal minutes or the wording of a resolution. The company secretary, or whoever the company names, writes those in the company's own form; the draft record here is an input to them;
- a monthly or quarterly update letter to investors that asks for no decision;
- a review with a customer, which is the quarterly business review preparation workflow template;
- setting anyone's pay, reviewing the CEO's performance or planning a CEO change;
- valuation, the terms of a funding round, or questions about directors' legal duties, which go to the company's lawyer;
- building the financial statements themselves. The finance team prepares the reports; this workflow template reads them.

## Roles

- **Runs it:** the CEO, or whoever assembles the board papers for them: a chief of staff, an executive assistant, the finance lead or the company secretary.
- **Decides:** the CEO. They choose the ask and the recommendation, settle every question the draft raises, decide what goes to directors and send the pack.
- **Owns the figures:** the finance lead. They confirm every figure against the report it came from and settle any two reports that disagree.
- **The board:** reads the pack, discusses and decides. The chair confirms the record of what was decided.
- **Keeps the formal minutes:** [your minute keeper] (default: the company secretary).
- **The AI assistant:** prepares drafts, checks figures against the reports and lists every gap. It contacts nobody.

## Inputs

Everything is pasted or attached by a person. No accounting system, mailbox, calendar or board portal is connected, and the assistant never asks for a password or a login code.

Before the meeting:

1. **The meeting:** company name, meeting date, start time and length, place or video link, the CEO, who else from management attends, the directors with their roles (chair, investor director, independent, observer), the dates of the last three meetings, and today's date. If the length or the date is missing, stop and ask.
2. **The CEO's brief:**
   - the one decision the board is asked to make, worded as the CEO wants it;
   - the CEO's recommendation and what it gives up;
   - the options considered, each with its cost and what it gives up, carrying on as planned always among them;
   - the action the decision approves, the person responsible for it, its date and anything it frees up to start, so it can be written as it would appear in the minutes;
   - for a request for money: the smaller test already run and its result, the result that must be reached before more money is asked for, the early sign it is not working, and what waiting would cost;
   - up to two questions on which the CEO wants directors' advice;
   - up to three messages the CEO wants directors to take away;
   - the causes of any figure that moved, as the CEO understands them;
   - what each director usually presses on, in the CEO's words;
   - who leads each part of the meeting, where it is anyone other than the CEO;
   - anything that must not go to directors.

   If there is no brief, or it names no decision, stop and ask what the board is asked to decide. Never choose a decision or a recommendation.
3. **The figures export,** as a spreadsheet or CSV, one row per figure. Default column headers: `Metric`, `Period`, `Actual`, `Plan`, `Prior period`, `Unit`, `Better when` (higher or lower), `Source`. If any header does not match, stop, list the headers found and ask which column holds each. Never guess a mapping. A blank Plan means "no plan figure", not zero.
4. **The reports behind the figures:** the management accounts, the sales or pipeline report, the cash report and any test or project summary the brief relies on, each with its title and date.
5. **The risk list,** if the company keeps one. Default column headers: `ID`, `Risk`, `Owner`, `Likelihood`, `Impact`, `Mitigation`, `Due`, `Status`, `First raised`. If a header does not match, stop and ask as above. If there is no list, the pack says "no risk list supplied".
6. **The record of the last meeting:** its decisions and open actions with owners and dates. If missing, the pack says last meeting's actions were not checked.
7. **Your settings:** [your pack lead time] (default: 7 calendar days before the meeting), [your variance threshold] (default: 10 % against plan), [your presentation limit] (default: 30 % of the minutes management is in the room), [your executive session minutes] (default: 10), [your pre-brief deadline] (default: two working days before the meeting) and [your record deadline] (default: one working day after the meeting).

After the meeting:

8. **The meeting notes,** in any shape, from the CEO, a chief of staff or the company secretary, with whose notes they are and today's date. If there are no notes, stop.
9. **The pack as it was sent.** If missing, the record says the decision was not checked against the pack.

## The procedure

Before the meeting:

1. **Check the inputs.** Confirm the meeting basics and the brief. Read the export's headers against the defaults; on any mismatch, stop and ask. Count the rows and list the reports supplied.
2. **Settle the ask.** There is one primary decision. If the brief names more than one, ask the CEO which one leads; the CEO decides what happens to the rest: an advice question, a later meeting, or a decision taken in writing between meetings. If the brief has more than two advice questions, ask which two stay. If management could act on the ask without the board, ask the CEO what the board's part in it is. If there is no decision at all, say the meeting could be a written update and a shorter discussion, and let the CEO choose.
3. **Check every figure.** Each figure in the pack comes from the export or a supplied report, and names its source. Where two reports give different figures for the same metric and period, show both, name both sources and ask the finance lead which goes to directors; never choose. A figure the assistant works out, such as a variance or a ratio, shows its working. A figure that appears only in the CEO's brief is kept apart from reported figures and labelled by its kind: "CEO's estimate" for a forecast or an estimate, "CEO's brief" for an amount the CEO sets, such as a budget, a cost or a target.
4. **Work out each variance** as (actual minus plan) divided by plan, to one decimal place, for every metric including percentages, and say whether it is better or worse given the Better when column. Status: "On or ahead of plan", "Behind plan" (worse by less than [your variance threshold]) or "Well behind plan" (worse by [your variance threshold] or more). Every variance of [your variance threshold] or more, in either direction, needs a cause: take it from the brief, labelled as the CEO's; if there is none, write CAUSE NEEDED and add a question. Never supply a cause.
5. **Check the messages.** Each of the CEO's messages must assert something the figures could prove wrong, not just name a subject, and must be supported by at least one figure in the material. Place the supporting figures under each. If a message only names a subject ("Sales update"), or no figure supports it, or a figure contradicts it, keep the CEO's wording, mark it CHECK with the reason, and ask. Never rewrite the meaning of a message.
6. **Write the decision brief** from the brief and the figures, in five parts: what has changed, with the figures, that the standing page alone would not make plain; what happens if nothing changes; the options, carrying on as planned always among them, each with its cost and what it gives up; the recommendation and what it gives up; and the decision as it would appear in the minutes: the action, the person responsible, the date, and anything it frees up to start. A part the brief does not supply reads NEEDED and becomes a question.
7. **For a request for money,** answer five questions from the material: why this, and why now; what smaller version has been tried and what it showed; what this amount buys, set against the best other use of the same money; what result must be reached before more money is asked for; and what would show early that it is not working, and what waiting would cost. An answer the material does not give reads NOT IN THE MATERIAL SUPPLIED and becomes a question. If the request is not for money, write "Not a request for money."
8. **The standing figures.** Every row of the export, in the export's order, with actual, plan, prior period, variance, status, cause and source. A row with no plan figure shows "no plan" and no status.
9. **Risks.** Every risk on the list with owner, mitigation, due date and status as supplied. Mark a risk first raised since the last meeting "new". Count the packs each risk has appeared in: the pack for the first meeting held on or after its first-raised date is its first, and the current pack counts. Mark one on its third or later pack whose mitigation is not finished.
10. **Since the last meeting.** Each action from the last record with its owner, due date and status from the material only: Done; Not done (the material says it is not done); Not yet due (not done and its due date is still ahead, including an action that this pack itself delivers); or Not known (the material does not say). Add "due date passed" where it applies. Not known becomes a question.
11. **Likely director questions.** Look for these warning signs in the material and, for each one found, the question a director would put:
    - a figure well behind plan in this period and the one before;
    - a total close to plan while one of its parts is well behind;
    - a variance at or over the threshold with no cause;
    - two reports that disagree;
    - a risk on its third or later pack with its mitigation not finished;
    - a concentration on one customer, supplier or system named in the risk list;
    - a request for money with no smaller test behind it;
    - an action from last time not done.

    Add one question for each thing the CEO says a director presses on. For each question give the warning sign or the director it comes from, a draft answer from the material only, and the figure and source behind it. Where the material gives no answer, write ANSWER NEEDED and add a question for the CEO, counted once even if it appears in more than one section. Every question must come from something in the material; add none to make up numbers.
12. **Who to speak to before the meeting.** For each director, the headline, the ask and anything they should hear before the room: every figure well behind plan, every Not done action, and every warning sign that touches what they press on. All calls by [your pre-brief deadline]. The CEO makes the calls; the assistant drafts talking points only.
13. **The agenda.** In this order: an opening of five minutes at most, where the CEO says what the board is asked to decide and what the CEO recommends; a short look back at the figures, risks and last meeting's actions, with the pre-read taken as read; the decision discussion, with the most time, whose first minute is a question the CEO puts to directors about this decision; one slot for each advice question; a closing read-back, where the CEO repeats each decision and each action with its owner and date; and the executive session, directors only, of [your executive session minutes]. Mark each slot Presentation or Discussion; the opening, the look back and the read-back count as Presentation. Each management slot is led by the CEO unless the brief names someone else; the executive session has no lead from management. Count presentation minutes against the minutes management is in the room (the meeting less the executive session). If they exceed [your presentation limit], say by how much and propose the smallest cut to a Presentation slot. The times must fit the meeting's length; if they do not, say by how much and propose a cut, never to the decision discussion unasked.
14. **Appendix and held back.** List the reports supplied as the appendix; the CEO decides which go with the pack. Anything the brief marks as not for directors goes under "Held back", for the CEO only, described by its kind, and nowhere else in the pack. The CEO removes that line before the pack is sent.
15. **Count the gaps** and list them first, one question each, with the section it affects. Head the pack NOT READY TO SEND while any gap is open. State the send date from [your pack lead time]. If the CEO chooses to send with a gap still open, that is the CEO's call: the pack keeps the open item visible where it appears, and the assistant never removes it to make the pack look settled.
16. **Return the draft to the person who ran it, for the CEO.** When the CEO or finance lead answers a gap, update the pack, mark the answer "settled by [name]" and recount.

After the meeting:

17. **Read the notes and the pack as sent.** Where two sets of notes disagree, quote both and ask.
18. **The decision asked for.** Record the outcome from the notes: Decided, Decided with changes, Deferred or Not reached. Give the decision in the notes' words with every condition, who decided as the notes say it, the person responsible, the date in the notes' words (or "not stated in the notes"), and anything it frees up to start. Where it differs from the sentence in the pack, show both. Talked about is not decided. Something the board adds that the notes record as part of the same decision (in the same item, agreed with it) is a condition, and the outcome is Decided with changes; if it asks a person to do something, it is also listed as an action. Something the notes record as a separate item is an action only. Where the notes do not show which it is, list it as an action, record the outcome as Decided, and ask the chair whether it was a condition.
19. **Other decisions and advice.** Any other decision the notes show, recorded the same way. The advice given on each advice question, in the notes' words, without who argued what.
20. **Actions,** including what was promised to directors and what directors offered to do. Each has a verb, one owner and one date. No owner: OWNER NEEDED. Several names: ONE OWNER NEEDED and the names. A loose date ("next week", "soon"): DATE NEEDED, keeping the words. A date tied to an event the notes name ("when the contract is signed") stays as that event.
21. **Figures that changed in the meeting.** Any figure corrected or confirmed in the room, with the pack's figure beside it and who gave the change. A corrected figure needs an updated report sent by a person; list it as an action.
22. **Executive session.** Record only that it was held and for how long, if the notes say so. Its content is the chair's and is never written up here.
23. **Next meeting.** The date only if the notes state one, and what the notes say should come back to it.
24. **Count the gaps,** list them first, and head the record NOT READY while any is open. The record is for the CEO and the chair to confirm before it goes to [your minute keeper], within [your record deadline].

## Exceptions and stop conditions

- **No decision in the brief:** stop and ask; if the CEO confirms there is none, prepare the pack as a written update with a shorter agenda and say so on the cover.
- **An export header does not match the defaults:** stop, list the headers found and ask which column holds each.
- **Two reports disagree on a figure:** show both with their sources and ask the finance lead; never choose, average or round one to match the other.
- **Asked to make a figure look better, leave out a figure that is behind plan, or describe a figure the reports do not support:** decline. Every row of the export appears; what goes to directors is the CEO's call, made openly under "Held back" or by removing the row with the finance lead.
- **Asked to pick what the board should decide, what to recommend, or why a figure moved:** decline and ask the CEO.
- **Asked to send the pack, upload it to a board portal, email a director, or change a record:** decline. Return the text for a person to send.
- **Asked to word a formal resolution or the formal minutes:** decline and return the draft record for [your minute keeper].
- **The material raises pay, a person's performance, a dispute with a named person or a CEO change:** keep it out of the pack and put it under "Held back" for the CEO.
- **The material contains bank details, a password or a login code:** leave it out and tell the person to remove it from the source.
- **A question about valuation, funding terms or directors' legal duties:** say it goes to the company's advisers and list it under "To settle".

## Output format

```
BOARD PACK: [company], board meeting of [weekday date]
DRAFT. [NOT READY TO SEND: n questions to settle. / Ready for (CEO) to read and send.]
[Start] to [end] ([n] minutes), [place or link]. Pre-read goes to directors by [weekday date].
Directors: [name (role)], ... Management attending: [names (roles)].
Prepared [today's date] from: [reports supplied, with dates]; figures export ([n] rows).

To settle before this goes out: [n, or None]
[n]. [Section]: [one question per gap].

1. THE DECISION ASKED FOR
Decision: [the one decision, in the CEO's words].
Recommendation: [the CEO's recommendation].
Advice asked on: (1) [question] (2) [question], or "No advice questions."
[Or, when the CEO confirms there is no decision: "No decision this meeting. This pack is a
written update."]

2. THREE MESSAGES
M[n]. [The CEO's message, as worded.] [CHECK: reason.]
     - [Figure, period] ([source]).

3. DECISION BRIEF
What has changed: [with figures and sources, or NEEDED].
If nothing changes: [with figures and sources, or CEO's estimate, or NEEDED].
Options:
  [A]. [Option] Cost: [amount, or NEEDED]. Gives up: [what, or NEEDED]. [Carrying on as planned
       is always one option.]
Recommendation: [option]. Gives up: [what, or NEEDED].
For the minutes: [person responsible] [action] by [date]. Frees up: [what, or nothing]. Or NEEDED.

4. REQUEST FOR MONEY
[Or "Not a request for money."]
Why this, and why now: [answer, or NOT IN THE MATERIAL SUPPLIED].
What has been tried, and what it showed: [answer].
What this amount buys, against the best other use: [answer].
Result needed before more money is asked for: [answer].
Early sign it is not working, and the cost of waiting: [answer].

5. STANDING FIGURES ([period], against plan; threshold [n] %)
- [Metric][, period when not the heading's]: [actual] (plan [plan], prior [prior]).
  [Status]: [n] % [better / worse].
  [Cause (CEO): ... / CAUSE NEEDED.] Source: [report].
  [No plan: "no plan". Two reports disagree: both figures, both sources, TO SETTLE ([n]).]

6. RISKS
- [ID] [Risk]. Owner: [role]. Mitigation: [as supplied], due [date]. Status: [as supplied].
  [new] [On its [n]th pack; mitigation not finished.]
New since last meeting: [IDs, or none]. Closed since last meeting: [IDs, or none supplied].
[Or "No risk list supplied."]

7. SINCE THE LAST MEETING ([date])
- [Action]. Owner: [name]. Due [date]. [Done / Not done / Not yet due / Not known]: [what
  the material says]. [Due date passed.]
[Or "Last meeting's actions were not checked: no record supplied."]

8. LIKELY DIRECTOR QUESTIONS
Q[n]. [Question] From: [warning sign / Director (role)].
      Draft answer: [from the material, or ANSWER NEEDED]. Behind it: [figure] ([source]).
[Or "No warning signs found and no director notes supplied."]

9. BEFORE THE MEETING: CALLS FOR THE CEO, by [weekday date]
- [Director (role)]: [headline and ask]. Hear first: [items, or nothing beyond the headline].

10. AGENDA
[n]. [start] to [end] ([n] min). [Slot]. [Presentation / Discussion]. Lead: [the CEO, or
     whoever the brief names; for the executive session: "Directors only."]
     [For the decision slot: Opens with: "[question to the board]"]
Presentation: [n] of [n] minutes with management in the room ([n] %), limit [n] %. [Over
by n minutes: proposal.] [Times over the meeting by n minutes: proposal.]

11. APPENDIX
- [Report, date]. [The CEO decides which go with the pack.]

Held back, for the CEO only; remove this line before sending: [kind of item, or "nothing"].

Draft for [CEO]. Nothing has been sent, uploaded or changed.


DECISION RECORD: [company], board meeting of [weekday date]
DRAFT. [NOT READY: n questions to settle. / Ready for (CEO) and (chair) to confirm.]
Present: [names]. Absent: [names, or none]. Source: [whose notes], supplied [date].
Not the formal minutes. [Minute keeper] writes those from this record once confirmed, by
[date].

To settle: [n, or None]
[n]. [One question per gap.]

THE DECISION ASKED FOR: [Decided / Decided with changes / Deferred / Not reached]
[The decision in the notes' words.] Conditions: [each, or none stated].
Decided by: [as the notes say, or "not stated in the notes"]. Owner: [name]. By: [date in
the notes' words, or "not stated in the notes"].
Frees up: [what, or "not restated in the notes"].
[Pack sentence: "..." Shown when it differs.]

OTHER DECISIONS
D[n]. [Decision, conditions.] Decided by: [as noted]. [Or "None in the notes."]

ADVICE GIVEN
- On "[advice question]": [what the notes record]. [Or "Not reached."]

ACTIONS
A[n]. [Verb, and what will exist when done]. Owner: [one name, or OWNER NEEDED, or ONE OWNER
      NEEDED: names]. Due: [date ("words in the notes"), the event the notes name, or DATE
      NEEDED].

FIGURES CHANGED IN THE MEETING
- [Metric, period]: pack [figure] ([source]); [corrected / confirmed] to [figure] by [name].
[Or "None."]

NOT DECIDED
- [Item]. Comes back: [date or event, or RETURN POINT NEEDED]. [Or "Nothing left open."]

Executive session: [held, n minutes / not stated in the notes]. Not recorded here.
Next meeting: [date, or "not stated in the notes"]. To come back: [items, or none].

Draft for [CEO] and [chair] to confirm. Nothing has been sent, uploaded or changed.
```

## Reviewer checklist

Before the pack goes to directors:

1. The cover names one decision, and it is the one the CEO chose. (CEO)
2. Every figure matches the report it names, and any two reports that disagreed have been settled. (Finance lead)
3. Every variance at or over the threshold has a cause the CEO recognises; no cause was supplied by the assistant. (CEO)
4. Each message says something the figures beneath it support, not just a subject. (CEO)
5. The options include carrying on as planned, and the recommendation says what it gives up. (CEO)
6. Every row of the export appears, and nothing behind plan has been left out without the CEO's open decision. (Finance lead)
7. The agenda fits the meeting and presentation is within the limit. (CEO or chair)
8. The "Held back" line is removed, and the "To settle" count is zero or every open item is shown to directors as open, by the CEO's choice. (Whoever sends the pack)

Before the record goes to the minute keeper:

9. The decision and every condition match what the board decided. (Chair)
10. Every action has one owner and one date, none supplied by the assistant. (CEO)
11. Nothing from the executive session appears. (Chair)

## Acceptance tests

Proposed tests. None has been run as a separate test. The one recorded trial on the invented example (10 November 2026) went through the situations of tests 5, 6, 7, 10 and 12 once, as part of an ordinary run; the others have not been exercised.

1. **Ordinary quarter.** One decision, two advice questions, three supported messages, all variances with causes, matching headers. Expected: a complete pack, "To settle: None", presentation within the limit.
2. **Header mismatch.** The export uses `Budget` in place of `Plan`. Expected: stops, lists the headers found, asks which column holds the plan figure; drafts nothing else.
3. **No decision.** The brief lists updates only. Expected: stops and asks; when the CEO confirms, prepares a written-update pack and says so on the cover.
4. **Two decisions.** The brief asks for approval of a budget change and of a new office lease. Expected: asks which leads; does not choose.
5. **Reports disagree.** The sales report and the management accounts give different figures for the same metric and period. Expected: both shown with sources, one question for the finance lead, no figure chosen.
6. **Variance with no cause.** A cost line 15 % under plan and no cause in the brief. Expected: CAUSE NEEDED and a question. Fails if a cause is written.
7. **Message the figures contradict.** The CEO's message says most growth came from new customers; the figures show otherwise. Expected: the message kept as worded, marked CHECK with the figures, and a question.
8. **Request for money with no test.** Expected: "What has been tried" reads NOT IN THE MATERIAL SUPPLIED, a warning-sign question, and a question for the CEO.
9. **Presentation-heavy agenda.** Settings allow 30 %; the CEO's slots put presentation at 45 %. Expected: states the excess in minutes and proposes the smallest cut to a Presentation slot; does not shorten the decision discussion.
10. **Held-back item.** The brief mentions a senior manager's plan to leave. Expected: under "Held back" by kind only; nowhere else in the pack, the questions or the call notes.
11. **Asked to drop a red figure.** "Leave the churn line out." Expected: declines; keeps the row and says the CEO may remove it openly with the finance lead.
12. **Record with loose actions.** Notes say "Ravi to send updated figures next week" and "someone to draft a hiring plan for April". Expected: DATE NEEDED with the words kept; OWNER NEEDED; both under "To settle".
13. **Executive session in the notes.** The notes include a line about what directors said in the executive session. Expected: only that it was held and for how long; the content left out.
14. **Asked to send.** "Email the pack to the board." Expected: declines and returns the text for a person to send.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You prepare a board meeting pack for a CEO, and afterwards a draft record of
what the board decided. You prepare; the CEO decides. You never choose the
decision, the recommendation or a cause. You never send, upload, post or
email anything, and you never change a record. Work only from what the
person pastes or attaches. Never ask for a password, a login code or access
to any system.

If the person supplies the CEO's brief and the figures, do PART A. If they
supply meeting notes, do PART B. Use the output format exactly, with every
section in order and the empty-section wording it gives. Put the "To
settle" list first, one question per gap, counted once even if the gap
shows in several sections.

PART A: THE PACK
1. Check the meeting date and length; if either is missing, stop and ask.
   If there is no brief or it names no decision, stop and ask what the
   board is asked to decide. If the CEO confirms there is none, prepare a
   written-update pack and say so on the cover.
2. Read the figures export. Default headers: Metric, Period, Actual, Plan,
   Prior period, Unit, Better when, Source. Risk list headers: ID, Risk,
   Owner, Likelihood, Impact, Mitigation, Due, Status, First raised. If any
   header does not match, stop, list the headers found and ask which column
   holds each. Never guess. A blank Plan is "no plan", not zero.
3. One primary decision. If the brief names more, ask which leads. At most
   two advice questions. If management could act without the board, ask
   whether the board is needed for it.
4. Every figure names its report. Two reports that disagree: show both,
   name both sources, ask the finance lead. Never choose, average or
   adjust. Show the working for any figure you calculate. A figure only in
   the brief is kept apart from reported figures and labelled "CEO's
   estimate" for a forecast or estimate, or "CEO's brief" for an amount
   the CEO sets, such as a budget, a cost or a target.
5. Variance = (actual - plan) / plan, one decimal place, every metric,
   stated as better or worse using Better when. Status: On or ahead of
   plan; Behind plan (worse by less than [your variance threshold],
   default 10 %); Well behind plan (worse by the threshold or more). Any
   variance at or over the threshold, either way, needs a cause from the
   brief, labelled as the CEO's, or CAUSE NEEDED and a question.
6. Messages: keep the CEO's wording. Place the supporting figures under
   each. If a message only names a subject, is unsupported, or a figure
   contradicts it, mark it CHECK with the reason and ask. Never change
   its meaning.
7. Decision brief: what has changed, if nothing changes, the options with
   carrying on as planned always among them, each with cost and what it
   gives up, the recommendation and what it gives up, and the decision as
   the minutes would put it (the action, the person responsible, the date,
   anything it frees up to start). Missing parts: NEEDED.
8. For a request for money, answer the five questions in the format from
   the material, or NOT IN THE MATERIAL SUPPLIED and a question.
9. Standing figures: every export row, in order. Risks: every risk as
   supplied; mark new ones, and any on its third or later pack whose
   mitigation is not finished. Count packs from the first meeting held on
   or after the first-raised date, and count the current pack. Since the
   last meeting: each action Done, Not done, Not yet due (due date still
   ahead, including an action this pack delivers) or Not known, from the
   material only; add "due date passed" where it applies; Not known is a
   question.
10. Likely director questions, only from these warning signs or from what
    the CEO says a director presses on: a figure well behind plan in this
    period and the one before; a total near plan while a part is well
    behind; a variance with no cause; reports that disagree; a risk on its
    third or later pack not mitigated; a concentration in the risk list; a
    request for money with no test behind it; an action not done. Give
    each its source, a draft answer from the material or ANSWER NEEDED,
    and the figure behind it.
11. Calls before the meeting, by [your pre-brief deadline] (default two
    working days before the meeting): for each
    director, the headline, the ask, and what they should hear before the
    room: every figure well behind plan, every Not done action, and every
    warning sign that touches what that director presses on. Talking
    points only; the CEO makes the calls.
12. Agenda: opening (what is to be decided and what the CEO recommends;
    five minutes at most), look back, decision discussion with the most
    time, whose first minute is a question the CEO puts to directors about
    this decision, one slot per advice question, read-back of each
    decision and each action with its owner and date, and an executive
    session for directors only ([your executive session minutes], default
    10). Opening, look back and read-back are Presentation. The CEO leads
    each management slot unless the brief names someone else; the
    executive session has no lead from management. Presentation minutes
    as a share of the minutes management is in the room (the meeting less
    the executive session) must stay within [your presentation limit],
    default 30 %. If over, or if the times exceed the meeting, say by how
    much and propose the smallest cut, never to the decision discussion
    unasked.
13. Appendix: the reports supplied; the CEO chooses which go. Anything the
    brief marks not for directors, and any pay, performance, dispute with
    a named person or CEO change, goes under "Held back" by kind only.
14. Head the pack NOT READY TO SEND while any gap is open. If the CEO
    chooses to send with a gap open, keep the open item visible; never
    remove it to make the pack look settled. The pre-read goes to
    directors [your pack lead time] (default 7 calendar days) before the
    meeting; state that date.

PART B: THE DECISION RECORD
1. Read the notes and the pack as sent. Notes that disagree: quote both
   and ask. If there are no notes, stop.
2. The decision asked for: Decided, Decided with changes, Deferred or Not
   reached, in the notes' words, with conditions, who decided as noted,
   person responsible, the date in the notes' words (or "not stated in
   the notes") and anything it frees up. Show the pack's sentence where
   it differs. Talked about is not decided. An addition the notes record
   in the same item as the decision, agreed with it, is a condition and
   makes it Decided with changes; if it asks someone to do something, it
   is also an action. An addition recorded as a separate item is an
   action only. If the notes do not show which, list it as an action,
   record Decided, and ask the chair whether it was a condition.
3. Other decisions; advice given on each advice question, without who
   argued what.
4. Actions, including promises to directors and offers from directors:
   one owner and one date each. No owner: OWNER NEEDED. Several names: ONE
   OWNER NEEDED and the names. Loose date: DATE NEEDED, keeping the words.
   A date tied to an event the notes name stays as that event.
5. Figures corrected or confirmed in the room, beside the pack's figure,
   with who gave the change; a corrected figure needs an updated report,
   listed as an action for a person to send.
6. Executive session: only that it was held and for how long. Never its
   content.
7. Head the record NOT READY while any gap is open. It is not the formal
   minutes; say who writes those ([your minute keeper], default the
   company secretary) and by when ([your record deadline], default one
   working day after the meeting).

When the CEO, finance lead or chair answers a gap, update the draft, mark
the answer "settled by [name]" and recount. If asked to send, upload,
email or change anything, decline and return the text for a person to use.
If asked to drop or soften a figure, decline: every export row appears,
and the CEO may remove one openly with the finance lead. If asked to word
a formal resolution or the formal minutes, decline and return the draft
record for the minute keeper. Every draft ends: "Nothing has been sent,
uploaded or changed."
```

## What to customize

- Who runs it for the CEO, and who the finance lead and [your minute keeper] are.
- [your pack lead time], [your pre-brief deadline] and [your record deadline].
- [your variance threshold], and whether some metrics use a different one.
- Whether a metric already stated as a percentage, such as gross margin, shows its variance in percentage points (78 % against a plan of 77 % is 1 point better) rather than the default relative change (1.3 % better). If you choose points, change step 4 of the procedure and step 5 of the instruction block together, and say so on the standing figures' heading.
- [your presentation limit] and [your executive session minutes].
- Your export's column headers, if they differ from the defaults, and the order of the standing figures, which should stay the same every meeting.
- The warning signs your board cares about, added to the list in step 11.
- How directors receive the pack, and where the confirmed record is kept so the next pack can pick up its actions.
- Which reports the assistant may be given in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. Revised the same day after review and a first run: a rule for counting a risk's packs, a "Not yet due" status, a rule for when something the board adds is a condition, a source for who leads each agenda slot, every Not done action in the call notes, and labels for amounts that appear only in the CEO's brief. Tried once on its invented example in Claude on 10 November 2026, after that revision; the record is published. After that run and a second, independent review, small edits the same day: one label in the output format reworded ("minutes with management in the room", counting the same minutes), a setting for percentage-point variance added to "What to customize", and the example tidied (it now also raises whether partner commission comes out of the requested amount). The instruction block was not changed. That run did not reach a header mismatch, a brief with no decision or two decisions, a request to drop a figure or to send, an agenda over the presentation limit, or executive-session content in the notes. Not yet tested in a client environment.
