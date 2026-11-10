# Decision log: an invented example

*Illustrative example with invented data.* Quellmoor Cabinets is an invented 85-person maker of kitchen cabinets that sells through dealers. The people, dealers, figures and decisions below are invented too. Noor, the chief of staff, keeps the leadership's register of approved decisions. On Tuesday 10 November 2026, the day after the Monday leadership meeting, she runs the capability with the register so far, two pieces of new material and two status updates. First come her inputs, in full, then what came back.

## The inputs

### 1. Settings

```
Today: Tuesday 10 November 2026
Company or team: Quellmoor Cabinets leadership team
Register keeper: Noor (chief of staff)
Approvers: Daniel (CEO), any decision. Ines (CFO), spending decisions up to $25,000.
Look-ahead: 7 days
Held-back subjects: default (one person's pay, performance, health or conduct)
```

### 2. The register so far: decisions export

```
id,date_approved,topic,decision,approved_by,why,rejected,review_date,status,supersedes,superseded_by,source
D-001,2026-09-14,List prices,Raise list prices on the standard range by 4% from 1 January 2027,Daniel (CEO),Board and hardware costs rose 6% this year,"Raise prices 8% in one step - dealers warned of lost orders; Add a fuel surcharge instead - dealers dislike surcharges",2027-02-15,Active,,,Leadership meeting 14 Sep item 2
D-002,2026-09-28,Dealer payment terms,Keep dealer payment terms at 30 days,Daniel (CEO),Two large dealers asked for 60 days and cash cannot carry it this year,Move all dealers to 60-day terms - would tie up about $400000 of cash,2027-03-31,Active,,,Leadership meeting 28 Sep item 1
D-003,2026-10-12,Second finishing shift,Run a second finishing shift from 2 November to clear the order backlog,Daniel (CEO),Backlog is 7 weeks against a 4-week target,Outsource finishing to a third party - quality and lead-time risk,2026-12-14,Active,,,Leadership meeting 12 Oct item 1
D-004,2026-10-26,Eastgate showroom,Close the Eastgate showroom when its lease ends on 31 March 2027,Daniel (CEO),Visits have halved since dealers began showing the range,Move to a smaller showroom - still costs more than it brings in,2027-01-11,Active,,,Leadership meeting 26 Oct item 3
D-005,2026-10-26,Production scheduling,Replace paper production tickets with the scheduling module of the existing ERP at a cost of $18000,Ines (CFO),Paper tickets are lost between stations,Buy a separate scheduling system - a second system to maintain,2027-01-25,Active,,,Ines email 26 Oct
```

### 3. The register so far: actions export

```
id,decision_id,action,owner,due,status,completed_on,note
A-001,D-001,Send the 2027 price list to dealers,Grace,2026-11-30,Open,,
A-002,D-001,Load the 2027 prices into the ERP,Ines,2026-12-18,Open,,
A-003,D-002,Write to the two dealers who asked for 60 days,Grace,2026-10-09,Done,2026-10-07,
A-004,D-003,Agree the second-shift rota with the finishing team,Ravi,2026-10-23,Done,2026-10-22,
A-005,D-003,Fit extra extraction filters for the second shift,Pieter,2026-10-30,Open,,
A-006,D-004,Confirm the lease end date and notice period with the Eastgate landlord,Ines,2026-11-06,Open,,
A-007,D-005,Set up the scheduling module on a test site,Pieter,2026-11-20,Open,,
A-008,D-005,Train the four team leads on the scheduling module,Ravi,2026-12-11,Open,,
```

### 4. New material: the leadership meeting record (Noor's notes)

```
Leadership meeting, Monday 9 November 2026. Present: Daniel (CEO), Ines (CFO),
Ravi (COO), Grace (head of sales). Notes: Noor.

1. Dealer terms. Dealer A (about 18% of sales) asked again for 60 days and says
   a competitor offers 45. Agreed: dealers buying more than $250,000 a year move
   to 45-day terms from 1 December; everyone else stays on 30. Turned down:
   60 days for Dealer A alone - the other dealers would hear of it.
   APPROVED: Daniel, 9 Nov.
   Ines to change the terms in the ERP by 27 Nov. Price list and new terms to go
   to dealers in one letter - Ines sends it by 20 Nov.
2. Second shift. Backlog down to 5 weeks, still above the 4-week target. Agreed:
   keep the second shift until 15 January, then review. APPROVED: Daniel, 9 Nov.
   Ravi to confirm with the shift team by Friday.
3. Finishing capacity. Ravi floated sending the gloss-finish doors to an outside
   finisher in January to free the line. Talked through; Daniel wants costs
   first. Not decided. Ravi to get two quotes.
4. Showroom. Grace suggested keeping Eastgate open on Saturdays only until the
   lease ends. Discussion only.
5. Pieter's pay review: agreed. APPROVED: Daniel, 9 Nov.
```

### 5. New material: an email from Daniel

```
From: Daniel (CEO)
Date: Friday 6 November 2026
To: Noor
Diesel has gone up again. Approved: from 1 December, add a 2% fuel surcharge to
deliveries more than 100 miles from the plant. Grace to tell the dealers.
```

### 6. Status updates

```
- Pieter, message, Thursday 5 November 2026: "Extra extraction filters fitted on
  3 Nov, second shift is using them."
- Ines, at the leadership meeting on 9 November 2026: the Eastgate lease end date
  is still not confirmed; waiting on the landlord's reply.
```

## What came back

```
DECISION LOG UPDATE: Quellmoor Cabinets leadership team
Prepared Tuesday 10 November 2026 for Noor (chief of staff). Register as supplied: 5
decisions (5 active, 0 superseded, 0 withdrawn) and 8 actions (6 open). New material:
Daniel's email, 6 November 2026; leadership meeting record, 9 November 2026. Status
updates: 2.

To settle before anything is entered: 4
1. F1: D-006 brings back the fuel surcharge that D-001 turned down on 14 September.
   Does Daniel confirm he is reopening it, or should it go back to him?
2. A-009 has no date. By when should Grace tell the dealers about the fuel surcharge?
3. F2: D-007 contradicts D-002. Does D-007 supersede D-002, do both stand with a scope
   for each written by Daniel, or does it go back to him?
4. F3: A-011 and A-001 cover the same letter to dealers, with different owners and
   dates. Does A-011 replace A-001, does A-001 stand with Daniel removing A-011, or
   does it go back to him?

Proposed new entries: 3
D-006. Delivery fuel surcharge. Approved by Daniel (CEO) on Friday 6 November 2026.
  Decision: From 1 December 2026, deliveries more than 100 miles from the plant carry
  a 2% fuel surcharge.
  Why: Diesel has gone up again.
  Rejected: none recorded.
  Review: not set.
  Related: D-001, which turned down a fuel surcharge in place of the price rise.
  Held: F1.
  Source: Daniel's email, 6 November 2026.
  Actions:
    A-009. Tell the dealers about the fuel surcharge. Owner: Grace. Due: DATE NEEDED
           (no date in the source).

D-007. Dealer payment terms. Approved by Daniel (CEO) on Monday 9 November 2026.
  Decision: From 1 December 2026, dealers buying more than $250,000 a year move to
  45-day payment terms; all other dealers stay on 30 days.
  Why: Dealer A, about 18% of sales, asked again for 60 days and says a competitor
  offers 45.
  Rejected: 60-day terms for Dealer A alone. Reason given: the other dealers would hear
  of it.
  Review: not set.
  Related: D-002, which keeps every dealer on 30-day terms. Held: F2.
  Source: leadership meeting record, 9 November 2026, item 1.
  Actions:
    A-010. Change the dealer payment terms in the ERP. Owner: Ines. Due: Friday
           27 November 2026.
    A-011. Send the dealers one letter with the 2027 price list and the new terms.
           Owner: Ines. Due: Friday 20 November 2026. See F3.

D-008. Second finishing shift. Approved by Daniel (CEO) on Monday 9 November 2026.
  Decision: The second finishing shift continues until 15 January 2027 and is then
  reviewed.
  Why: The backlog is down to 5 weeks, still above the 4-week target.
  Rejected: none recorded.
  Review: Friday 15 January 2027.
  Related: D-003. Both can stand: D-008 says how long the shift D-003 started runs.
  D-003's review date, Monday 14 December 2026, stays as recorded; D-008's is Friday
  15 January 2027.
  Source: leadership meeting record, 9 November 2026, item 2.
  Actions:
    A-012. Confirm the extension with the second-shift team. Owner: Ravi. Due: Friday
           13 November 2026 ("by Friday").

Flags: 3
F1. REVIVES A REJECTED PROPOSAL
  New: D-006, a 2% fuel surcharge on deliveries more than 100 miles from the plant
       from 1 December 2026.
  Earlier: D-001, approved 14 September 2026 (raise list prices by 4% from 1 January
           2027), turned down "Add a fuel surcharge instead". Reason given: dealers
           dislike surcharges.
  Choices: (1) Daniel confirms he is reopening it, and D-006 says "Reopens the option
           turned down in D-001 on 14 September 2026, confirmed by Daniel". (2) Back
           to Daniel. (3) Not entered. Held until Noor settles it with Daniel.
F2. CONTRADICTS AN EARLIER DECISION
  New: D-007, 45-day terms from 1 December 2026 for dealers buying more than $250,000
       a year.
  Earlier: D-002, approved 28 September 2026: keep dealer payment terms at 30 days.
           D-002 also turned down 60-day terms for all dealers; D-007 sets 45 days for
           some dealers, so it does not bring that option back.
  Choices: (1) D-007 supersedes D-002, which stays in the register marked "Superseded
           by D-007". (2) Both stand, with the scope of each written by Daniel.
           (3) Back to Daniel. Held until Noor settles it with Daniel.
F3. DUPLICATE ACTION
  New: A-011, send the dealers one letter with the 2027 price list and the new terms.
       Owner: Ines. Due: Friday 20 November 2026.
  Earlier: A-001 (D-001), send the 2027 price list to dealers. Owner: Grace. Due:
           Monday 30 November 2026. Open.
  Choices: (1) Keep A-011 and mark A-001 Cancelled, replaced by A-011. (2) Keep A-001
           and Daniel removes A-011. (3) Back to Daniel. Held until Noor settles it
           with Daniel.

Not entered: discussed, not approved: 2
- Send the gloss-finish doors to an outside finisher in January to free the line.
  Talked through; Daniel wants costs first. Ravi to get two quotes, with no date.
  Source: leadership meeting record, 9 November 2026, item 3. Needs approval from:
  Daniel. If approved, it would bring back the option D-003 turned down on 12 October
  2026, "Outsource finishing to a third party" (reason given: quality and lead-time
  risk).
- Keep the Eastgate showroom open on Saturdays only until the lease ends. Source:
  leadership meeting record, 9 November 2026, item 4. Needs approval from: Daniel.
  Touches D-004 (close Eastgate when its lease ends on 31 March 2027); as discussed,
  both could stand.

Held back: one approved item about one person's pay, for Noor only.

Action status changes: 1
- A-005. Fit extra extraction filters for the second shift. Owner: Pieter. Open to
  Done, completed Tuesday 3 November 2026. Source: Pieter, message, Thursday 5 November
  2026.

Overdue: 2
- A-005. Fit extra extraction filters for the second shift. Owner: Pieter. Due Friday
  30 October 2026, 11 days overdue. Update: Pieter reports it done on 3 November; see
  Action status changes.
- A-006. Confirm the lease end date and notice period with the Eastgate landlord.
  Owner: Ines. Due Friday 6 November 2026, 4 days overdue. Update: still not
  confirmed, waiting on the landlord's reply (Ines, leadership meeting, 9 November
  2026).

Due in the next 7 days (Tuesday 10 November to Tuesday 17 November 2026): 1
- A-012. Confirm the extension with the second-shift team. Owner: Ravi. Due Friday
  13 November 2026. (proposed)

Reviews due in the next 7 days: None

Register changes, once approved:
- Add D-006 and A-009: waits on questions 1 and 2.
- Add D-007 and A-010: waits on question 3.
- Add A-011: waits on questions 3 and 4.
- Add D-008 and A-012: no question open.
- Mark D-002 "Superseded by D-007": only if choice (1) is made under F2.
- Mark A-001 Cancelled, replaced by A-011: only if choice (1) is made under F3.
- Mark A-005 Done, completed 3 November 2026.

Draft for Noor. Nothing has been entered in the register and nothing has been sent.
```

Noor took the three flags and the missing date to Daniel that afternoon. He confirmed he was reopening the fuel surcharge, set Grace's date, chose to let D-007 supersede D-002, and gave the dealer letter to Ines. Noor gave his answers to the assistant, read the updated draft, which then read "None. Ready for Noor to enter.", and made the changes in the register herself.
