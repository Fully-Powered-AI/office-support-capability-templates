# Business trip plan: trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID `claude-opus-5-5`)
- **Date:** 2026-11-10

The inputs are the invented example in [`example.md`](example.md): the brief, the travel policy excerpt, the options table and the journey times, with the default settings. No client data was used.

## How the trial was run, and why it is not blind

I followed the fenced instruction block and the output format in `member/template.md`, as they stood after the independent review's minor points were applied, on those inputs only. This run is not blind and is not an independent test. I made those review edits myself just before the run, and I had already read the example's published output and the record of an earlier run on the same day. That earlier record is replaced by this one, because the instruction block and the output format changed after it; the model it named could not be confirmed. Where my plan matches the example, that may be because I had seen it. The ambiguities listed below are the more reliable signal.

## What came out

```
BUSINESS TRIP PLAN: Dana (operations director), Chicago, Tuesday 1 December 2026 to Thursday 3 December 2026
Prepared 10 November 2026 for Sam. Purpose: Client X kickoff and workshop; Supplier B visit. Cost centre: CC-410.
Changes from the last plan: first plan.
Trip dates: out Tuesday 1 December, back Thursday 3 December. 2 nights: 1 December, Chicago; 2 December, Chicago. Starts from: Oakland (OAK).
Policy: excerpt supplied (flights, hotels, meals, ground transport, approval). Exceptions approved by: Lee (CFO).
Settings: at the airport 90 min before departure, 30 min from landing to leaving; at each meeting 15 min early; prices checked again after 3 days. All times local.

To settle before booking: 1
1. No journey time or cost was supplied from the Supplier B office back to Hotel B on Wednesday
   after 15:00; the walk time given is for the Client X office to Supplier B only. How will Dana
   get back, and what should the estimate carry for it?

Fixed meetings
- Tuesday 1 December, 15:00 to 16:30. Client X kickoff. At the Client X office (Loop).
- Wednesday 2 December, 09:00 to 12:00. Client X workshop. At the Client X office (Loop).
- Wednesday 2 December, 14:00 to 15:00. Supplier B. At the Supplier B office (River North).
- Thursday 3 December, 08:30 to 09:30. Breakfast with the Client X CEO. At the Client X office (Loop).

Shortlist
Journey out
- Lowest that fits: F1, Airline A, OAK to ORD nonstop, 07:00 to 13:10, $214.00 (one way, economy,
  taxes included, carry-on). Direct, checked 9 November. Cancellation: changes for a fee.
  Policy: within (economy; the only fare from OAK that reaches the 15:00 kickoff).
- Alternative: none that fits.
Journey back
- Lowest that fits: F4, Airline A, ORD to OAK nonstop, 13:30 to 15:55, $198.00 (one way, economy,
  taxes included, carry-on). Direct, checked 9 November. Cancellation: changes for a fee.
  Policy: within (economy; departs within two hours of 11:45, the earliest workable departure).
- Alternative: F6, Airline B, ORD to OAK nonstop, 16:40 to 19:05, $231.00 (one way, economy,
  taxes included, carry-on). Direct, checked 9 November. Cancellation: no changes.
  Policy: over: departs more than two hours after 11:45 and costs $33.00 more than F4; approval
  from Lee (CFO).
Hotel
- Lowest that fits: H2, Hotel B, Loop, 5 min walk to the Client X office, 2 nights at $245.00 =
  $490.00, plus $85.75 taxes and fees = $575.75. Direct, checked 10 November.
  Cancellation: free until 29 November, 18:00. Policy: within ($245.00 a night against the
  $260.00 cap before taxes).
- Alternative: H3, Hotel C, Loop, 3 min walk to the Client X office, 2 nights at $289.00 =
  $578.00, plus $101.15 taxes and fees = $679.15. Third-party, checked 4 November. RECHECK.
  Cancellation: non-refundable. Policy: over: $29.00 a night above the $260.00 cap, $58.00 for
  the stay; approval from Lee (CFO).
Exception reason: none needed.

Set aside, and why
- F2, Airline B, $189.00: lands at ORD at 15:55, after the 15:00 kickoff starts.
- F3, Airline C, $176.00: leaves from SFO; the brief says Dana leaves from OAK. Not swapped in.
- F5, Airline B, from $129: a "from" fare in a fare alert, not a price for 3 December.
- H1, Hotel A, $159.00 a night: in Schaumburg, a 40-minute drive from the Client X office; the
  brief asks for a hotel within a 15-minute walk.
- H4, Hotel D, $219.00 a night: priced for 1 to 4 December, three nights; the brief is two
  nights, 1 to 3 December. Not rescaled.

Day by day, if the Lowest that fits options are booked
Tuesday 1 December
- 05:05 Leave home for OAK. Drive, 25 min, parking $28.00 a calendar day.
- 05:30 At OAK, 90 min before F1.
- 07:00 F1 departs OAK. Lands at ORD 13:10.
- 13:40 Leave ORD, 30 min after landing. Train to the Client X office, 45 min, $5.00 (taxi or
  rideshare 40 to 60 min, about $55).
- 14:25 At the Client X office.
- 15:00 to 16:30 Client X kickoff, Client X office. Spare before the meeting margin: 20 min.
- 16:30 Walk to Hotel B, 5 min, no cost.
Wednesday 2 December
- 09:00 to 12:00 Client X workshop, Client X office. Leave Hotel B by 08:40: walk, 5 min, no cost.
- 14:00 to 15:00 Supplier B, Supplier B office. Leave the Client X office by 13:20: walk, 25 min,
  no cost (car 15 min, about $15).
- 15:00 Supplier B office back to Hotel B: TRANSFER TIME NEEDED (question 1).
Thursday 3 December
- 08:30 to 09:30 Breakfast with the Client X CEO, Client X office. Leave Hotel B by 08:10: walk,
  5 min, no cost.
- 11:15 Leave the Client X office for ORD. Train, 45 min, $5.00 (taxi or rideshare 40 to 60 min,
  about $55).
- 12:00 At ORD, 90 min before F4.
- 13:30 F4 departs ORD. Lands at OAK 15:55.
- 16:25 Leave OAK, 30 min after landing. Drive home, 25 min; home about 16:50.

Cost estimate
- Journey out, F1: $214.00. Direct, checked 9 November. Policy: within.
- Journey back, F4: $198.00. Direct, checked 9 November. Policy: within.
- Hotel, H2: $575.75. Direct, checked 10 November. Policy: within.
- Ground transport: train ORD to the Client X office $5.00; train Client X office to ORD $5.00;
  walks $0.00 = $10.00. Supplied by Sam. Policy: within (train).
- Parking: 3 days x $28.00 = $84.00. Supplied by Sam. Policy: not covered by the excerpt.
- Meals: 2 travel days x $55.00 + 1 full day x $75.00 = $185.00. Policy allowance.
Total: $1,266.75 USD.
Over policy: none. Approval needed before booking from Lee: none.
Not priced: Supplier B office back to Hotel B on Wednesday (question 1).
Personal costs, kept out of the total: none.

Bookings still to make
1. F1, Airline A, OAK to ORD, 1 December 07:00, $214.00. Booked by: Sam. Book by: Tuesday
   17 November (policy: at least 14 days before departure). Approval: not needed under the policy
   supplied. Cancellation: changes for a fee. Check the price again if booking after 12 November.
2. F4, Airline A, ORD to OAK, 3 December 13:30, $198.00. Booked by: Sam. Book by: Thursday
   19 November (policy: at least 14 days before departure). Approval: not needed under the policy
   supplied. Cancellation: changes for a fee. Check the price again if booking after 12 November.
3. H2, Hotel B, 1 to 3 December, $575.75. Booked by: Sam. Book by: no deadline supplied.
   Approval: not needed under the policy supplied. Cancellation: free until 29 November, 18:00.
   Check the price again if booking after 13 November.
Already booked: nothing supplied.

Draft for Sam. Nothing has been booked, held, paid or sent.
```

## What was observed

Every part of the output format was produced. No stop condition applied: the destination and both dates were in the brief, the option headers matched the defaults, and nobody asked for a booking, a forecast or visa advice. No card, passport or login detail was in the inputs.

Every sum was re-added: $490.00 + $85.75 = $575.75, $578.00 + $101.15 = $679.15, and $214.00 + $198.00 + $575.75 + $10.00 + $84.00 + $185.00 = $1,266.75. The dates and weekdays were checked against a calendar: 1 December 2026 is a Tuesday, and 14 days before 1 and 3 December are Tuesday 17 and Thursday 19 November.

**How the edited rules applied on this example:**

- The journey time from the Client X office to Supplier B does not say "either way", so the reverse journey had no time and became question 1.
- Parking is not mentioned in the policy excerpt, so it is "not covered by the excerpt" on its line and is not a question.
- The rule that sets aside a journey home leaving before the earliest workable departure (11:45) removed nothing here: F4 and F6 both leave later, and F5 was already set aside as a From-price.
- Both alternatives that are over policy (F6 and H3) name Lee (CFO) as the approver, from the brief and the policy's CFO rule.

**Where the instructions were ambiguous or I had to choose:**

1. The policy says to take the lowest fare departing "within two hours of the time that suits the meetings". Neither the template nor the policy says what that time is. I took the earliest workable departure, 11:45. That makes F4 "within" and F6 "over". Another reading would change that.
2. The earliest workable departure depends on the transfer mode: 11:45 by train (45 min), 12:00 by taxi on the longer end of its range. I used the train, as the cheapest supplied mode that fits.
3. The format asks for a cost on every transfer, and walks have none. I wrote "no cost".
4. The template says "30 minutes from landing to leaving the arrival airport". I applied it at OAK on the way home as well as at ORD.
5. The brief gives no hotel check-in or check-out time and no rule on going back to the hotel on Thursday before the airport. I timed nothing for them and invented nothing.
6. F5 was checked four days before today, which would carry RECHECK, but it was set aside as a From-price; the format does not say whether a set-aside row shows RECHECK, so I left it off.
7. The settings appear in the instruction block as bracketed placeholders with defaults. The brief said "use the defaults", so this was clear here; a person who leaves them unfilled without saying so might be unsure.

**Differences from the published example** (see the caution above about having seen it):

- My question 1 adds that the walk time given is for one direction only.
- I wrote "no cost" on the walks and "30 min after landing" on the two airport exits; the example leaves these out. On F3 I wrote "Not swapped in" where the example says "Not compared", and I added "Not rescaled" on H4. The example marks Thursday as the check-out day; I did not. The Tuesday parking note reads slightly differently.
- The decisions, the shortlist, the approvers named, the set-aside list, the timetable, the total ($1,266.75), the book-by dates and the check-again dates are the same as the example's.

**Facts in either output that are not in the inputs:**

- Mine: none that I know of. Derived values (times, book-by dates, the 05:05 start, the 16:50 arrival home) all follow from the inputs and settings.
- The published example's closing paragraph says Dana chose to walk back from Supplier B, Sam added the time and re-ran the plan, and Sam booked the flights and hotel on 11 November. None of that is in the inputs; it is narrative added after the plan, outside the plan's output, in an example declared invented.

**The reviewer checklist** (items 1 to 8, which can be checked from the output): all pass on this output. Item 9 (the traveller reading the timetable) is a human step and was not tested.
