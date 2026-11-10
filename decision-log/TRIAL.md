# Decision log: trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID `claude-opus-5-5`)
- **Date:** 2026-11-10

The inputs are the invented Quellmoor Cabinets example in `public/example.md`. No client data was used. The run was started by the same session that had just applied the independent review's points to the template and the example, and that session had read the example's output. The run itself was a separate session that saw only the instruction block, the output format and the inputs.

## How it was run

A fresh, non-interactive session with no tools, no project settings, no slash commands and no files open, started in an empty folder. Its system prompt was the template's fenced instruction block followed by the output format, exactly as the template says to paste them as custom instructions. Its one message was the example's six inputs, verbatim: the settings (which name the company or team, "Quellmoor Cabinets leadership team"), the decisions export, the actions export, the leadership meeting record, Daniel's email and the status updates. Nothing else from the template or the example was given. The block was supplied as a system prompt, not typed into a product's custom-instructions box, so this trial does not test that box.

Two earlier runs the same day were on earlier versions. The first left several points open (the company name in the settings, the order of the gaps, where an action with no decision goes, dates with no year, a new reason for a rejected option, an earlier review date, how far a duplicate action reaches), which the next version settled. The run on that version put a location on the "Held back" line and "See F1" on an action whose flag was on its decision; after the independent review, this version says the "Held back" line gives the kind of item only, not where it was, that "See F(n)" goes on an action only when the flag is on that action, and, in the instruction block, that a duplicate action is one under a different owner or date and that the assistant never supplies an owner or a date. This record is of the run on this version only.

## What came out

The output is as the model returned it. It did not wrap its lines to the output format's width, and it added Markdown headings, bold type and bulleted choices that the format does not use; both are left as returned.

```
# DECISION LOG UPDATE: Quellmoor Cabinets leadership team

Prepared Tuesday 10 November 2026 for Noor (chief of staff). Register as supplied: 5 decisions (5 active, 0 superseded, 0 withdrawn) and 8 actions (6 open). New material: email from Daniel (CEO), Friday 6 November 2026; leadership meeting record (Noor's notes), Monday 9 November 2026. Status updates: 2.

To settle before anything is entered: 4

1. **D-006, F1 (REVIVES A REJECTED PROPOSAL).** The fuel surcharge was turned down in D-001 on 14 September 2026 because dealers dislike surcharges. Which choice applies?
   - (1) Daniel confirms reopening it.
   - (2) It goes back to Daniel.
   - (3) It is not entered.
2. **D-006, A-009 (DATE NEEDED).** By what date should Grace tell the dealers about the fuel surcharge? The source gives no date.
3. **D-007, F2 (CONTRADICTS AN EARLIER DECISION).** D-002 keeps dealer payment terms at 30 days. Which choice applies?
   - (1) D-007 supersedes D-002.
   - (2) Both stand, with the scope of each written by Daniel.
   - (3) It goes back to Daniel.
4. **D-007, A-011, F3 (DUPLICATE ACTION).** Ines's letter covers the same price list letter as open action A-001 (Grace, due 30 November). Which choice applies?
   - (1) Keep A-011 and cancel A-001, replaced by A-011.
   - (2) Keep A-001, and Daniel removes A-011.
   - (3) It goes back to Daniel.

## Proposed new entries: 3

**D-006. Fuel surcharge.** Approved by Daniel (CEO) on Friday 6 November 2026.
  Decision: From 1 December 2026, add a 2% fuel surcharge to deliveries more than 100 miles from the plant.
  Why: Diesel has gone up again.
  Rejected: none recorded.
  Review: not set.
  Related: D-001 (List prices, 14 September 2026) turned down a fuel surcharge. See F1. Held: F1.
  Source: Email from Daniel (CEO) to Noor, Friday 6 November 2026.
  Actions:
    A-009. Tell the dealers about the 2% fuel surcharge on deliveries more than 100 miles from the plant from 1 December. Owner: Grace. Due: DATE NEEDED ("no date in the source").

**D-007. Dealer payment terms.** Approved by Daniel (CEO) on Monday 9 November 2026.
  Decision: Dealers buying more than $250,000 a year move to 45-day payment terms from 1 December 2026. All other dealers stay on 30 days.
  Why: Dealer A (about 18% of sales) asked again for 60 days and says a competitor offers 45.
  Rejected: 60 days for Dealer A alone. Reason given: the other dealers would hear of it.
  Review: not set.
  Related: D-002 (Dealer payment terms, 28 September 2026, review Wednesday 31 March 2027) keeps all dealers on 30 days. See F2. Held: F2.
  Source: Leadership meeting record (Noor's notes), Monday 9 November 2026, item 1.
  Actions:
    A-010. Change the dealer payment terms in the ERP so that dealers buying more than $250,000 a year are on 45 days. Owner: Ines. Due: Friday 27 November 2026.
    A-011. Send dealers one letter containing the 2027 price list and the new payment terms. Owner: Ines. Due: Friday 20 November 2026. See F3.

**D-008. Second finishing shift.** Approved by Daniel (CEO) on Monday 9 November 2026.
  Decision: Keep the second finishing shift until 15 January 2027, then review.
  Why: Backlog is down to 5 weeks, still above the 4-week target.
  Rejected: none recorded.
  Review: Friday 15 January 2027.
  Related: Extends D-003 (Second finishing shift, approved 12 October 2026). D-003's review of Monday 14 December 2026 stays as recorded. D-008's review is Friday 15 January 2027.
  Source: Leadership meeting record (Noor's notes), Monday 9 November 2026, item 2.
  Actions:
    A-012. Confirm with the shift team that the second shift continues until 15 January. Owner: Ravi. Due: Friday 13 November 2026 ("by Friday").

## Flags: 3

**F1. REVIVES A REJECTED PROPOSAL**
  New: D-006. "From 1 December 2026, add a 2% fuel surcharge to deliveries more than 100 miles from the plant."
  Earlier: D-001, approved by Daniel (CEO) on Monday 14 September 2026. It rejected "Add a fuel surcharge instead". Reason given: dealers dislike surcharges. The new reason (diesel up again) does not remove the flag.
  Choices:
  - (1) Daniel confirms reopening, and the entry reads: "Reopens the option turned down in D-001 on 14 September 2026, confirmed by Daniel."
  - (2) It goes back to the approver.
  - (3) It is not entered.

  Held until Noor settles it with Daniel.

**F2. CONTRADICTS AN EARLIER DECISION**
  New: D-007. "Dealers buying more than $250,000 a year move to 45-day payment terms from 1 December 2026. All other dealers stay on 30 days."
  Earlier: D-002, approved by Daniel (CEO) on Monday 28 September 2026. "Keep dealer payment terms at 30 days." Review Wednesday 31 March 2027.
  Choices:
  - (1) D-007 supersedes D-002. D-002 stays in the register, marked Superseded by D-007.
  - (2) Both stand, with the scope of each written by Daniel.
  - (3) It goes back to the approver.

  Held until Noor settles it with Daniel.

**F3. DUPLICATE ACTION**
  New: A-011. "Send dealers one letter containing the 2027 price list and the new payment terms." Owner: Ines. Due Friday 20 November 2026.
  Earlier: A-001 (D-001), Open. "Send the 2027 price list to dealers." Owner: Grace. Due Monday 30 November 2026. Both actions would produce the same letter carrying the 2027 price list to dealers.
  Choices:
  - (1) Keep the new one and cancel A-001, replaced by A-011.
  - (2) Keep A-001, and Daniel removes A-011.
  - (3) It goes back to the approver.

  Held until Noor settles it with Daniel.

## Not entered: discussed, not approved: 2

- **Gloss-finish doors.** Ravi floated sending the gloss-finish doors to an outside finisher in January to free the line. The meeting talked it through. Daniel wants costs first. Not decided. Recorded action: Ravi to get two quotes.
  Source: Leadership meeting record (Noor's notes), Monday 9 November 2026, item 3.
  Needs approval from: Daniel (CEO). Ines (CFO) could approve it only if it is a spending decision up to $25,000.
  If approved, it would revive the option D-003 turned down on 12 October 2026: "Outsource finishing to a third party". Reason given: quality and lead-time risk.
- **Eastgate showroom.** Grace suggested keeping Eastgate open on Saturdays only until the lease ends. Discussion only.
  Source: Leadership meeting record (Noor's notes), Monday 9 November 2026, item 4.
  Needs approval from: Daniel (CEO).
  It touches D-004 (close Eastgate when the lease ends on 31 March 2027). It keeps that closing date, so as worded it would not contradict D-004.

## Held back
One item about one person's pay.

## Action status changes: 1

- A-005. Fit extra extraction filters for the second shift. Owner: Pieter. Open to Done, completed 3 November 2026. Source: Pieter, message, Thursday 5 November 2026 ("Extra extraction filters fitted on 3 Nov, second shift is using them.").

## Overdue: 2

- A-005. Fit extra extraction filters for the second shift. Owner: Pieter. Due Friday 30 October 2026, 11 days overdue. Update: Pieter reported the filters fitted on 3 November (message, 5 November 2026). The change to Done is proposed above.
- A-006. Confirm the lease end date and notice period with the Eastgate landlord. Owner: Ines. Due Friday 6 November 2026, 4 days overdue. Update: Ines, at the leadership meeting on 9 November 2026, said the date is still not confirmed and she is waiting on the landlord's reply. The action stays Open.

## Due in the next 7 days (Tuesday 10 November 2026 to Tuesday 17 November 2026): 1

- A-012. Confirm with the shift team that the second shift continues until 15 January. Owner: Ravi. Due Friday 13 November 2026. (proposed)

## Reviews due in the next 7 days: None

## Register changes, once approved

- Add D-006 and A-009. Waits on gap 1 (F1) and gap 2 (A-009 date).
- Add D-007 and A-010. Waits on gap 3 (F2).
- If F2 is settled with choice (1), mark D-002 Superseded by D-007, and D-007 supersedes D-002. Waits on gap 3.
- Add A-011. Waits on gap 3 (F2, because it belongs to D-007) and gap 4 (F3).
- If F3 is settled with choice (1), change A-001 from Open to Cancelled, replaced by A-011. Waits on gap 4.
- Add D-008 and A-012. Waits on no gap, only Noor's approval.
- Change A-005 from Open to Done, completed 3 November 2026, as reported by Pieter. Waits on no gap, only Noor's approval.

Draft for Noor (chief of staff). Nothing has been entered in the register and nothing has been sent.
```

## What was observed

**Every required part was produced.** The model reached the output format's last line. It stopped for nothing: the headers matched, no id repeated, and today's date was in the settings. The stop conditions were therefore not reached. The held-back path was: item 5 of the meeting record, a pay review, appears only in the "Held back" part.

**The points settled in this version were followed:**

- **Held back, the kind only.** The line reads "One item about one person's pay." It gives no meeting, date or item number.
- **"See F(n)" only on a flagged action.** A-009 carries no flag mark; A-011 carries "See F3", the flag on that action.
- **How a related entry relates.** D-006's Related line says D-001 turned down a fuel surcharge; D-007's says D-002 keeps all dealers on 30 days; D-008's says it extends D-003 and gives both review dates.
- **Duplicate action.** F3 is raised for A-011 against A-001, with different owners and dates, and says both would produce the same letter carrying the price list. A-009 (tell the dealers about the surcharge) is not flagged against A-011.
- **No owner or date supplied.** A-009 has DATE NEEDED; every other owner and date comes from the sources.

**The points settled in the earlier version were followed again:** the company name in the header; the gaps in entry order (F1 on D-006, the missing date on A-009, F2 on D-007, F3 on A-011); "Ravi to get two quotes" written into the outside-finisher item as "Recorded action", with the "Not entered" count at 2; the years on dates given without one; F1 raised in spite of the new reason, with a note that the new reason does not remove the flag; D-003's review date kept beside D-008's; and A-005 shown both under "Overdue" and under "Action status changes".

**Where the model went beyond or around the format:**

- **Markdown and line width.** Section headings carry "#" or "##", entry and flag headings are bold, the choices under each flag and under "To settle" are bulleted lines, and "Held until" sits in its own paragraph. The lines are unwrapped. The format is plain text.
- **"Held back" as a heading.** The format's one line, "Held back: [...]", became a heading with the sentence beneath it, and the sentence does not say it is for the register keeper only.
- **"See F1" and "See F2" in the Related lines.** The model put a flag mark in the Related line of D-006 and D-007, beside the "Held: F(n)" the format asks for, so each flag is named twice there.
- **"no date in the source" in quotation marks.** The format offers either the source's words in quotation marks or "no date in the source"; the model put the second in quotation marks too.
- **An extra approver note.** For the outside-finisher item, "Not entered" adds that Ines could approve it only if it is a spending decision up to $25,000, which is what the settings say.
- **Register changes** come in a different order from the entries, the section's heading has no colon, and each condition is spelled out ("If F2 is settled with choice (1)"). Every addition and status change is there.

**Differences from the published example** (compared after the run):

- The decisions, the numbering (D-006 to D-008, A-009 to A-012), the three flags and their choices, the owners and dates, the order and count of the gaps (4), the two "Not entered" items, the overdue days (11 and 4), the one action coming due, the empty review list, the status change and the held-back line's content agree with the example.
- The example is plain text; the run uses Markdown, as noted above.
- Wording differs in places: the run's A-010 adds "so that dealers buying more than $250,000 a year are on 45 days", its A-009 and A-012 repeat what the dealers and the shift team are told, its D-007 Related line adds D-002's review date, and its questions under "To settle" give the three choices as bulleted lines.
- The example's F2 notes that D-002 also turned down 60-day terms for all dealers and that D-007 does not bring that back; the run does not mention it. The run's note that Ines could approve the outside finisher within her limit is not in the example.
- The example's page ends with a paragraph about what Noor did next. That is not part of the output and the model did not produce it.

**Facts in the output that are not stated in the inputs.**

- The years on "1 December", "15 January", "27 Nov" and "20 Nov" come from the template's rule, not from the sources.
- "The 2027 price list" in A-011 comes from the register's A-001 and D-001; the meeting record says only "price list".
- The weekdays were computed, not given. They are correct: 14 and 28 September 2026 are Mondays, 30 October, 6 November, 13, 20 and 27 November 2026 and 15 January 2027 Fridays, 30 November and 14 December 2026 Mondays, 17 November 2026 a Tuesday, 31 March 2027 a Wednesday. The overdue counts, 11 and 4 days, are today minus the due dates.
- No other fact was added.

**Not tried.** The eleven acceptance tests in the template were not run, so the approver flag, the header stop, the missing-date stop and the requests to enter, delete or send were not exercised. This trial covered one set of inputs, once.
