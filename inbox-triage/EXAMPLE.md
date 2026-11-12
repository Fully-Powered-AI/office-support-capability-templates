# Inbox triage: an invented example

*Illustrative example with invented data.* Tallow Lane Property Management is an invented 25-person firm that manages office buildings for their owners. Its managing director, Helen Marsh, and her executive assistant, Owen Hale, are invented, as are every sender, address, building and amount below. Every address uses the reserved `.example` domain. Owen runs the workflow template at 08:30 on Monday 9 November 2026, before Helen arrives. First come the inputs he supplied, in full, then the triage that came back.

## The inputs

### 1. Whose inbox, and the settings

```
Inbox: Helen Marsh, managing director, helen@tallowlane.example
Run by: Owen Hale, executive assistant
Today: Monday 9 November 2026, 08:30
The business: tallowlane.example. Colleagues: Owen Hale (executive assistant),
  Ruth Bell (bookkeeper, ruth@tallowlane.example), Marco Diaz (maintenance
  manager, marco@tallowlane.example), Lena Fry (leasing manager,
  lena@tallowlane.example)
Day ends: 17:30. Working days: Monday to Friday. Can wait: 3 working days.
Spending threshold: any approval of $2,500 or more goes to Reply today.
Key senders: anyone at northgate-holdings.example (owner of Harbour Court).
Private subjects: Helen's personal and family matters; any employee's pay,
  health, performance or conduct.
Draft length: 120 words.
```

### 2. Routing list

```
Supplier invoices and statements -> Ruth Bell, bookkeeper
Repairs and maintenance -> Marco Diaz, maintenance manager
Viewings and new tenancy enquiries -> Lena Fry, leasing manager
```

### 3. Promises Helen made recently

```
- To Lena Fry, on Thursday 5 November: my answer on the January rent review
  letters, by Wednesday 11 November.
```

### 4. Two replies Helen was happy with

```
Hi Marco,
Yes, go ahead. Keep me posted on the date.
Helen

Hi Graham,
Thanks for this. I'll look at it tonight and come back to you tomorrow morning.
Helen
```

### 5. The export: inbox-export-2026-11-09.csv

```
Date,From,To,Cc,Subject,Body
2026-11-04 16:20,Helen Marsh <helen@tallowlane.example>,graham@northgate-holdings.example,,Q3 service charge summary,"Graham, thanks for the call. I'll have the Q3 service charge summary to you by Friday. Helen"
2026-11-05 17:05,Asha Rao <asha@raodesign.example>,helen@tallowlane.example,,"Entry buzzer, suite 4","Hi Helen, the entry buzzer for suite 4 at Harbour Court stopped working this afternoon. Can someone take a look? Asha"
2026-11-06 10:30,Nina Cho <nina@chofloorplans.example>,helen@tallowlane.example,,Coffee?,"Helen, fancy a coffee in the next couple of weeks? I'd like to talk about the Riverside fit-outs. Nina"
2026-11-06 11:20,Kestrel Cleaning Accounts <accounts@kestrelcleaning.example>,helen@tallowlane.example,,"Invoice KC-2291, October cleaning","Please find attached invoice KC-2291 for October cleaning at Harbour Court, $3,180.00, due 20 November 2026. Payment by bank transfer to the account on your file. Kestrel Cleaning"
2026-11-06 14:10,Tom Weller <tom@wellerarchitects.example>,helen@tallowlane.example,,"Viewing, Unit 2B Harbour Court","Hello Helen, could we see Unit 2B next week? Any afternoon suits. Tom Weller"
2026-11-06 15:02,Lena Fry <lena@tallowlane.example>,tom@wellerarchitects.example,helen@tallowlane.example,"Re: Viewing, Unit 2B Harbour Court","Hi Tom, Thursday 12 November at 2pm works. I'll meet you at reception. Lena"
2026-11-06 16:42,Graham Pike <graham@northgate-holdings.example>,helen@tallowlane.example,,Re: Q3 service charge summary,"Helen, any news on the Q3 summary? I need it before our board call on Wednesday 11th. Graham"
2026-11-07 09:15,Asha Rao <asha@raodesign.example>,helen@tallowlane.example,,"Re: Entry buzzer, suite 4","Helen, this is my second message. The suite 4 buzzer is still dead and we have clients visiting from Monday. When will it be fixed? Asha"
2026-11-07 12:00,Pellowby Desk <receipts@pellowbydesk.example>,helen@tallowlane.example,,Your Pellowby Desk receipt,"Thank you for your payment of $49.00 for Pellowby Desk Team, November 2026."
2026-11-07 18:30,Lettings Leaders Digest <news@lettingsleaders.example>,helen@tallowlane.example,,This week in property management,"Five trends shaping office leasing this winter, plus our events calendar."
2026-11-08 08:12,Jo Abbott <jo@abbottstudio.example>,helen@tallowlane.example,,Small office from January?,"Hi, do you have a small office free from January, around six desks? Jo Abbott, Abbott Studio"
2026-11-08 10:44,Murrowfinch <hello@murrowfinch.example>,helen@tallowlane.example,,Boost tenant engagement in 2027,"Hi Helen, Murrowfinch gives property managers one app for every tenant request. Can we book 15 minutes this week?"
2026-11-08 13:25,,helen@tallowlane.example,,Fwd:,"See below, thoughts?"
2026-11-08 19:10,Mark Marsh <mark.marsh@mailbox.example>,helen@tallowlane.example,,Thursday,"Can you do pickup on Thursday? I'm away until late."
2026-11-08 21:03,Kestrel Cleaning Accounts <accounts@kestre1cleaning.example>,helen@tallowlane.example,,URGENT: new bank details,"Dear Helen, our bank has changed. Please pay invoice KC-2291 ($3,180.00) to the new account below today to avoid a late fee. New account: Kestrel Cleaning Ltd, account ending 4471. Please don't call our office, the lines are down. Kestrel Cleaning"
2026-11-09 07:40,Ines Moreau <ines@pmassociation.example>,helen@tallowlane.example,,Speaking at our February forum,"Dear Helen, we'd love you to join a panel on tenant retention at our forum on 18 February. Could you let us know by 20 November? Ines Moreau, Programme lead"
2026-11-09 08:05,Marco Diaz <marco@tallowlane.example>,helen@tallowlane.example,,"Car park barrier quote, Harbour Court: need your OK","Helen, the quote to replace the Harbour Court car park barrier is $7,400. They can start Wednesday if we confirm by end of today. Quote attached. Marco"
```

## The output

```
INBOX TRIAGE: Helen Marsh, Monday 9 November 2026, as of 08:30

Prepared for: Owen Hale and Helen Marsh. Source: inbox-export-2026-11-09.csv, 17 rows, Wednesday 4 November to Monday 9 November 2026. Threads: 14.
Settings: day ends 17:30; can-wait replies within 3 working days; routing list supplied; colleague replies checked; voice from 2 samples; promises list supplied.

Headline: 14 threads. Held for Helen: 1. Reply today: 3. For someone else: 2. Can wait: 2. Already covered: 1. Private: 1. No reply needed: 3. Could not sort: 1.

HELD FOR HELEN, NO DRAFT: 1
H1. Kestrel Cleaning Accounts <accounts@kestre1cleaning.example>, Sunday 8 November 21:03. Subject: URGENT: new bank details. Asks: "Please pay invoice KC-2291 ($3,180.00) to the new account below today to avoid a late fee." and "Please don't call our office, the lines are down." Hold: new bank details and an urgent payment. Address check: this message came from kestre1cleaning.example, with the digit 1; Kestrel's invoice on Friday 6 November came from kestrelcleaning.example, with the letter l. Next step: before any money moves, Helen or Ruth rings Kestrel Cleaning on the number in Tallow Lane's own supplier records, and asks whether its bank details have changed. Linked to: E1.

REPLY TODAY: 3
T1. Marco Diaz <marco@tallowlane.example>, Monday 9 November 08:05. Subject: Car park barrier quote, Harbour Court: need your OK. Ask: Helen's approval of the quote to replace the Harbour Court car park barrier. Amounts and dates: $7,400; start Wednesday if confirmed by end of today; quote attached. Waiting since: Monday 9 November 08:05; 1 message. Earlier promise: none found. If it waits until tomorrow: the Wednesday start, offered only if confirmed by end of today, is lost outright.
Draft T1, to marco@tallowlane.example, re: Car park barrier quote, Harbour Court: need your OK:
Hi Marco,
[Yes, go ahead at $7,400 for a Wednesday start. / Not yet: (reason).]
Helen
Gaps: [Yes, go ahead at $7,400 for a Wednesday start. / Not yet: (reason).]: Helen's decision.

T2. Asha Rao <asha@raodesign.example>, Saturday 7 November 09:15. Subject: Re: Entry buzzer, suite 4. Ask: when the entry buzzer for suite 4 at Harbour Court will be fixed. Amounts and dates: it stopped working Thursday afternoon; clients visiting from Monday (today). Waiting since: Thursday 5 November 17:05; 2 messages. Earlier promise: none found. If it waits until tomorrow: a second working day of Asha's clients arriving to a dead buzzer, with both her messages unanswered.
Draft T2, to asha@raodesign.example, re: Entry buzzer, suite 4:
Hi Asha,
Sorry you've had to write twice. Marco Diaz, our maintenance manager, is dealing with the suite 4 buzzer, and [when it will be fixed: only once Marco has said].
Helen
Gaps: [when it will be fixed: only once Marco has said]. Send after the forwarding note below has gone to Marco.
Forward to: Marco Diaz, maintenance manager. Forwarding note, for a person to forward with the original attached:
Marco, Asha Rao (asha@raodesign.example) reported the entry buzzer for suite 4 at Harbour Court not working on Thursday 5 November at 17:05 and wrote again on Saturday 7 November. She has clients visiting from today. Please deal with it and tell me when it will be fixed so I can tell her. I haven't promised her a time.
Helen

T3. Graham Pike <graham@northgate-holdings.example>, Friday 6 November 16:42. Subject: Re: Q3 service charge summary. Ask: news on the Q3 service charge summary. Amounts and dates: he needs it before his board call on Wednesday 11 November. Waiting since: Friday 6 November 16:42; 1 message. Earlier promise: "I'll have the Q3 service charge summary to you by Friday.", Wednesday 4 November. If it waits until tomorrow: the summary promised for Friday slips another day, with Graham's board call on Wednesday.
Draft T3, to graham@northgate-holdings.example, re: Q3 service charge summary:
Hi Graham,
You'll have the Q3 service charge summary [when Graham will have it, before the board call on Wednesday 11 November]. Sorry it's later than I said.
Helen
Gaps: [when Graham will have it, before the board call on Wednesday 11 November]: not in the messages or inputs; Helen to say.

FOR SOMEONE ELSE: 2
E1. Kestrel Cleaning Accounts <accounts@kestrelcleaning.example>, Friday 6 November 11:20. Subject: Invoice KC-2291, October cleaning. What it is: a supplier invoice for October cleaning at Harbour Court, $3,180.00, due 20 November 2026, payable to the account on file. Goes to: Ruth Bell, bookkeeper. Acknowledgement from Helen: not needed: handler replies.
Forwarding note E1, to Ruth Bell, for a person to forward with the original attached:
Ruth, Kestrel Cleaning invoice KC-2291 for October cleaning at Harbour Court: $3,180.00, due 20 November 2026, payable by bank transfer to the account on file. Separately, a message on Sunday 8 November from a different address, accounts@kestre1cleaning.example, asked for this invoice to be paid today to new bank details. Please don't use those details until someone has rung Kestrel on the number in our supplier records.
Helen

E2. Jo Abbott <jo@abbottstudio.example>, Sunday 8 November 08:12. Subject: Small office from January? What it is: a new tenancy enquiry for a small office of around six desks from January. Goes to: Lena Fry, leasing manager. Acknowledgement from Helen: not needed: handler replies.
Forwarding note E2, to Lena Fry, for a person to forward with the original attached:
Lena, Jo Abbott of Abbott Studio is asking whether we have a small office free from January, around six desks. Could you reply to her?
Helen

CAN WAIT: 2
W1. Nina Cho <nina@chofloorplans.example>, Friday 6 November 10:30. Subject: Coffee? Ask: a coffee in the next couple of weeks to talk about the Riverside fit-outs. Reply by: Thursday 12 November (can-wait period).
Draft W1, to nina@chofloorplans.example, re: Coffee?:
Hi Nina,
[Yes, I'd like that, and happy to talk about the Riverside fit-outs. Would (two times from Helen's calendar) suit? / Not for now: (reason).]
Helen
Gaps: [Yes, I'd like that ... Would (two times from Helen's calendar) suit? / Not for now: (reason).]: Helen's decision; if yes, two times from her calendar.

W2. Ines Moreau <ines@pmassociation.example>, Monday 9 November 07:40. Subject: Speaking at our February forum. Ask: whether Helen will join a panel on tenant retention at the forum on 18 February. Reply by: Friday 20 November (asked by sender).
Draft W2, to ines@pmassociation.example, re: Speaking at our February forum:
Hi Ines,
Thank you for asking me. [I'd be glad to join the panel on 18 February. / I can't join this time, but thank you for thinking of me.]
Helen
Gaps: [I'd be glad to join the panel on 18 February. / I can't join this time, but thank you for thinking of me.]: Helen's decision.

ALREADY COVERED: 1
- Tom Weller, "Viewing, Unit 2B Harbour Court": answered by Lena Fry on Friday 6 November 15:02. No draft.

PROMISES: 2
- To Graham Pike: "I'll have the Q3 service charge summary to you by Friday.", made Wednesday 4 November. Due: Friday 6 November. Status: overdue. Item: T3.
- To Lena Fry: "my answer on the January rent review letters, by Wednesday 11 November", made Thursday 5 November. Due: Wednesday 11 November. Status: open. Item: no message in this batch.

PRIVATE, FOR HELEN ONLY: 1
- Mark Marsh, Sunday 8 November 19:10. Not summarised.

NO REPLY NEEDED: 3. 1 receipt; 1 newsletter; 0 notifications; 1 unsolicited sales; 0 other. Nothing has been archived, deleted or moved; each kind can be listed in full on request.

COULD NOT SORT: 1
- Row 13, Sunday 8 November 13:25: no sender, and the message it forwards is not in the row.

QUESTIONS FOR OWEN: 2
1. Row 13 has no sender and only says "See below, thoughts?": who sent it, and can you paste the message it forwards?
2. Mark Marsh's message is filed as Private because it looks like a family matter, from the sender's name and a short note. Is that right?

Draft for Owen Hale. Nothing has been sent, forwarded, archived, deleted, moved or labelled.
```

Owen rang Kestrel Cleaning on the number in Tallow Lane's supplier records, then passed the triage to Helen when she arrived. Owen forwarded the three notes, the one to Marco first. Helen decided on the barrier quote, the coffee and the panel, filled the gaps once Marco had given a repair time, and sent each reply from her own mailbox.
