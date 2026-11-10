# Staff newsletter and FAQ roundup: trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-10

The inputs are the invented example in `public/example.md` (Brindlecote Packaging, November 2026 issue): its issue settings, 13 team update rows, 6 staff questions, 3 approved sources and last month's issue. No client data was used. This is the record of the second of two runs, both on 10 November 2026.

## The first run, and what changed after it

The first run was made in Claude (Claude Sonnet 5.5) by an assistant that had not written the template. Its first read of the example was cut short by mistake, so a partial run saw only two of the three sources and not last month's issue; it put the boots question under "Answers needed" and left the visitor tablets row out as outside the November window rather than as already in last issue. When the rest of the file was read, that read also showed the example's output, so the full first run was not blind. The full run made the same decisions as the example: the same seven news items, the same five rows left out for the same reasons, the same two items to settle, the same question under "Answers needed" and the same two questions not chosen. It found these places where the template left room to guess or where the example went beyond its own rules:

1. The procedure said each item names its team first, while the output format put the team in brackets at the end of a coming-up item.
2. The people-news line of the output format read "[item, shared with the person's agreement]"; the run printed those words and the example did not.
3. The example added weekdays inside the items' own words ("Friday 4 December", "Monday 16 November") and expanded two date ranges into the heading, against "facts exactly as submitted and nothing added". Every weekday was correct, but none was in the rows.
4. "The shortest passage that answers it in full" did not settle whether a closely linked second sentence belongs; the example quoted two sentences for the carry-over and parking questions, and the run quoted one.
5. The example wrote "its longest run" where the row says "the longest run", and "Sent by: Dana" without the role.
6. The draft's heading had no singular for one item to settle, and "[owner to confirm this is still current]" did not say the owner's name replaces "owner".
7. The template's version note still said it had not been tried.

After that run the template was revised: coming-up items start with the weekday and the date from the row's `date` column and end with the team in brackets, while wins and people news start with the team; dates inside an item's own words stay as submitted, with no weekday added and no range turned into the heading; the consent words were taken out of the people-news line; answers quote only the sentences that answer the question as asked, with "Read the rest" only where the answer runs past the quote limit; "Sent by" carries the role; the heading's count and the old-source note say how they are written; and the instruction block now also says to name unusable sources under "Sources not used", to list set-aside questions under "Questions not chosen", that a question asking for a decision nobody has made is one no source answers, and that the closing line names the approver's role. The example's output was revised to match.

## How this run was made

This run was made by the session that made those revisions, after it had seen both the old and the revised example output. It is therefore not a blind run either. It followed the revised instruction block and output format in `member/template.md` on the example's inputs, written out in full, and was compared with the example's output and the reviewer checklist only afterwards.

## What came out

```
ISSUE CHECK: Brindlecote News, November 2026
For: Martin (managing director). Send date: Monday 30 November 2026. Sent by: Dana (office manager).
Prepared Thursday 26 November 2026 from 13 team update rows, 6 questions and 3 approved sources. Last issue: October 2026, supplied.
News items in the draft: 7 of a limit of 15. Questions answered in the draft: 3 of a limit of 6.

To settle before this goes out: 2
1. Row 13 (Office, from Dana): the type "shoutout" is not win, coming up or people news. Dana, which is it? The row stays out of the draft until then.
2. Question 3, own safety boots: the answer quotes the Site safety rules, approved 10 June 2025, more than 12 months before the send date. Tomas (quality manager), does section 2.1 still hold?

Left out of the draft: 5
- Row 7 (Production, from Ravi): held-out subject; its content is not repeated here. Stays out.
- Row 8 (Sales, from Ines): people news with no consent recorded. Comes in once Ines records that the person agreed.
- Row 9 (Finance, from Grace): reads as a change not yet announced, with no link to an announcement. Comes in once the change has been announced and the link is added.
- Row 10 (Production, from Ravi): held-out subject; its content is not repeated here. Stays out.
- Row 12 (Office, from Dana): already in last issue. Stays out.

Answers needed: 1
- "When will we hear about the new pension provider?" (asked 5 times). No approved source answers it. Owner: Martin (managing director). Not in the draft.

Questions not chosen: 2
- Question 5 (asked 4 times): one person's own case. For HR to answer directly; not repeated here.
- "Is the canteen open on Saturdays?" (asked 2 times): below the threshold of 3.


BRINDLECOTE NEWS: November 2026
DRAFT. NOT READY TO SEND: 2 items to settle (see the issue check).

In this issue: 3 wins, 3 dates coming up, 1 piece of people news and answers to 3 questions you keep asking.

Wins
- Production: Line 3 ran 30 days without an unplanned stop, the longest run since it was installed.
- Sales: signed a two-year supply agreement with Customer K for printed trays.
- Quality: passed the annual food-safety audit with no major findings. More: intranet/quality/audit-2026

Coming up
- Tuesday 8 December: allergen refresher training for all production staff, 8 and 9 December, 30 minutes per shift. (Quality) More: intranet/training
- Friday 11 December: winter party, 5 pm, in the canteen. Partners welcome. Sign up by 4 December. (HR) More: intranet/winter-party
- Thursday 24 December: office closed 24 December to 1 January; production runs to the holiday rota. (Office) More: intranet/holiday-rota

People news
- HR: welcome to Oskar, who joined Finance as accounts assistant on 16 November.

Questions you keep asking
Q. How many days of holiday can I carry over into next year?
A. "You may carry up to five unused days of annual leave into the next holiday year."
Source: Staff handbook, section 4.3. Owner: Leena (HR manager). Approved 2 March 2026.

Q. Where do I park now the north car park is being resurfaced?
A. "While the north car park is closed, staff park in the overflow area behind Unit 4."
Source: Car park works notice. Owner: Dana (office manager). Approved 2 November 2026.

Q. Can I wear my own safety boots on the production floor?
A. "Personal safety footwear is allowed on the production floor if it meets the site standard and has been checked by the shift supervisor." [Tomas to confirm this is still current]
Source: Site safety rules, section 2.1. Owner: Tomas (quality manager). Approved 10 June 2025.

Questions about this issue: Dana (office manager).

Draft for Martin (managing director) to approve. Nothing has been sent.
```

## What was observed

**Every required part was produced.** The issue check with its four lists and the count lines, the draft with all four sections, the opening line, the status heading and the closing line. No stop applied: the settings, both tables' headers and all three sources were complete, and every source had an owner and an approval date, so the "Sources not used" note was left out.

**The decisions matched the example's and the first run's.** The same seven items are in the draft, the same five rows are left out for the same reasons, the same two items are to settle, the same pension question is under "Answers needed" and the same two questions are not chosen. Row 12 (the visitor tablets) is both already in last issue and dated outside the November window; the rule order puts last issue first.

**The output matches the revised example's output** word for word, apart from line wrapping. Both are the work of the same session, so this shows that the revised instructions and the revised example agree, not that a fresh assistant would land in the same place.

**Facts in the output that are not in the inputs.** None. The three weekdays in the coming-up headings come from the rows' `date` column and are correct for 2026 (8 December a Tuesday, 11 December a Friday, 24 December a Thursday). "Joined" for Oskar is the tense change the template allows for a send date after 16 November. The duplicated "Friday 11 December" was dropped from the party item as an edit for length.

**What the template still leaves open, and what this run did:**

- Whether a row waiting under "To settle", such as the "shoutout" row, should also appear under "Left out of the draft". The rules put it under "To settle" only, and this run did that.
- Whether the first word after a team's name keeps the submitted capital. Nothing says; this run used a lower-case letter, as last month's issue does.
- A coming-up item whose row gives the start of a range now repeats a date ("Tuesday 8 December: ... 8 and 9 December"). It is faithful to the row but reads a little heavily; the template accepts that cost to avoid adding dates nobody submitted.
- "Only the sentences that answer the question as asked" is still a judgement. Under it the carry-over answer leaves out the 31 March deadline, which staff may well want; a company that prefers the fuller answer can say so in its settings.
- The first run's record said the example exercised acceptance test 13 (two sources disagree). It does not: the example has no disagreeing sources. The example exercises tests 3 to 10, test 2 in part (its health item has no consent recorded) and the ordinary items of test 1. Tests 11 (header mismatch), 12 (asked to send) and 13, and the linked half of test 5, were not run.
