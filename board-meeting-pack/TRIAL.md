# Board meeting pack: one trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-10

The inputs for this trial are the invented example in [example.md](example.md), Company V. No client data was used.

How this run was made, plainly. An earlier run on the same day, by Claude Sonnet 5.5, a model that had not written the template, found gaps in the template: no rule for counting a risk's packs in the pasted instructions, no status for an action the pack itself delivers, no rule for whether something the board adds is a condition or an action, and no source for who leads each agenda slot. The template and the example were then revised to close those gaps, and the example's brief was reworded in two places (the first advice question and the cost of waiting). That earlier record no longer matched the template or the example, so it was replaced by this one. This run was made by the model that made the revision, with the template's instruction block and output format as they now stand, on the example's revised inputs. It is not a blind run: the example's own outputs and the earlier record had been read before it. Its agreement with the published example is therefore weaker evidence than an independent run would give.

Inputs used: the example's sections 1 to 6 (meeting and settings, Mara's brief, figures export, reports, risk list, record of the last meeting) for the pack. For the decision record: Teo's notes, and as "the pack as sent", this run's own draft pack with the answers the example's narrative gives applied (the cancellation cause, the two reworded messages, the other $150,000 unspent until April), question 1 left open with both figures shown, and the "To settle" list and "Held back" line removed. This run's question 6 is not answered in the example's narrative, so it stayed open in the pack as sent.

Edits made after this run, on the same day, following a second, independent review. The template's instruction block was not changed. One label in the output format was reworded, from "management minutes" to "minutes with management in the room", counting the same minutes; the output below keeps the label this run produced. The published example was edited in small ways: it now raises the same commission question as this run's question 6, and its narrative answers it; its call notes no longer give Director A the sentence proposed for the minutes; and a few labels and phrases were tidied. The input sections the run used (the meeting, the brief, the export, the reports, the risk list and the last record) were not changed. Where this record compares itself with the published example, below and in the paragraph above, it describes the example as it stood when the run was made.

## What came out

Both parts were produced in full: all eleven sections of the pack and the whole decision record. No stop condition was triggered: the export and risk-list headers matched, the brief names one decision, and notes were supplied.

### The pack

```
BOARD PACK: Company V, board meeting of Thursday 22 October 2026
DRAFT. NOT READY TO SEND: 6 questions to settle.
10:00 to 11:30 (90 minutes), at our office and on video. Pre-read goes to directors by
Thursday 15 October 2026.
Directors: Director A (chair, investor director), Director B (investor director),
Director C (investor director), Director D (independent). Management attending: Mara (CEO),
Ravi (finance lead).
Prepared Monday 12 October 2026 from: Management accounts Q3 2026; Sales report Q2 2026;
Sales report Q3 2026; Cash report 30 September 2026; Partner test summary 5 September 2026;
risk list (undated); record of the meeting of 23 July 2026; figures export (10 rows).

To settle before this goes out: 6
1. Standing figures (Ravi): new-customer ARR added in Q3 2026 is $0.21m in the Sales report
   Q3 2026 and $0.19m in the Management accounts Q3 2026 (prior period $0.22m and $0.20m).
   Which goes to directors, and when will the July action to reconcile the two definitions,
   due 30 September, be finished?
2. Standing figures (Mara): ARR lost to cancellations was 12.5 % better than plan. The brief
   gives no cause. What was it?
3. Messages, M1 (Mara): in Q3, new-customer ARR added ($0.21m or $0.19m) was larger than
   expansion ARR added ($0.17m), so the figures do not show growth coming "mostly from
   existing customers". Keep the wording, reword it, or supply the figure that supports it?
4. Messages, M2; request for money; Q9 (Mara): "cheaply" and "against the best other use"
   need the cost of new ARR through direct sales, or what the two salespeople would be
   expected to bring in. Neither is in the material. Supply it, or say it is not available.
5. Likely director questions, Q10 (Mara): $90,000 of the $240,000 hiring budget moves to the
   first stage. What happens to the other $150,000 while the hires are paused?
6. Request for money (Mara): is the partners' 20 % commission on first-year ARR paid from
   the $90,000, or on top of it?

1. THE DECISION ASKED FOR
Decision: Approve $90,000 for a first stage of a partner channel with gym-equipment
distributors, October 2026 to March 2027, taken from the $240,000 budgeted for two
new-business salespeople in the first half of 2027. The two sales hires pause until the
April 2027 meeting.
Recommendation: Approve.
Advice asked on: (1) What should our agreements with distributors settle before the first
gym is signed? (2) Should the April meeting see a sales hiring plan whatever the partner
results?

2. THREE MESSAGES
M1. Growth now comes mostly from existing customers; new-customer sales are behind for a
    second quarter. CHECK: the second half is supported; the first is not. Q3 new-customer
    ARR added exceeds expansion ARR added (To settle 3).
     - New-customer ARR added, Q2 2026: $0.22m, plan $0.30m (Sales report Q2 2026).
     - New-customer ARR added, Q3 2026: $0.21m, plan $0.32m (Sales report Q3 2026); $0.19m
       (Management accounts Q3 2026). To settle 1.
     - Expansion ARR added, Q3 2026: $0.17m, plan $0.10m (Sales report Q3 2026).
M2. Distributors brought gyms in cheaply in a small test. CHECK: no direct-sales cost to
    compare with, so "cheaply" is not shown (To settle 4).
     - Distributor A, 1 May to 31 August 2026: 12 gyms signed, $54,000 of new ARR, cost
       $22,000 (Partner test summary, 5 September 2026).
M3. We have the cash to stage this and decide again in April.
     - Cash at end of Q3 2026: $3.90m, plan $3.70m (Cash report 30 September 2026).
     - Months of cash at current net burn, Q3 2026: 26, plan 24 (Cash report 30 September
       2026).
     - First stage: $90,000, taken from the $240,000 hiring budget (CEO's brief).

3. DECISION BRIEF
What has changed: new-customer ARR added has been well behind plan two quarters running:
$0.22m against $0.30m in Q2, 26.7 % worse (Sales report Q2 2026); $0.21m against $0.32m in
Q3, 34.4 % worse (Sales report Q3 2026; $0.19m in the Management accounts, To settle 1).
Total ARR is $4.62m against $4.65m, 0.6 % worse (Management accounts Q3 2026), held up by
expansion ARR of $0.17m against $0.10m (Sales report Q3 2026). Cause (CEO): fewer direct
deals won since a competitor began including booking software with equipment leases.
If nothing changes: CEO's estimate: at Q3's pace, new-customer ARR for 2027 ends about
$0.45m below plan.
Options:
  A. Stay the course: hire the two salespeople in Q1 2027. Cost: $240,000 for the first half
     of 2027 (CEO's brief). Gives up: nothing new, but they will not be fully selling until
     late 2027.
  B. Partner channel first stage (recommended). Cost: $90,000 (CEO's brief; commission, To
     settle 6). Gives up: two salespeople's selling time in the first half of 2027; partners
     take 20 % of first-year ARR as commission.
  C. Cut new-business spend and put the effort into existing customers. Cost: saves
     $240,000 (CEO's brief). Gives up: new-customer growth.
Recommendation: B. Gives up: two salespeople's selling time in the first half of 2027, and
20 % of first-year partner ARR as commission.
For the minutes: Mara runs a first stage of the partner channel with gym-equipment
distributors, October 2026 to March 2027, with $90,000 taken from the first-half 2027
hiring budget and the two sales hires paused, judged at the April 2027 meeting against 30
gyms signed and $120,000 of new ARR from partners (CEO's brief). Frees up: signing with
Distributor A and one more distributor.

4. REQUEST FOR MONEY
Why this, and why now: new-customer ARR well behind plan in Q2 and Q3 (section 3), cause as
the CEO gives it. Deciding in January instead misses the distributors' spring trade-show
season (CEO's brief).
What has been tried, and what it showed: Distributor A, 1 May to 31 August 2026: 41 gyms
referred, 12 signed (29.3 %, 12 / 41), $54,000 of new ARR for $22,000 ($10,800 commission,
$11,200 joint marketing), or $2.45 of new ARR per $1 spent (54,000 / 22,000) (Partner test
summary, 5 September 2026). One distributor only.
What this amount buys, against the best other use: $90,000 lets the company sign with
Distributor A and one more distributor (CEO's brief). The best other use named is two
salespeople for $240,000 over the same half year; what they would bring in, and the cost of
new ARR through direct sales: NOT IN THE MATERIAL SUPPLIED (To settle 4).
Result needed before more money is asked for: 30 gyms signed and $120,000 of new ARR from
partners, judged at the April 2027 meeting (CEO's brief).
Early sign it is not working, and the cost of waiting: fewer than 10 gyms signed through
partners by 31 December 2026: stop and report at the January meeting. Waiting until January
misses the spring trade-show season (CEO's brief).

5. STANDING FIGURES (Q3 2026, against plan; threshold 10 %)
- Annual recurring revenue: $4.62m (plan $4.65m, prior $4.31m).
  Behind plan: 0.6 % worse ((4.62 - 4.65) / 4.65). Source: Management accounts Q3 2026.
- New-customer ARR added, Q2 2026: $0.22m (plan $0.30m, prior $0.25m).
  Well behind plan: 26.7 % worse ((0.22 - 0.30) / 0.30). Cause (CEO): fewer direct deals
  won since a competitor began including booking software with equipment leases. Source:
  Sales report Q2 2026.
- New-customer ARR added: $0.21m (plan $0.32m, prior $0.22m).
  Well behind plan: 34.4 % worse ((0.21 - 0.32) / 0.32). Cause (CEO): as above. Source:
  Sales report Q3 2026. Two reports disagree: $0.19m in the Management accounts Q3 2026.
  TO SETTLE (1).
- New-customer ARR added: $0.19m (plan $0.32m, prior $0.20m).
  Well behind plan: 40.6 % worse ((0.19 - 0.32) / 0.32). Cause (CEO): as above. Source:
  Management accounts Q3 2026. Two reports disagree: $0.21m in the Sales report Q3 2026.
  TO SETTLE (1).
- Expansion ARR added: $0.17m (plan $0.10m, prior $0.12m).
  On or ahead of plan: 70.0 % better ((0.17 - 0.10) / 0.10). Cause (CEO): the
  class-booking add-on launched in June. Source: Sales report Q3 2026.
- ARR lost to cancellations: $0.07m (plan $0.08m, prior $0.09m).
  On or ahead of plan: 12.5 % better ((0.07 - 0.08) / 0.08; lower is better). CAUSE NEEDED
  (To settle 2). Source: Management accounts Q3 2026.
- Gross margin: 78 % (plan 77 %, prior 77 %).
  On or ahead of plan: 1.3 % better ((78 - 77) / 77). Source: Management accounts Q3 2026.
- Operating expense: $1.46m (plan $1.50m, prior $1.41m).
  On or ahead of plan: 2.7 % better ((1.46 - 1.50) / 1.50; lower is better). Source:
  Management accounts Q3 2026.
- Cash at end of quarter: $3.90m (plan $3.70m, prior $4.35m).
  On or ahead of plan: 5.4 % better ((3.90 - 3.70) / 3.70). Source: Cash report
  30 September 2026.
- Months of cash at current net burn: 26 (plan 24, prior 23).
  On or ahead of plan: 8.3 % better ((26 - 24) / 24). Source: Cash report 30 September
  2026.

6. RISKS
- R1 New-customer sales below plan. Owner: CEO. Mitigation: partner channel test; decision
  at October board, due 22 October 2026. Status: decision in October pack.
  On its 3rd pack (23 April, 23 July, 22 October); mitigation not finished.
- R2 All member payments run through one payment processor. Owner: CTO. Mitigation: sign a
  second processor, due 15 December 2026. Status: contract with the second processor under
  review. On its 4th pack (22 January, 23 April, 23 July, 22 October); mitigation not
  finished.
- R3 Two largest customers (gym chains) are 14 % of ARR. Owner: Head of customer success.
  Mitigation: renewal talks with both, due 28 February 2027. Status: talks started with
  one. On its 4th pack (22 January, 23 April, 23 July, 22 October); mitigation not
  finished.
New since last meeting: none. Closed since last meeting: none supplied.

7. SINCE THE LAST MEETING (23 July 2026)
- Bring a recommendation on new-customer sales to the October meeting. Owner: Mara. Due
  22 October 2026. Not yet due: this pack delivers it (CEO's brief).
- Reconcile the sales report and management accounts definitions of new-customer ARR.
  Owner: Ravi. Due 30 September 2026. Not done: "not done yet" (CEO's brief). Due date
  passed.
- Introduce Mara to two distributor contacts. Owner: Director B. Due 31 August 2026. Done:
  both introductions made in August (CEO's brief).

8. LIKELY DIRECTOR QUESTIONS
Q1. Why has new-customer ARR fallen short of plan in both Q2 and Q3, and what happens if it
    goes on? From: a figure well behind plan in this period and the one before.
    Draft answer: the CEO's cause is fewer direct deals won since a competitor began
    including booking software with equipment leases. CEO's estimate: at Q3's pace,
    new-customer ARR for 2027 ends about $0.45m below plan. Behind it: $0.22m against
    $0.30m (Sales report Q2 2026); $0.21m against $0.32m (Sales report Q3 2026).
Q2. What is holding total ARR close to plan while new-customer ARR is well behind? From: a
    total near plan while a part is well behind.
    Draft answer: expansion ran $0.07m over plan and cancellations $0.01m under, against
    new-customer ARR $0.11m short: -0.11 + 0.07 + 0.01 = -0.03, which is 4.62 - 4.65.
    Behind it: Sales report Q3 2026; Management accounts Q3 2026 (ARR, cancellations).
Q3. Which new-customer figure is right, and when will the two reports agree? From: reports
    that disagree; an action not done (July action 2).
    Draft answer: ANSWER NEEDED (To settle 1). Behind it: $0.21m (Sales report Q3 2026);
    $0.19m (Management accounts Q3 2026).
Q4. Why were cancellations 12.5 % below plan? From: a variance with no cause.
    Draft answer: ANSWER NEEDED (To settle 2). Behind it: $0.07m against $0.08m
    (Management accounts Q3 2026).
Q5. R1 is on its third pack. What is different this time? From: a risk on its third or
    later pack not mitigated (R1).
    Draft answer: this pack asks the board to decide the partner channel, which is R1's
    mitigation. Behind it: risk list, R1.
Q6. Will the second payment processor be signed by 15 December? From: a risk on its fourth
    pack not mitigated; a concentration on one system (R2).
    Draft answer: the contract with the second processor is under review, due 15 December
    2026. Behind it: risk list, R2.
Q7. How far have renewal talks with the two largest customers got? From: a concentration
    in the risk list; a risk on its fourth pack not mitigated (R3).
    Draft answer: together they are 14 % of ARR; talks have started with one of the two,
    due to finish by 28 February 2027. Behind it: risk list, R3.
Q8. What exactly will the minutes record if we approve? From: Director A (chair).
    Draft answer: the sentence under "For the minutes" in section 3. Behind it: CEO's
    brief.
Q9. What does a dollar of partner spend bring back, against a dollar of direct sales?
    From: Director B (investor director).
    Draft answer: in the test, $2.45 of new ARR for each $1 (54,000 / 22,000). Direct
    sales: ANSWER NEEDED (To settle 4). Behind it: Partner test summary, 5 September 2026.
Q10. Does this change how long the cash lasts? From: Director C (investor director).
    Draft answer: 26 months at current net burn. The $90,000 is taken from the $240,000
    hiring budget, not added to it (CEO's brief). What happens to the other $150,000:
    ANSWER NEEDED (To settle 5); whether commission is on top: To settle 6. Behind it: Cash
    report 30 September 2026; CEO's brief.
Q11. Who will run the partner channel day to day? From: Director D (independent).
    Draft answer: the head of partnerships, with no new hire; Mara owns it. Behind it:
    CEO's brief.

9. BEFORE THE MEETING: CALLS FOR THE CEO, by Tuesday 20 October 2026
- Director A (chair, investor director): new-customer ARR well behind plan for a second
  quarter; the ask is $90,000 for a first partner stage with the two hires paused. Hear
  first: new-customer ARR well behind plan in Q2 and Q3 (Q3 figure being settled); the July
  reconciliation is not done.
- Director B (investor director): the same headline and ask. Hear first: new-customer ARR
  well behind plan in Q2 and Q3; the July reconciliation is not done; the test's $2.45 of
  new ARR per $1, with the direct-sales comparison still open.
- Director C (investor director): the same headline and ask. Hear first: new-customer ARR
  well behind plan in Q2 and Q3; the July reconciliation is not done; 26 months of cash,
  with the $90,000 taken from the hiring budget.
- Director D (independent): the same headline and ask. Hear first: new-customer ARR well
  behind plan in Q2 and Q3; the July reconciliation is not done; the head of partnerships
  runs it, with no new hire.

10. AGENDA
1. 10:00 to 10:04 (4 min). Opening: what the board is asked to decide, and Mara's
   recommendation. Presentation. Lead: Mara.
2. 10:04 to 10:14 (10 min). Look back: figures, risks and July's actions, pre-read taken
   as read. Presentation. Lead: Mara.
3. 10:14 to 10:59 (45 min). Decision: the partner channel first stage. Discussion.
   Lead: Mara.
   Opens with: "What would you need to see in January to keep this stage going?"
4. 10:59 to 11:09 (10 min). Advice: what the distributor agreements must settle.
   Discussion. Lead: Mara.
5. 11:09 to 11:17 (8 min). Advice: a sales hiring plan for April. Discussion. Lead: Mara.
6. 11:17 to 11:20 (3 min). Read-back: each decision, and each action with its owner and
   date. Presentation. Lead: Mara.
7. 11:20 to 11:30 (10 min). Executive session. Discussion. Directors only.
Presentation: 17 of 80 management minutes (21 %), limit 30 %.

11. APPENDIX
- Management accounts Q3 2026.
- Sales report Q2 2026.
- Sales report Q3 2026.
- Cash report, 30 September 2026.
- Partner test summary, 5 September 2026.
The CEO decides which go with the pack.

Held back, for the CEO only; remove this line before sending: one personnel matter.

Draft for Mara. Nothing has been sent, uploaded or changed.
```

### The decision record

```
DECISION RECORD: Company V, board meeting of Thursday 22 October 2026
DRAFT. NOT READY: 3 questions to settle.
Present: Director A, Director B, Director C, Director D, Mara, Ravi. Absent: none.
Source: Teo's notes, supplied Thursday 22 October 2026.
Not the formal minutes. The company secretary writes those from this record once
confirmed, by Friday 23 October 2026.

To settle: 3
1. A1: the notes say "next week". On what date will Ravi send the corrected management
   accounts?
2. A3: no date in the notes. By when will Director D make the introduction?
3. A4: no one is named. Who brings the sales hiring plan to the April meeting?

THE DECISION ASKED FOR: Decided with changes
Approved: $90,000, October 2026 to March 2027, from the first-half sales hiring budget,
hires paused to April. Conditions: Mara reports gyms signed and partner ARR at the January
meeting (added by Director A); that report includes the cost per $1 of new ARR, partner
against direct (added by Director B). Both agreed in the same item. The head of
partnerships runs it day to day.
Decided by: not stated in the notes ("APPROVED"). Owner: Mara. By: end of March 2027
("Oct-Mar").
Frees up: not restated in the notes.
Pack sentence: "Mara runs a first stage of the partner channel with gym-equipment
distributors, October 2026 to March 2027, with $90,000 taken from the first-half 2027
hiring budget and the two sales hires paused, judged at the April 2027 meeting against 30
gyms signed and $120,000 of new ARR from partners. Frees up: signing with Distributor A
and one more distributor." Shown because the board added the January report and the notes
do not restate the April test.

OTHER DECISIONS
None in the notes.

ADVICE GIVEN
- On "What should our agreements with distributors settle before the first gym is
  signed?": a distributor channel in another portfolio company had partners and direct
  sales fighting over who owned a customer. Set the rule on who owns a gym before signing.
- On "Should the April meeting see a sales hiring plan whatever the partner results?": the
  board wants a sales hiring plan at the April meeting whatever the partner numbers (A4).

ACTIONS
A1. Send corrected management accounts for Q3 2026. Owner: Ravi. Due: DATE NEEDED ("next
    week").
A2. Report gyms signed and partner ARR, with the cost per $1 of new ARR through partners
    and through direct sales, at the January meeting. Owner: Mara. Due: the January meeting
    (Thursday 21 January 2027).
A3. Introduce Mara to a distributor in the north-west. Owner: Director D. Due: DATE NEEDED.
A4. Bring a sales hiring plan to the April meeting. Owner: OWNER NEEDED. Due: the April
    2027 meeting.
A5. Confirm the second payment processor is signed. Owner: CTO. Due: 15 December 2026.
A6. Tell the board when the second payment processor is signed. Owner: Mara. Due: when it
    is signed.

FIGURES CHANGED IN THE MEETING
- New-customer ARR added, Q3 2026: pack $0.21m (Sales report Q3 2026) and $0.19m
  (Management accounts Q3 2026), left open; confirmed at $0.21m by Ravi. The management
  accounts used the old definition; corrected accounts are A1.

NOT DECIDED
- Nothing left open.

Executive session: held, 10 minutes. Not recorded here.
Next meeting: Thursday 21 January 2027. To come back: the partner channel report (A2).

Draft for Mara and Director A to confirm. Nothing has been sent, uploaded or changed.
```

## What was observed

Everything the format asks for was produced. Every export row appears in order; the variances reproduce to one decimal place; the two disagreeing reports are both shown and neither is chosen; the cancellation variance has CAUSE NEEDED rather than an invented cause; M1 and M2 keep the CEO's words and are marked CHECK; the held-back item appears once, by kind only, and nowhere in the questions or calls; the executive session is recorded only as held and for how long; and nothing was sent.

The rules added in the revision decided the cases the earlier run had found open. The pack count gave R1 its 3rd pack and R2 and R3 their 4th. July action 1 came out Not yet due. The board's additions in the same agreed item came out as conditions, with the outcome Decided with changes, and the January report also as an action. Every management slot is led by Mara, because the brief names no one else, and the executive session has no lead from management.

### Differences from the published example

- **Questions to settle.** Six against the example's five. The extra one asks whether the partners' 20 % commission is paid from the $90,000 or on top of it. The brief does not say, and the test's cost included commission. The example does not raise it.
- **Director questions.** Eleven against ten. This run gives R1 its own question; the example folds R1 into its first question. The first question is worded differently in each and draws on the same cause.
- **Agenda.** 4, 10 and 3 minutes of presentation (21 %) against the example's 3, 10 and 2 (19 %); the second advice slot is 8 minutes, not 10. The opening question differs. Both are within the limit and fit the meeting.
- **Calls.** This run gives Director A only the figures well behind plan and the action not done, because no warning sign touches what A presses on. The example also gives A the sentence proposed for the minutes.
- **The decision record.** The same outcome, conditions, six actions and three questions as the example. This run says the pack sentence is shown also because the notes do not restate the April test.

### Facts not in the inputs

- In this run: the year 2026 on the notes' "15 Dec" (taken from R2 in the pack), and "end of March 2027" for "Oct-Mar", with the notes' words kept beside it. Calculated figures show their working.
- In the example: the closing narrative after each output (the answers Mara and Ravi gave, the confirmations) is invented, as the example says. It is not output of the template.

### Shortcomings in the template that remain

1. **"Could management act without the board?"** The material rarely says what management may do alone, so the check depends on knowledge the inputs do not carry. This run did not ask.
2. **Variance on percentages.** Relative change for every metric gives gross margin 78 against 77 as 1.3 % better, where a reader may expect one point.
3. **Counting gaps by hand.** One gap appears in several sections, and renumbering changes every cross-reference. This run got it right, but the step is easy to get wrong.
4. **Advice that reads like an action.** "Set the rule on who owns a gym before signing" is advice in the notes with no owner. The template records advice in the notes' words and makes nothing an action that the notes do not assign, so it stays advice; a chair may want it tracked.
5. **Not reached by this run:** a header mismatch, a brief with no decision or two decisions, a request to drop a figure or to send the pack, an agenda over the presentation limit, and executive-session content in the notes.
