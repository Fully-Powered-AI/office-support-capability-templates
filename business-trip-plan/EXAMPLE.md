# Business trip plan: an invented example

*Illustrative example with invented data.* An invented 120-person engineering consultancy is sending Dana, its operations director, to Chicago for three days. Sam, her executive assistant, books her travel. Client X, Supplier B, Airlines A to C and Hotels A to D are invented placeholders, and so are Dana, Sam, Lee and every flight, room, price and journey time below. The city and airport names are real places, used only so the timetable reads naturally.

Sam runs the capability on Tuesday 10 November 2026 with the four things below, and uses the default settings.

## What Sam supplied

### The brief

```
Today: Tue 10 Nov 2026
Traveller: Dana, operations director. I'm Sam, her assistant; I book.
Purpose: Client X kickoff and workshop; Supplier B visit.
Destination: Chicago. Out Tue 1 Dec, back Thu 3 Dec. Leaves from Oakland (OAK).
Meetings:
- Tue 1 Dec 15:00-16:30 Client X kickoff, Client X office (Loop)
- Wed 2 Dec 09:00-12:00 Client X workshop, Client X office (Loop)
- Wed 2 Dec 14:00-15:00 Supplier B, Supplier B office (River North)
- Thu 3 Dec 08:30-09:30 breakfast with Client X CEO, Client X office (Loop)
Needs: hotel within a 15-minute walk of the Client X office; no overnight
flights; carry-on only.
Cost centre: CC-410. Exceptions approved by: Lee (CFO).
Already booked: nothing.
Settings: use the defaults.
```

### The travel policy excerpt

```
Flights: economy. Book at least 14 days before departure. Take the lowest
fare departing within two hours of the time that suits the meetings.
Hotels: Chicago cap $260 a night before taxes.
Meals: $75 a full day; $55 on a travel day.
Ground transport: train, taxi or rideshare. Keep receipts over $25.
Anything over policy needs the CFO's approval before booking.
```

### The options found

```
Ref | Type | Provider | Details | Dates | Depart | Arrive | Price | Price covers | Cancellation | Checked on | Source
F1 | Flight | Airline A | OAK-ORD nonstop | 2026-12-01 | 07:00 | 13:10 | 214.00 | one way, economy, taxes incl., carry-on | changes for a fee | 2026-11-09 | Airline A website
F2 | Flight | Airline B | OAK-ORD nonstop | 2026-12-01 | 09:45 | 15:55 | 189.00 | one way, economy, taxes incl., carry-on | no changes | 2026-11-09 | travel tool
F3 | Flight | Airline C | SFO-ORD nonstop | 2026-12-01 | 07:30 | 13:45 | 176.00 | one way, economy, taxes incl., carry-on | changes for a fee | 2026-11-09 | travel tool
F4 | Flight | Airline A | ORD-OAK nonstop | 2026-12-03 | 13:30 | 15:55 | 198.00 | one way, economy, taxes incl., carry-on | changes for a fee | 2026-11-09 | Airline A website
F5 | Flight | Airline B | MDW-OAK nonstop | 2026-12-03 | 12:15 | 14:40 | from 129 | fares from, in a fare alert | not stated | 2026-11-06 | fare alert email
F6 | Flight | Airline B | ORD-OAK nonstop | 2026-12-03 | 16:40 | 19:05 | 231.00 | one way, economy, taxes incl., carry-on | no changes | 2026-11-09 | travel tool
H1 | Hotel | Hotel A | Schaumburg, 40 min drive to Client X office | 2026-12-01 to 2026-12-03 | | | 159.00 a night | before taxes | free cancellation until 2026-11-29 | 2026-11-10 | Hotel A website
H2 | Hotel | Hotel B | Loop, 5 min walk to Client X office | 2026-12-01 to 2026-12-03 | | | 245.00 a night | before taxes; taxes and fees 85.75 for the stay | free cancellation until 2026-11-29 18:00 | 2026-11-10 | travel tool
H3 | Hotel | Hotel C | Loop, 3 min walk to Client X office | 2026-12-01 to 2026-12-03 | | | 289.00 a night | before taxes; taxes and fees 101.15 for the stay | non-refundable | 2026-11-04 | booking comparison site
H4 | Hotel | Hotel D | Loop, 12 min walk to Client X office | 2026-12-01 to 2026-12-04 | | | 219.00 a night | before taxes | free cancellation until 2026-11-30 | 2026-11-10 | travel tool
```

### The journey times

```
From a maps app, 10 Nov:
Home and OAK: drive 25 min, either way. OAK parking $28 a calendar day.
ORD to Client X office: train 45 min, $5; taxi or rideshare 40-60 min, about $55.
Hotel B and Client X office: walk 5 min, either way.
Client X office to Supplier B: walk 25 min; car 15 min, about $15.
Client X office to ORD: train 45 min, $5; taxi or rideshare 40-60 min, about $55.
```

## What came back

```
BUSINESS TRIP PLAN: Dana (operations director), Chicago, Tuesday 1 December 2026 to Thursday 3 December 2026
Prepared 10 November 2026 for Sam. Purpose: Client X kickoff and workshop; Supplier B visit. Cost centre: CC-410.
Changes from the last plan: first plan.
Trip dates: out Tuesday 1 December, back Thursday 3 December. 2 nights: 1 December, Chicago; 2 December, Chicago. Starts from: Oakland (OAK).
Policy: excerpt supplied (flights, hotels, meals, ground transport, approval). Exceptions approved by: Lee (CFO).
Settings: at the airport 90 min before departure, 30 min from landing to leaving; at each meeting 15 min early; prices checked again after 3 days. All times local.

To settle before booking: 1
1. No journey time or cost was supplied from the Supplier B office back to Hotel B on Wednesday
   afternoon. How will Dana get back, and what should the estimate carry for it?

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
  Policy: over: departs more than two hours after 11:45 and costs $33.00 more than F4;
  approval from Lee (CFO).
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
- F3, Airline C, $176.00: leaves from SFO; the brief says Dana leaves from OAK. Not compared.
- F5, Airline B, from $129: a "from" fare in a fare alert, not a price for 3 December.
- H1, Hotel A, $159.00 a night: in Schaumburg, a 40-minute drive from the Client X office; the
  brief asks for a hotel within a 15-minute walk.
- H4, Hotel D, $219.00 a night: priced for 1 to 4 December, three nights; the brief is two
  nights, 1 to 3 December.

Day by day, if the Lowest that fits options are booked
Tuesday 1 December
- 05:05 Leave home for OAK. Drive, 25 min; park at OAK.
- 05:30 At OAK, 90 min before F1.
- 07:00 F1 departs OAK. Lands at ORD 13:10.
- 13:40 Leave ORD. Train to the Client X office, 45 min, $5.00 (taxi or rideshare 40 to 60 min,
  about $55).
- 14:25 At the Client X office.
- 15:00 to 16:30 Client X kickoff, Client X office. Spare before the meeting margin: 20 min.
- 16:30 Walk to Hotel B, 5 min.
Wednesday 2 December
- 09:00 to 12:00 Client X workshop, Client X office. Leave Hotel B by 08:40: walk, 5 min.
- 14:00 to 15:00 Supplier B, Supplier B office. Leave the Client X office by 13:20: walk, 25 min
  (car 15 min, about $15).
- 15:00 Supplier B office back to Hotel B: TRANSFER TIME NEEDED (question 1).
Thursday 3 December
- 08:30 to 09:30 Breakfast with the Client X CEO, Client X office. Leave Hotel B by 08:10: walk,
  5 min. Check-out day.
- 11:15 Leave the Client X office for ORD. Train, 45 min, $5.00 (taxi or rideshare 40 to 60 min,
  about $55).
- 12:00 At ORD, 90 min before F4.
- 13:30 F4 departs ORD. Lands at OAK 15:55.
- 16:25 Leave OAK. Drive home, 25 min; home about 16:50.

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

Sam asked Dana how she wanted to get back from Supplier B on Wednesday; she chose to walk, and Sam added the time to the journey list and ran the plan again. Dana read the timetable, and Sam booked the two flights and the hotel herself on 11 November, inside every check-again date. Nothing in this example happened to a real company.
