# Trial: Reviewer comments into one resolution list

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-10

This trial used only the invented example that ships with the template. The charity, the funder, the people, the report and every figure are made up, and no client data was used.

The template was tried three times on 10 November 2026, each time on that one invented example. The first run was done by a different model (Claude Sonnet 5.5) that did not write the template and had not read the example's output. It reached the same thirteen items, types, clashes and statuses as the example, and raised nine presentation and placement questions the template did not answer; they are summarised under "The first run" below. The template's procedure, instruction block and output format were then revised to answer them, and the example gained one line (the position of the insertion R1-04). The second run, on the revised template, is summarised under "The second run".

An independent review then asked for small amendments, and the template was amended: the base question gained a wording for when no base is supplied; the reviewer line and the instruction block now say "sender not stated" or "role not stated" where an input gives none; the instruction block now says to recommend nothing unless the owner asks; the rule to keep every reviewer's words now names its one exception, a comment about a person's performance, pay or conduct; and the procedure and instruction block now give a test for "a commitment to a client or funder" and the order of lines under "Watch items". This record is of the third run, on the amended template.

The second and third runs were done by the model that made the revisions and the amendments, after it had read the example's output and the earlier records. They are therefore checks that the rules can be followed and agree with the example, not blind trials.

## Inputs used

The five inputs in [public/example.md](example.md), under "The inputs": the settings, the base version of the funder report, the exports of Kofi's and Margit's marked-up copies, and Theo's email. The amended instruction block and output format in the template (member/template.md) were followed step by step. Where the template leaves wording open (the "To settle first" lines, the clash lines, the reasons for clashes, the description of the chart change), the wording below is this run's own.

## What came out

The list below is the full output from this run.

```
RESOLUTION LIST: Funder report: July to September 2026, version 3

For: Ines, communications lead. Prepared 15 October 2026 from 3 reviewer inputs. Deadline: 23 October 2026, report due to Funder B.
Reviewers:
R1 Kofi, programme director: export of a marked-up copy, dated 12 October 2026. 6 items.
R2 Margit, finance manager: export of a marked-up copy, dated 13 October 2026. 4 items.
R3 Theo, board chair: email, dated 14 October 2026. 3 items.
Items: 13 (4 replacements, 1 insertion, 1 deletion, 0 moves, 0 formatting, 3 comments, 3 notes, 1 check by hand). Clashes: 2. Watch items: 7. Open: 13. Decided by the owner: 0.

To settle first: 4
1. Clash C1 (R1-01, R2-01): Kofi and Margit put different household figures for the Saturday distribution into the summary.
2. Clash C2 (R1-05, R2-04): Kofi deletes the schools pilot and Margit asks for it to stay.
3. Not placed (R1-06): the comment is anchored to "Table 1", which is not in version 3.
4. Check by hand (R1-03): a change in 2. Meals and families served that the export gives only as "[chart]".

Clashes: 2
C1. 1. Summary: "around 300 households a week"
  R1-01 Kofi: replace with "about 320 households a week"
  R2-01 Margit: replace with "around 280 households a week"; reviewer's comment "Register average Jul-Sep is 281."
  Why they cannot both be done: the same words cannot carry both figures. Status: Open.
C2. 5. Next quarter: "and begin a pilot with two schools"
  R1-05 Kofi: remove "and begin a pilot with two schools"; reviewer's comment "Schools pilot is not confirmed yet."
  R2-04 Margit: comment "Keep this in. The funder asked about schools last quarter."
  Why they cannot both be done: Margit asks to keep the words Kofi deletes. Status: Open.

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
  Check by hand: the export row gives "[chart]" as both the old and the new content, so the change cannot be read
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
R1-03: a change in section 2, Meals and families served, that Kofi's export gives only as "[chart]"; his marked-up copy will show it.

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

## What was observed

- **Every required part was produced,** in the order of the output format: the header, the reviewer lines, the counts, "To settle first", the clashes, the checklist by section, "Not placed", "Check by hand", "Watch items", "Agreements", the accepted-edits line and the closing line. No stop form applied: there was one base, both exports had the default headers, and every input was readable.
- **The counts agreed.** 13 items; the type counts (4, 1, 1, 0, 0, 3, 3, 1) add up to 13. Every item appears once, in a section or under "Not placed". All 13 are Open.
- **Words were copied exactly.** Every proposed word and comment is as the reviewers wrote it, including Margit's "Jul-Sep" and "10 Oct" inside quotes, which the date rule leaves alone. No two reviewers' items were merged, and no comment was about a person's performance, pay or conduct, so nothing was held back.
- **Nothing was invented.** Every quotation traces to the inputs, and the run added no figure, date or name of its own.
- **The placement and order rules decided the points the first run had to guess.** Theo's first two notes ask something of a whole section (open with a point, add a line) and were placed "section only"; his third asks for a change to one sentence and was placed "near". In section 4, R2-03 and R3-03 begin at the same words, so reviewer order put R2-03 first. Kofi's insertion was recorded with "Position: not stated". The one chart row and the "Table 1" row were handled by the rules for placeholders and unplaced anchors; Kofi had only one unplaced anchor, so the earlier-version question was correctly not raised.
- **The amendments that this example exercises gave the same result as the example.** By the new test, removing the schools pilot (R1-05) takes a promise of work for the funder's programme out of a report that goes to the funder, so it carries "Owner to confirm who signs this off."; Margit's spending corrections (R2-02, R2-03) only correct figures, and Theo's repair date (R3-03) only corrects a date about the charity's own arrangements, so they do not. The watch items are listed in reviewer order, then by item number, as the template now says.
- **The other amendments were not exercised.** Every input named its sender and role, a base was supplied, the run was not asked which reviewer is right, and no comment had to be held back, so the no-base wording, "sender not stated", "recommend nothing" and the held-back exception were not tried.

### Differences from the published example

The two lists agree on every item, type, placement, order, clash, count, watch label, sign-off line, status and line of the format. They differ only where the template leaves the wording open:

1. The four "To settle first" lines and the two "Why they cannot both be done" lines are worded differently.
2. The description of R1-03 ("Check by hand" in its checklist entry, and its line under "Check by hand") is worded differently.
3. The item lines under the clashes are worded slightly differently: this run joins the reviewer's comment with "; reviewer's comment" where the example writes ", with the comment", and in C2 it quotes the words Kofi removes where the example says "remove the words".

### Facts in either output that are not in the inputs

None in this run's output. The example's output adds nothing that is not in the inputs; its closing paragraph restates what the owner does next.

### Where the template still leaves a judgement

- Whether an insertion that adds a new figure (R1-04) "changes" a figure on the watch list. This run, like the example and the second run, marked it.
- The commitment test is still a reading of words: here it gave a clear answer for each item, but another document could hold a sentence where "a promise of work, a service or a result" and "the organisation's own arrangements" are hard to tell apart.

### The first run

The first run, by Claude Sonnet 5.5, produced the same thirteen items, the same types, both clashes, the same four "To settle first" entries, the same unplaced and check-by-hand items, and every status Open. Its record noted these differences from the example, each of which led to a change in the template:

1. It placed Theo's first two notes "near", quoting the sentence each points to, where the example placed them "section only". The template now says an item that asks something of a whole section is "section only".
2. It listed R3-01 first in section 1, because its sentence begins before the other items' words. The template now orders exact and near items by where their quoted words begin, then section-only items.
3. It marked R1-06, an unplaced comment that changes nothing, as a watch item, giving 8 where the example has 7. The template already said such a comment is not a watch item; the run's own record judged it had over-marked.
4. It wrote watch kinds in the watch list's words ("figures and amounts"). The template now gives the singular labels and splits figures from amounts of money.
5. It wrote the exports' dates as 2026-10-12. The template now sets one date form outside quoted words.
6. It wrote the document's name in capitals, as the base's title is. The template now says sentence case, without the version label.
7. It quoted the shared words "begin a pilot with two schools" as C2's base words. The template now uses the first item's base words.
8. It followed the counts line literally ("1 insertions, 1 deletions"). The template now says a count of 1 takes the singular.
9. Its free-text lines were worded differently; the template still leaves those open.

It also asked where "Prepared [date]" comes from, whether a line break counts in a word-for-word match, and where an inserted sentence goes. The settings now include today's date, a line break counts as a space, and an insertion records its position or "Position: not stated".

### The second run

The second run, on the template as revised after the first run and before the review's amendments, was done by Claude Opus 5.5. It produced the same thirteen items, types, placements, order, clashes, counts, watch labels and statuses as the example and as this run, and differed from the example only in free wording. It recorded three points the template then left to judgement: whether removing the schools pilot changes "a commitment to a funder" (it judged that it does, and that the spending corrections and the repair date do not), whether R1-04 changes a figure, and the order of lines under "Watch items" (it used item order). The amended template now settles the first and the third.

### Shortcomings

Three runs on one invented example, the second and third by the model that revised and amended the template and had seen the example's output. No run tried any of the template's thirteen acceptance tests, a later run with the owner's decisions, or any stop form, including the new no-base wording of the base question. Nothing here shows how the template behaves on a real document, on a real tracked-changes file or in another product.
