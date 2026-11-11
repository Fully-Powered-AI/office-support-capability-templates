# Executive week-ahead calendar review: tried once on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (`claude-sonnet-5-5`)
- **Date:** 2026-11-10

The inputs are the invented example in [example.md](example.md) (Company A, Morgan and Sam). No client data was used. The run was a single attempt by a model that did not write the template. It followed the instruction block and the output format in `member/template.md`, working from the example's inputs only, and read the example's output after producing its own.

## Inputs used

The five inputs under "The inputs" in [example.md](example.md): the settings (week of 16 to 20 November 2026, working hours 08:30 to 18:00, base Office, a Wednesday school run protected from 08:30 to 09:30, everything else the defaults), the calendar export of 12 November 2026 at 16:00 (23 rows), Morgan's two priorities, the two-line preparation list and the three travel times.

## What came out

```
WEEK-AHEAD CALENDAR REVIEW: Morgan (managing director), week of Monday 16 November 2026

For: Sam and Morgan. Prepared Thursday 12 November 2026 from the calendar export of 12 November 2026, 16:00 (23 events; 1 declined, left out), 2 priorities, the preparation list (2 lines), 3 travel times.
Settings: times in local time; working days Monday to Friday, 08:30 to 18:00; base Office; protected Wednesday 08:30 to 09:30 (school run); break 10 min; longest run 3 h; reservations 60 to 120 min; morning 08:30 to 12:00, afternoon 12:00 to 18:00.

Week at a glance
Monday 16 November: 6 meetings, 5 h of meetings; 4 h 30 min free in working hours.
Tuesday 17 November: 5 meetings, 4 h 15 min of meetings; 5 h 15 min free in working hours.
Wednesday 18 November: 3 meetings, 2 h 45 min of meetings; 5 h 15 min free in working hours.
Thursday 19 November: 3 meetings, 5 h of meetings; 5 h 30 min free in working hours.
Friday 20 November: 3 meetings, 2 h 30 min of meetings; 7 h free in working hours.

Conflicts: 3
C1. Monday 16 November. Supplier A service review (15:00 to 16:00, Video, from Supplier A account manager, Tentative) overlaps Finance weekly (15:30 to 16:30, Office, from Jordan, Accepted). Decision 2.
C2. Wednesday 18 November. Residents' committee (09:00 to 10:00, Property 14, from Kit, Accepted) overlaps protected time, 08:30 to 09:30 (school run). Decision 4.
C3. Thursday 19 November. Industry dinner (18:00 to 20:00, Hotel A, from Association A, Accepted) is outside working hours, which end at 18:00. Decision 7.

Travel and breaks: 3
T1. Monday 16 November, 09:00 to 12:30. 4 meetings with no break of 10 min: 3 h 30 min, over the 3 h limit by 30 min. Decision 1.
T2. Tuesday 17 November. Client B quarterly review ends 11:00 at Client B offices; Leasing team stand-up starts 11:15 at Office. Gap 15 min; travel 30 min: short by 15 min. Decision 3.
T3. Wednesday 18 November. Residents' committee ends 10:00 at Property 14; Client B renewal workshop starts 10:30 at Client B offices. Travel time not supplied. Decision 5.

Purpose not stated: 2
M1. Tuesday 17 November 15:30 to 16:30, Catch-up, from Lee. No purpose in the invitation. Question 1 for the organiser.
M2. Wednesday 18 November 14:00 to 14:45, Owner call: Building C, from Morgan. No purpose in the invitation. Decision 6.

Preparation: 2
P1. Tuesday 17 November 10:00, Client B quarterly review. Needs: read the service figures sent to Client B last week (30 min). Set aside: none. Short by 30 min: proposed R2.
P2. Thursday 19 November 14:00, Board meeting. Needs: read the board pack, due from Jordan on Tuesday (90 min). Set aside: Prep: Board meeting, Thursday 12:30 to 13:30 (60 min). Short by 30 min: proposed R4.

Invitations not yet answered: 3
I1. Monday 16 November 15:00 to 16:00, Supplier A service review, from Supplier A account manager: Tentative. See C1.
I2. Wednesday 18 November 10:30 to 11:30, Client B renewal workshop, from Client B facilities director: Not answered. See T3.
I3. Friday 20 November 10:00 to 11:00, Vendor demo: tenant portal, from Supplier D: Not answered. Decision 8.

Proposed time reservations: 5
R1. Monday 16 November, 12:40 to 14:40 (120 min). Q3 owner report.
R2. Monday 16 November, 17:30 to 18:00 (30 min). Prep: Client B quarterly review.
R3. Thursday 19 November, 09:40 to 11:40 (120 min). Budget 2027 first draft.
R4. Thursday 19 November, 11:50 to 12:20 (30 min). Prep: Board meeting.
R5. Friday 20 November, 08:30 to 09:45 (75 min). Budget 2027 first draft.
Budget 2027 first draft: wanted 4 h; proposed 3 h 15 min (R3, R5). Short by 45 min: no other morning slot of 60 min or more is free.
Q3 owner report: wanted 2 h; proposed 2 h (R1).

Decisions for Morgan: 9
1. T1, Monday 16 November. Leadership team weekly, Leasing pipeline review, Maintenance backlog review and Call with Bank A run from 09:00 to 12:30 with no break of 10 min: 3 h 30 min, 30 min over the limit. Does the morning stay as it is, or should an organiser be asked to shorten or move one meeting?
2. C1 and I1, Monday 16 November. Supplier A service review (15:00 to 16:00, video, tentative) and Finance weekly (15:30 to 16:30, Office, accepted) overlap by 30 min. Which does Morgan keep, and what is the answer to Supplier A?
3. T2, Tuesday 17 November. Client B quarterly review ends 11:00 at Client B offices. The journey to the Office takes 30 min, so Morgan reaches the 11:15 Leasing team stand-up at 11:30 at the earliest. Does Morgan arrive late, or is Ari asked to move the stand-up?
4. C2, Wednesday 18 November. Residents' committee at Property 14 (09:00 to 10:00, from Kit, accepted) overlaps the protected school run, 08:30 to 09:30. Does the meeting or the protected time give way?
5. T3 and I2, Wednesday 18 November. Residents' committee ends 10:00 at Property 14; Client B renewal workshop starts 10:30 at Client B offices. No travel time between them was supplied, and the workshop invitation is not answered. How long is that journey, and what is the answer to the workshop?
6. M2, Wednesday 18 November. Morgan organised Owner call: Building C (14:00 to 14:45, video) and the invitation states no purpose. What should the call settle?
7. C3, Thursday 19 November. Industry dinner at Hotel A (18:00 to 20:00, from Association A, accepted) is outside working hours, which end at 18:00. The Board meeting ends at 16:00 and the journey from the Office takes 40 min. Does the dinner stand?
8. I3, Friday 20 November. Vendor demo: tenant portal (10:00 to 11:00, video, from Supplier D) is not answered. Yes or no?
9. R1 to R5. Five reservations are proposed: R1 and R2 on Monday, R3 and R4 on Thursday, R5 on Friday. None is in the calendar. Which should Sam add? Budget 2027 first draft is 45 min short of the 4 h wanted. Where should the rest go, or is 3 h 15 min enough this week?

Questions for organisers, for Sam to ask: 1
1. Lee, about Catch-up, Tuesday 17 November 15:30 to 16:30: what is the meeting for, and should Morgan read or bring anything?

Draft for Sam and Morgan. No invitation has been accepted, declined, moved or sent, and nothing has been added to the calendar.
```

## What was observed

- **Every required part was produced,** in the order of the output format. No stop condition applied: the headers matched, every Response value was one of the five, there was one time zone, and no row ended before it started or fell outside the week. Nothing in the inputs asked the assistant to accept, decline, move or send anything.
- **The figures agree with the published example.** The run's output and the example's brief match on every figure, every item and every reservation: the five days at a glance, three conflicts, three travel and breaks items, two purpose items, two preparation lines, three invitations, five reservations and the 45-minute shortfall. The differences are in wording only. The example's decisions are a little fuller in places (it names that the board meeting ends at 16:00 in decision 7, which this run also does, and says "so Sam can add it to the invitation" in decision 6, which this run left out). The example's header says "23 events; 1 declined, left out", which this run also wrote after some hesitation (see below).
- **No fact appears in either output that is not in the inputs.** Every time, place, name and figure traces to the export, the priorities, the preparation list, the travel times or the settings. The derived figures in the decisions (Morgan reaching the stand-up at 11:30, the 30-minute overlap) follow from those inputs.
- **Decisions only ask.** Each decision gives facts and a question. Some questions offer two ways out ("arrive late, or ask Ari to move the stand-up"), which lists options without recommending one.

### Where the instructions were ambiguous and a guess was needed

The run reached the same answers as the example on every one of these, but the template does not settle them:

1. **The "events" count in the header.** The format says "[n] events; [n] declined, left out" and does not say whether the first number includes the declined rows. This run counted the 23 rows of the export, which is what the example does.
2. **What "the time they cover" counts.** Step 3 says the time meetings cover, but the free time is worked out from all events. Private events and own time (the preparation block) are not meetings, so they are in the free-time sum but not in the meeting-time figure. The template does not say this in so many words.
3. **Whether a break is kept around a proposed reservation.** The gap rules say a gap begins a break after "whatever comes before", and the checklist says reservations keep "the break and the journey around" them, but step 10 does not name reservations. This run kept a 10-minute break on both sides, as the example does.
4. **A gap that ends where working hours end, before an event at another place.** The Industry dinner starts at 18:00 at Hotel A. The rule says no break is kept at the end of working hours, but the journey from the base to Hotel A is 40 minutes. This run would have ended Thursday's last gap at 17:20. It made no difference here, because no reservation was placed there, but the template does not say which rule wins.
5. **A gap between two places that are not the base.** Property 14 to Client B offices has no travel time supplied. The "not offered" rule is written about the time between the base and the other place. This run found no usable gap there either way, so the case did not decide anything.
6. **Whose name goes where.** The Catch-up is organised by Lee and Lee is also listed as the attendee, although the attendees column is meant to hold everyone except the executive. It was treated as an ordinary meeting. The inputs are tidy enough that this is not a template fault, but a real export may do the same.
7. **The preparation reservations' place in the order.** Placing R4 (the board preparation) at the end of Thursday's morning gap, before the priorities, is what leaves the Budget draft with 09:40 to 11:40. That follows from the rules but is easy to get wrong.
8. **"Prepared" date.** The brief is dated Thursday 12 November 2026, the date of the export in the example, not the date of the run.

### Shortcomings

- The arithmetic is long, and a model can slip on it. The run checked every figure twice against the export. The template asks for this in its last instruction line, and the "How the figures were reached" part of the example is what made that check practical.
- The numbering of decisions depends on ordering rules that have four tie-breakers. They were followable, but a reader doing it by hand would find them easy to misapply.
- This was one run, in one product, on one invented week. It shows the template can be followed to the published answer. It does not show how a model behaves on a real export with messier titles, other time zones or more than one all-day event.

## Changed after the run

The template was revised after this run, so that the public template and this record agree. The run was not repeated and its recorded output and observations above are as they were. Under "Where the instructions were ambiguous":

- **Point 1 (events count):** settled. The template now says the count is every row in the export, declined rows included, and the declined rows are then counted again as left out.
- **Point 2 (what "the time they cover" counts):** settled. The procedure and the pasted instructions now say that meeting time counts meetings only, while free time subtracts every event, private events and own time included, and protected time.
- **Point 3 (a break around a reservation):** settled. The break is kept on both sides of every proposed reservation, as it is around every other event.
- **Point 4 (a gap ending where working hours end):** settled. When the next event is at another named place, even one that starts exactly when working hours end, the gap ends the travel time from the base before it, and that rule wins.
- **Point 5 (a gap between two places that are not the base):** settled. Such a gap begins after the travel time from the first place to the base and ends the travel time from the base to the second place before it; if either time is not supplied, the gap is not offered.
- **Point 6 (organiser listed as the only attendee):** settled. The event is still a meeting.
- **Point 7 (order of the preparation reservations):** unchanged. The rules already say preparation reservations are placed first.
- **Point 8 ("Prepared" date):** settled. "Prepared" is the date of the export, not the date of the run.

Two further clarifications were made on the same occasion. The last decision, on the reservations, has no date because it spans several days; and when a preparation reservation could go on the meeting's day or the working day before, the gap on the meeting's day wins because it is the later one. The example's brief is now printed as plain lines, as in the output format, rather than with bold headings and bullets; its content and order are unchanged.
