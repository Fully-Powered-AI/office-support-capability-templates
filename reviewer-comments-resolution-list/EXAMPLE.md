# Reviewer comments into one resolution list: an invented example

*Illustrative example with invented data.* The organisation, the funder, the people, the report and every figure below are invented. Charity A is an invented community food charity. Ines, its communications lead, owns the quarterly report to its funder, Funder B. Three people reviewed version 3: Kofi, the programme director, and Margit, the finance manager, each returned a marked-up copy, which Ines exported to a comments-and-changes file; Theo, the board chair, sent an email. First come the inputs Ines supplied, in full, then the list the capability returned.

## The inputs

### 1. Settings

```
Owner: Ines, communications lead
Today: 15 October 2026
Deadline: 23 October 2026, report due to Funder B
Watch list: the default
Naming rule: reviewers named as given
```

### 2. The base version

```
FUNDER REPORT: JULY TO SEPTEMBER 2026 (version 3)

1. Summary
This quarter we served 4,180 households, up from 3,760 last quarter. Our new
Saturday distribution opened on 6 July and now serves around 300 households a week.

2. Meals and families served
We distributed 61,400 meals. Fresh produce made up 38 per cent of what we gave out,
our highest share yet. Demand rose most among families with children under five.

3. Volunteers
112 volunteers gave 5,960 hours. We trained 18 new shift leads.

4. Spending against the grant
We spent $48,200 of the $52,000 quarterly grant. The $3,800 underspend comes from a
delayed refrigeration repair, now booked for October.

5. Next quarter
We will open a second evening session in November and begin a pilot with two
schools.
```

### 3. Export of Kofi's marked-up copy

```
reviewer,date,type,section,anchor_text,proposed_text,comment
Kofi (programme director),2026-10-12,replace,1. Summary,around 300 households a week,about 320 households a week,
Kofi (programme director),2026-10-12,comment,2. Meals and families served,our highest share yet,,Can we say why? The new grower partnership.
Kofi (programme director),2026-10-12,replace,2. Meals and families served,[chart],[chart],
Kofi (programme director),2026-10-12,insert,3. Volunteers,We trained 18 new shift leads.,Volunteer turnover fell to 9 per cent.,
Kofi (programme director),2026-10-12,delete,5. Next quarter,and begin a pilot with two schools,,Schools pilot is not confirmed yet.
Kofi (programme director),2026-10-12,comment,Table 1,Table 1: households by area,,Table 1 numbers need updating for September.
```

### 4. Export of Margit's marked-up copy

```
reviewer,date,type,section,anchor_text,proposed_text,comment
Margit (finance manager),2026-10-13,replace,1. Summary,around 300 households a week,around 280 households a week,Register average Jul-Sep is 281.
Margit (finance manager),2026-10-13,replace,4. Spending against the grant,"$48,200","$48,650",
Margit (finance manager),2026-10-13,replace,4. Spending against the grant,"The $3,800 underspend","The $3,350 underspend",Late invoice from the van lease posted 10 Oct.
Margit (finance manager),2026-10-13,comment,5. Next quarter,begin a pilot with two schools,,Keep this in. The funder asked about schools last quarter.
```

### 5. Theo's email

```
From: Theo (board chair)
Date: 14 October 2026
Subject: Funder report v3

Ines, I've read version 3. Three things:
- The summary should open with the Saturday distribution. It's the headline.
- In the volunteers section, add a line thanking the shift leads.
- In the spending section, say the refrigeration repair is booked for 21 October, not just October.
Thanks, Theo
```

## The output

```
RESOLUTION LIST: Funder report: July to September 2026, version 3

For: Ines, communications lead. Prepared 15 October 2026 from 3 reviewer inputs. Deadline: 23 October 2026, report due to Funder B.
Reviewers:
R1 Kofi, programme director: export of a marked-up copy, dated 12 October 2026. 6 items.
R2 Margit, finance manager: export of a marked-up copy, dated 13 October 2026. 4 items.
R3 Theo, board chair: email, dated 14 October 2026. 3 items.
Items: 13 (4 replacements, 1 insertion, 1 deletion, 0 moves, 0 formatting, 3 comments, 3 notes, 1 check by hand). Clashes: 2. Watch items: 7. Open: 13. Decided by the owner: 0.

To settle first: 4
1. Clash C1 (R1-01, R2-01): two different figures for the Saturday households.
2. Clash C2 (R1-05, R2-04): remove or keep the schools pilot.
3. Not placed (R1-06): Kofi's comment on "Table 1: households by area"; the base has no Table 1.
4. Check by hand (R1-03): a change in section 2 that the export shows only as "[chart]".

Clashes: 2
C1. 1. Summary: "around 300 households a week"
  R1-01 Kofi: replace with "about 320 households a week"
  R2-01 Margit: replace with "around 280 households a week", with the comment "Register average Jul-Sep is 281."
  Why they cannot both be done: two different figures for the same words. Status: Open.
C2. 5. Next quarter: "and begin a pilot with two schools"
  R1-05 Kofi: remove the words, with the comment "Schools pilot is not confirmed yet."
  R2-04 Margit: comment "Keep this in. The funder asked about schools last quarter."
  Why they cannot both be done: one removes the words the other asks to keep. Status: Open.

Checklist by section
1. Summary
R1-01 Kofi · replacement · Place: exact
  Base: "around 300 households a week"
  Replace with: "about 320 households a week"
  Clash: C1 · Watch: figure
  Status: Open. Owner's note: none
R2-01 Margit · replacement · Place: exact
  Base: "around 300 households a week"
  Replace with: "around 280 households a week"
  Reviewer's comment: "Register average Jul-Sep is 281." · Clash: C1 · Watch: figure
  Status: Open. Owner's note: none
R3-01 Theo · note · Place: section only
  Base: no exact words given
  Note: "The summary should open with the Saturday distribution. It's the headline."
  Status: Open. Owner's note: none
2. Meals and families served
R1-02 Kofi · comment · Place: exact
  Base: "our highest share yet"
  Comment: "Can we say why? The new grower partnership."
  Status: Open. Owner's note: none
R1-03 Kofi · check by hand · Place: section only
  Base: no exact words given
  What the input shows: "[chart]"
  Check by hand: the export shows the change only as "[chart]", and the base text supplied has no chart in words
  Status: Open. Owner's note: none
3. Volunteers
R1-04 Kofi · insertion · Place: exact
  Base: "We trained 18 new shift leads."
  Insert: "Volunteer turnover fell to 9 per cent."
  Position: not stated · Watch: figure
  Status: Open. Owner's note: none
R3-02 Theo · note · Place: section only
  Base: no exact words given
  Note: "In the volunteers section, add a line thanking the shift leads."
  Status: Open. Owner's note: none
4. Spending against the grant
R2-02 Margit · replacement · Place: exact
  Base: "$48,200"
  Replace with: "$48,650"
  Watch: amount
  Status: Open. Owner's note: none
R2-03 Margit · replacement · Place: exact
  Base: "The $3,800 underspend"
  Replace with: "The $3,350 underspend"
  Reviewer's comment: "Late invoice from the van lease posted 10 Oct." · Watch: amount
  Status: Open. Owner's note: none
R3-03 Theo · note · Place: near
  Base: "The $3,800 underspend comes from a delayed refrigeration repair, now booked for October."
  Note: "In the spending section, say the refrigeration repair is booked for 21 October, not just October."
  Watch: date
  Status: Open. Owner's note: none
5. Next quarter
R1-05 Kofi · deletion · Place: exact
  Base: "and begin a pilot with two schools"
  Remove: "and begin a pilot with two schools"
  Reviewer's comment: "Schools pilot is not confirmed yet." · Clash: C2 · Watch: promise about future work · Owner to confirm who signs this off.
  Status: Open. Owner's note: none
R2-04 Margit · comment · Place: exact
  Base: "begin a pilot with two schools"
  Comment: "Keep this in. The funder asked about schools last quarter."
  Clash: C2
  Status: Open. Owner's note: none

Not placed: 1
R1-06 Kofi · comment · Not found in the base
  Anchor given: "Table 1: households by area", under "Table 1"
  Comment: "Table 1 numbers need updating for September."
  Status: Open. Owner's note: none

Check by hand: 1
R1-03: the export shows a change in section 2, Meals and families served, only as "[chart]"; open Kofi's marked-up copy to see it.

Watch items: 7
R1-01: figure
R1-04: figure
R1-05: promise about future work
R2-01: figure
R2-02: amount
R2-03: amount
R3-03: date

Agreements: none

Edits the owner accepted, to make in the base: none yet

Resolution list only. Nothing in Funder report: July to September 2026 has been edited, accepted, declined or merged, and nothing has been sent.
```

Every item traces to a row in one of the two exports or a line of Theo's email, and every base quotation is in version 3 as supplied. What happens next is Ines's: she decides each item, makes the edits in version 3 herself and replies to her reviewers.
