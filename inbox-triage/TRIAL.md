# Inbox triage: a trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID `claude-sonnet-5-5`)
- **Date:** 2026-11-09

The inputs for this run are the invented example's own: the settings, routing list, promises, two sample replies and the export of 17 messages in `public/example.md`, section "The inputs". No client data was used. The run followed the fenced instruction block and the output format in the capability template, and the example's published output was read only afterwards. The run was done by a model that had not written the template.

## What came out

```
INBOX TRIAGE: Helen Marsh, Monday 9 November 2026, as of 08:30

Prepared for: Owen Hale and Helen Marsh. Source: inbox-export-2026-11-09.csv, 17 rows, Wednesday 4 November to Monday 9 November 2026. Threads: 14.
Settings: day ends 17:30; can-wait replies within 3 working days; routing list supplied; colleague replies checked; voice from 2 samples; promises list supplied.

Headline: 14 threads. Held for Helen: 1. Reply today: 3. For someone else: 2. Can wait: 2. Already covered: 1. Private: 1. No reply needed: 3. Could not sort: 1.

HELD FOR HELEN, NO DRAFT: 1
H1. Kestrel Cleaning Accounts <accounts@kestre1cleaning.example>, Sunday 8 November 21:03. Subject: URGENT: new bank details. Asks: "Please pay invoice KC-2291 ($3,180.00) to the new account below today to avoid a late fee." and "Please don't call our office, the lines are down." Hold: new bank details and pressure to pay today. Address check: this message comes from kestre1cleaning.example (the digit 1); the invoice on Friday 6 November came from kestrelcleaning.example (the letter l). Next step: before any money moves, Helen or Ruth rings Kestrel Cleaning on the number in Tallow Lane's own supplier records and asks whether its bank details have changed; the message's request not to call is a reason to call, not to skip it. Linked to: E1.

REPLY TODAY: 3
T1. Marco Diaz <marco@tallowlane.example>, Monday 9 November 08:05. Subject: Car park barrier quote, Harbour Court: need your OK. Ask: Helen's approval of the quote to replace the Harbour Court car park barrier. Amounts and dates: $7,400; start Wednesday if confirmed by end of today; quote attached. Waiting since: Monday 9 November 08:05; 1 message. Earlier promise: none found. If it waits until tomorrow: the Wednesday start is lost.
Draft T1, to marco@tallowlane.example, re: Car park barrier quote, Harbour Court: need your OK:
Hi Marco,
[Yes, go ahead / Not yet: reason]. Keep me posted on the date.
Helen
Gaps: [Yes, go ahead / Not yet: reason]: Helen's decision.

T2. Asha Rao <asha@raodesign.example>, Saturday 7 November 09:15. Subject: Re: Entry buzzer, suite 4. Ask: when the suite 4 entry buzzer at Harbour Court will be fixed. Amounts and dates: stopped working Thursday afternoon; clients visiting from Monday (today). Waiting since: Thursday 5 November 17:05; 2 messages. Earlier promise: none found. If it waits until tomorrow: a second day of her clients arriving to a dead buzzer, with both her messages unanswered.
Draft T2, to asha@raodesign.example, re: Entry buzzer, suite 4:
Hi Asha,
Sorry you've had to write twice. Marco Diaz, our maintenance manager, is dealing with the buzzer. [When Marco expects it to be fixed: only once he has said.]
Helen
Gaps: [When Marco expects it to be fixed: only once he has said.]
Forward to: Marco Diaz. Forwarding note, for a person to forward with the original attached:
Marco, Asha Rao (asha@raodesign.example) of Rao Design reported on Thursday 5 November at 17:05 that the suite 4 entry buzzer at Harbour Court stopped working, and wrote again on Saturday 7 November. She has clients visiting from today. Please deal with it and tell Helen when it will be fixed so she can tell Asha. Helen has not promised Asha a time.

T3. Graham Pike <graham@northgate-holdings.example>, Friday 6 November 16:42. Subject: Re: Q3 service charge summary. Ask: news on the Q3 service charge summary. Amounts and dates: needed before his board call on Wednesday 11th (11 November). Waiting since: Friday 6 November 16:42; 1 message. Earlier promise: "I'll have the Q3 service charge summary to you by Friday.", Wednesday 4 November. If it waits until tomorrow: the summary promised for Friday is a further day late, one day before Graham's board call.
Draft T3, to graham@northgate-holdings.example, re: Q3 service charge summary:
Hi Graham,
Sorry, the Q3 summary is later than I said. [When Graham will have it: he needs it before the board call on Wednesday 11 November.]
Helen
Gaps: [When Graham will have it]: not in the messages or inputs; Helen to say.

FOR SOMEONE ELSE: 2
E1. Kestrel Cleaning Accounts <accounts@kestrelcleaning.example>, Friday 6 November 11:20. Subject: Invoice KC-2291, October cleaning. What it is: a supplier invoice, $3,180.00, due 20 November 2026, payable by bank transfer to the account on file. Goes to: Ruth Bell, bookkeeper. Acknowledgement from Helen: not needed: handler replies.
Forwarding note E1, to Ruth Bell, for a person to forward with the original attached:
Ruth, invoice KC-2291 from Kestrel Cleaning for October cleaning at Harbour Court: $3,180.00, due 20 November 2026, by bank transfer to the account on file. A later message from a different address (accounts@kestre1cleaning.example) asks for this invoice to be paid to new bank details; it is held (H1). Please do not pay to any new details until a person has rung Kestrel on the number we already hold.

E2. Jo Abbott <jo@abbottstudio.example>, Sunday 8 November 08:12. Subject: Small office from January? What it is: a new tenancy enquiry for a small office, around six desks, from January. Goes to: Lena Fry, leasing manager. Acknowledgement from Helen: not needed: handler replies.
Forwarding note E2, to Lena Fry, for a person to forward with the original attached:
Lena, Jo Abbott of Abbott Studio asks whether we have a small office free from January, around six desks. Please reply to her.

CAN WAIT: 2
W1. Nina Cho <nina@chofloorplans.example>, Friday 6 November 10:30. Subject: Coffee? Ask: a coffee in the next couple of weeks to talk about the Riverside fit-outs. Reply by: Thursday 12 November (can-wait period).
Draft W1, to nina@chofloorplans.example, re: Coffee?:
Hi Nina,
Thanks for this. [Yes: two days and times that suit Helen / Not for now: reason].
Helen
Gaps: [Yes: two days and times / Not for now: reason]: Helen's decision.

W2. Ines Moreau <ines@pmassociation.example>, Monday 9 November 07:40. Subject: Speaking at our February forum. Ask: whether Helen will join a panel on tenant retention at the forum on 18 February. Reply by: Friday 20 November (asked by sender).
Draft W2, to ines@pmassociation.example, re: Speaking at our February forum:
Hi Ines,
Thanks for asking me. [Yes, I'll join the panel on 18 February / Not this time: reason].
Helen
Gaps: [Yes, I'll join / Not this time: reason]: Helen's decision.

ALREADY COVERED: 1
- Tom Weller, "Viewing, Unit 2B Harbour Court": answered by Lena Fry on Friday 6 November 15:02. No draft.

PROMISES: 2
- To Graham Pike: "I'll have the Q3 service charge summary to you by Friday.", made Wednesday 4 November. Due: Friday 6 November. Status: overdue. Item: T3.
- To Lena Fry: "my answer on the January rent review letters, by Wednesday 11 November", made Thursday 5 November. Due: Wednesday 11 November. Status: open. Item: no message in this batch.

PRIVATE, FOR HELEN ONLY: 1
- Mark Marsh, Sunday 8 November 19:10. Not summarised.

NO REPLY NEEDED: 3. 1 receipt · 1 newsletter · 0 notifications · 1 unsolicited sales · 0 other. Nothing has been archived, deleted or moved; ask to see any group.

COULD NOT SORT: 1
- Row 13, Sunday 8 November 13:25: no sender; the body says only "See below, thoughts?" and holds no forwarded message.

QUESTIONS FOR OWEN: 2
1. Row 13 has no sender and no forwarded text: who sent it, and can you paste what it forwards?
2. Mark Marsh's message was filed as Private because it looks like a family matter. Is that right?

Draft for Owen Hale. Nothing has been sent, forwarded, archived, deleted, moved or labelled.
```

## What was observed

Every group and part in the output format was produced, and the counts add up: 1 + 3 + 2 + 2 + 1 + 1 + 3 + 1 = 14 threads from 17 rows. Nothing in the inputs made the instructions stop, and no header mismatch, missing date or missing routing item arose. No message in the export is written to direct an AI assistant, so that rule was not exercised.

What the comparison found in the example as first published. Set against this run, the example's output went beyond its inputs or the template's own draft rules in four places, and differed in order and questions in two more:

- The Q3 summary draft said "Here's the Q3 service charge summary" and asked for it to be attached, which assumes a finished summary that no input mentions. The run left the date the summary will arrive as a gap.
- The coffee draft said "Yes, I'd like that". Whether to accept an invitation is Helen's choice, so the run left it in square brackets, as the template asks for decisions.
- The buzzer draft said Marco "has this now", which no input shows, and promised a call "by (time) today"; its note asked Marco to call her. The run said only that Marco is dealing with it and left the repair time as a gap.
- The invoice forwarding note added "for your usual approval and payment run", a process not in the inputs. The run did not.
- The example put the buzzer first in Reply today and the barrier quote second; the run put the barrier quote first because its deadline is today. The template then said only "the item that costs most if it waits", so both could be defended.
- The example filed Mark Marsh's message as private without asking; the run filed it as private and asked.

The example was corrected after this run on all six points, and the template was clarified (see the end of this record). The comparison below is with the corrected example.

Differences from the corrected example:

- The order of Reply today now matches: barrier quote first, buzzer second. The corrected example's cost line for the buzzer also says why it comes second; the run's does not.
- The Q3 summary, coffee and buzzer drafts now leave the same things as gaps or decisions as the run did. The wording differs: for example, the example's Q3 draft opens with when the summary will come and apologises second, and its buzzer note says Helen has not promised a time in Helen's own voice.
- The invoice forwarding note matches in substance. The example's notes are signed "Helen"; the run's are not.
- The panel and barrier drafts. The run's wording differs slightly (a different bracket text, and in the barrier draft the line "Keep me posted on the date." taken from a sample). The substance matches.
- The questions now match: both ask who sent row 13 and whether Mark Marsh's message is private.
- Held item, promises, already covered, no-reply counts, could-not-sort row and the headline counts matched the example before and after the correction.

Facts not in the inputs:

- In the run's output, none found. Every name, amount and date traces to the inputs.
- In the example's output as first published: the finished Q3 summary being ready to attach; "approval and payment run" as Ruth's process; Marco having "this now". In the corrected example, none found.

Where the template was ambiguous, or the run had to guess:

- Threads and a linked message. The grouping rule needs matching subjects, so the invoice and the later bank-details message are two threads. The template does not say how to link them beyond a forwarding note. The run linked them by hand.
- A message from a colleague. Marco's quote request came from inside the business. Steps 6 and 8 talk about an "outside" sender and a colleague handler. The run treated it as Reply today because of the $7,400 and the deadline, with no forwarding note, but the template does not say so.
- The Reply today order. "Costs most if it waits" has no tie-break between a hard deadline today and a person already waiting two days.
- Private mail from an unfamiliar address. The private rule names "personal and family matters" but gives no way to tell one from the sender's name and a short message. The run guessed and asked.
- A task that falls inside two rules. Marco's quote could also count as "repairs and maintenance", which the routing list gives to Marco himself.
- Draft opening. The rule "open with the answer, or say honestly when it will come" does not say what to do when the answer is a decision for the owner. The run opened with the bracket.
- A sample sign-off. Copying "Keep me posted on the date" from a sample can read as an undertaking the owner has not made for this message. The run used it only in the draft to Marco, where the sample was written for the same kind of reply.
- The instruction block's rule for the questions group says "one question each" but does not say whether a guess the run made should be listed there.

The run made no changes to any mailbox, since none was connected. The reviewer checklist was then applied to the run's output: the counts add up; the held item names a check by a person and repeats no bank details; every draft figure traces to the inputs; Reply today items state a cost; every item for someone else names a handler; both promises are listed; nothing private is summarised. Item 8, the owner's approval, is for the people who would use the drafts.

## Changed after this run

- The example's output was corrected on the six points listed above. Its inputs are unchanged except that two invented senders in the no-reply rows were renamed (a software receipt and a sales message); this run used the earlier names, which appear nowhere in its output.
- The template's procedure and instruction block were clarified on five points: when two Reply today items would cost about as much, a deadline that ends today comes before a sender already waiting; a colleague asking the owner for approval is the owner's to answer, never "already covered" and never routed back to that colleague; a message that only looks private is listed as private and asked about in the questions; a draft may open with the owner's decision in square brackets; and the batch limit has a stated default of 150 threads. Each clarification states what this run already did. The template was not run again after them.
- 10 November 2026: the example's buzzer item (T2) no longer ends with a sentence on why it comes after T1, because the output format has no place for one; the comparison above, which mentions that sentence, describes the example before this edit. Two passages of the template's instruction block were rewrapped with no change of wording. This run's output is unchanged.

**Changed after this run (11 November 2026):** in the template and the example, the closing words of the "No reply needed" line were reworded and its counts are now separated by semicolons. The output above is as the run produced it.
