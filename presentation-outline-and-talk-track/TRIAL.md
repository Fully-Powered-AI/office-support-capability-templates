# Presentation outline and talk track: one trial run on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-10
- **Template version:** 0.1.0

This is a record of one run of the capability template on its own invented example. Pelterwick Facilities, Maren, her board, her sites and every figure are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

This is the second recorded run on the same example. An earlier run the same day, by a different model, showed where the instructions left room to guess and where the trial's own set-up had produced a false result; the template and the example were revised, and the run recorded here was made on the revised versions. What the earlier run found, and what was changed, is at the end.

## How the run was made

Each pass was a fresh session started from Claude Code with no tools and no access to any file. The template's instructions for an AI assistant, followed by its output format, were copied out of the template unchanged and given as the session's instructions; the inputs were sent as one message. The two passes ran in separate sessions. Neither session saw the example's talk track, the template's procedure or the earlier run. The run was set up by the model that revised the template, which had read the example; the sessions that produced the output had not.

Pass one was first run once before the example's notes said where the nine far sites are. That attempt asked, among seven questions, whether the far sites were in the west, since the case for a depot in the west depends on it. The notes were given that fact ("all of them in the west"), and pass one was run again. The output below is from the second attempt; the first is not recorded beyond this paragraph.

## The inputs used

- **Pass one:** "Settings: the defaults.", then Maren's brief and notes exactly as given under "What Maren supplied" in the first pass of [the worked example](example.md). Her notes now say the nine sites more than 50 minutes away are all in the west and are what she calls the far sites. She gave no pace.
- **Pass two:** "Settings: the defaults.", then the same brief and notes, the example's storyboard as Maren approved it, her answer to its questions ("Approved, headlines as drafted. The second prospect told Rafe on the phone; fine to say. I'll get the weekly driving hours from Callum."), and her five slides as text, exactly as given in the second pass of the example. This is the set of inputs the example says Maren supplied, so the slides' headlines match the storyboard the run was given.

## What came out: pass one

The complete output, as returned:

```
STORYBOARD: Our distance problem
For: Maren (managing director, Pelterwick Facilities). Occasion: quarterly board meeting, Thursday 19 November 2026. Prepared Monday 9 November 2026 (your date; my system shows 10 November, which doesn't affect anything here).
Audience: the chair (founder and owner), two non-executive directors and Callum (finance director). They know the business well and have heard you raise travel before, but they have never seen the numbers.
Slot: 3:00, questions after, outside the slot. The chair hands to you and you hand back. Pace: ordinary, 140 words a minute (you weren't sure, so I've used the default).
Scripted target: 378 words (2:42), leaving 0:18 unscripted. Slide limit: 6.
Working: allowance is 10% of 3:00, which is 0:18. That leaves 2:42 (2.7 minutes). 2.7 × 140 = 378 words.

To settle before the storyboard is approved: 5
1. Pace: do you speak slower or faster than most people? I've used ordinary (140 words a minute, target 378 words). Steady (120) would give 324 words. Quick (160) would give 432 words.
2. "Call-out response": what does the average measure? I've read it as the time from the client's call to a crew arriving on site, which is how your notes read most plainly. Is that right?
3. The new site that started in October: is it one of the 9 far sites? The Q3 figures cover July to September, before it started. I need to know whether "9 far sites" matches the sites behind the 22% and the 3h10.
4. "Lost 3 clients last year": is that calendar 2025, or the last twelve months? I've read it as 2025, since your notes say "this year" for the prospects.
5. The prospect who said no in writing: should the slide and talk mention that it was in writing? I've included it on slide 4 without naming the prospect.

The one message: Our nine far sites in the west cost us crew time, slow our call-outs and have already lost us business, so I'm asking for your go-ahead to bring a full costed plan for a second depot in the west to the March board.
What the room should do or think afterwards: give the go-ahead to bring a full costed plan for a second western depot to the March board. This is not a decision on the depot itself.

Supporting points
1. Travel eats far more crew time at the far sites. Backed by: in Q3 2026, travel was 22% of crew hours at the far sites and 8% at the rest.
2. Far-site clients wait much longer for a call-out. Backed by: in Q3 2026, the average call-out response was 3h10 at the far sites and 1h25 at the others.
3. Distance is already costing us clients and new business. Backed by: we lost 3 clients last year. 2 of them were far sites, and both said slow call-outs were the reason. 2 prospects in the west said no this year because of distance, one of them in writing.

Shape: where we stand (one depot, the far sites), what it means (crew time, call-outs, lost business), what I ask (go-ahead for a costed plan in March).

Slides: 5
1. Nine of our 41 sites are more than 50 minutes from our only depot, and all nine are in the west. Carries: Opening. Shows: the one depot on the east side of the city; 41 client sites, with the 9 far sites marked as more than 50 minutes' drive away and all in the west; a line saying the talk ends with a request to plan a western depot.
2. At the far sites, travel took 22% of crew hours in Q3, against 8% everywhere else. Carries: point 1. Shows: Q3 2026 travel as a share of crew hours, 22% at the far sites against 8% at the rest.
3. Far-site clients waited 3h10 on average for a call-out in Q3, against 1h25 everywhere else. Carries: point 2. Shows: Q3 2026 average call-out response, 3h10 at the far sites against 1h25 at the others.
4. Distance has already cost us two clients and two prospects in the west. Carries: point 3. Shows: 3 clients lost last year, 2 of them far sites, both citing slow call-outs; 2 western prospects who said no this year because of distance, one in writing.
5. I'm asking for your go-ahead to bring a full costed plan for a western depot to the March board. Carries: Ask. Shows: what the plan would cover (site, cost, staffing and timing); a line making clear this asks for permission to plan, not a decision on the depot.

The headlines in order: Nine of our 41 sites are more than 50 minutes from our only depot, and all nine are in the west. At the far sites, travel took 22% of crew hours in Q3, against 8% everywhere else. Far-site clients waited 3h10 on average for a call-out in Q3, against 1h25 everywhere else. Distance has already cost us two clients and two prospects in the west. I'm asking for your go-ahead to bring a full costed plan for a western depot to the March board.
(The headlines carry the story as written, so none needed fixing.)

Left out: staff turnover down to 14% this year. It doesn't bear on the distance problem or the ask, and a good-news figure in a three-minute case could blur the message. Tell me if you want it in, and how it connects.

Draft for Maren. Nothing has been sent and no file has been changed.
```

## What came out: pass two

The complete output, as returned:

```
TALK TRACK: Our distance problem
For: Maren. Occasion: quarterly board meeting, Thursday 19 November 2026. Prepared 16 November 2026.
Slot: 3:00. Pace: ordinary, 140 words a minute. Scripted target: 378 words (2:42).

To settle before you rehearse: 5
1. Slide 2: What are the weekly driving hours at the far sites? This is storyboard question 2, still open until Callum sends the number. The script has a [CHECK] where it goes.
2. Slide 4: Your notes say "Don't name them." I've read that as covering the two businesses. Does it also cover Rafe? Until you say, the script says "the other told us so on the phone" and leaves Rafe out.
3. Slide 5: Do you want to mention the industrial unit you viewed last week? Your notes say landlord talks aren't public yet, so I've left it out.
4. Slide 1: Will you change "Client sites: 40" to 41 before Thursday? The script says forty-one, as your notes do.
5. Slide 3: Will you change "Clients lost last year: 3, all far sites" to show only two were far sites? The script follows your notes.

Slide 1: Nine of our sites sit more than 50 minutes from our only depot
Thank you. I'll start with what I'm asking for, so you know where I'm going. I'd like your go-ahead to bring a costed plan for a second depot in the west to the March board. [pause] Here's why. We have one depot, on the east side of the city, and forty-one client sites, including the new one that started in October. Nine of those sites are more than fifty minutes' drive from the depot, and all nine are in the west. I call them the far sites. [next slide]

Slide 2: At those sites, 22% of crew hours go on the road, against 8% elsewhere
First, what that distance costs us in crew time. In the third quarter of this year, travel took twenty-two per cent of crew hours at the far sites. At the rest, it took eight per cent. [pause] Put plainly, more than a fifth of our crews' time at the far sites goes on travel. That's [CHECK: weekly driving hours at the far sites, from Callum] hours of driving a week. [next slide]

Slide 3: Far sites wait more than twice as long for a call-out, and two of last year's three lost clients left over it
Distance costs us clients, too. In the third quarter, the far sites waited on average three hours ten minutes for a call-out. The other sites waited one hour twenty-five minutes. That's more than twice as long. [pause] And it's cost us. We lost three clients last year. Two of them were far sites, and both told us slow call-outs were why they left. [next slide]

Slide 4: Two businesses in the west turned us down this year because of the distance
It's costing us new work as well. This year, two businesses in the west turned us down because of the distance. One put it in writing. The other told us so on the phone. [next slide]

Slide 5: I am asking to bring a costed plan for a second depot in the west to the March board
So that brings me back to my ask. I'd like your go-ahead to bring a full costed plan for a second depot in the west to the March board. The plan will cover the site, the cost, the staffing and the timing. I'm not asking you to decide on the depot today, only to let me bring you the plan. [pause] Thank you. I'll hand back to the chair for questions.

Timing at 140 words a minute
Slide 1: 86 words, 0:37
Slide 2: 59 words, 0:25
Slide 3: 62 words, 0:27
Slide 4: 34 words, 0:15
Slide 5: 70 words, 0:30
Total: 311 words, 2:13. Scripted target 378 words (2:42); slot 3:00.
Under the scripted target by 67 words (0:29). Nothing has been added to fill it. Callum's figure on slide 2 will add a word or two once it's in.

If you run long on the day, cut first:
- Slide 5: "I'm not asking you to decide on the depot today, only to let me bring you the plan." (18 words, 0:08).
- Slide 1: "including the new one that started in October" (8 words, 0:03).

Where the script follows your notes, not the slide:
- Slide 1: the slide says "Client sites: 40"; your notes say 41, because the new site started in October. The script says forty-one. The audience will see 40 on screen until you change the slide.
- Slide 3: the slide says "Clients lost last year: 3, all far sites"; your notes say only two of the three were far sites. The script says two of them were far sites. The audience will see "all far sites" on screen until you change the slide.

Facts used
- One depot, on the east side of the city: slide 1 text; storyboard material.
- Forty-one client sites: slide 1 notes (the slide says 40).
- The new site started in October: slide 1 notes.
- Nine sites more than fifty minutes' drive from the depot: slide 1 headline and text.
- All nine are in the west, called the far sites: storyboard material.
- Third quarter of this year, travel twenty-two per cent of crew hours at far sites, eight per cent at the rest: slide 2 headline and text (Q3 2026).
- More than a fifth: worked out. 22% is more than 20%, which is one fifth.
- Weekly driving hours at the far sites: [CHECK], to come from Callum (slide 2 notes).
- Average call-out response in the third quarter, three hours ten minutes at far sites, one hour twenty-five minutes at others: slide 3 text.
- More than twice as long: worked out. 3 h 10 min = 190 minutes; 1 h 25 min = 85 minutes; 190 ÷ 85 = 2.24.
- Three clients lost last year, two of them far sites, both citing slow call-outs: slide 3 headline and notes.
- Two businesses in the west turned us down this year because of distance: slide 4 headline and text.
- One in writing: slide 4 notes. The other told us on the phone: slide 4 notes; supplied by Maren in answer to storyboard question 1.
- A full costed plan for a second depot in the west, at the March board: slide 5 headline and text; brief ("full").
- The plan will cover site, cost, staffing, timing: slide 5 text.
- Not a decision on the depot itself: brief.
- Hand back to the chair for questions: inputs; slide 5 notes.

Draft for Maren. Nothing has been sent and no deck or file has been changed.
```

## What was observed

**What held.** Every part of both output formats was produced. The scripted target (378 words, 2:42, leaving 0:18) and the slide limit (6) were worked out correctly, and both passes stayed within the limit with five slides. Staff turnover was left out with a reason. In pass two the word counts and times were checked afterwards against the template's counting rule and are right: 86, 59, 62, 34 and 70 words, 311 in all, 2:13, 67 words (0:29) under the target, with nothing added to fill it. Both notes-over-slide differences were found and listed with the on-screen warning (40 against 41 sites on slide 1; "all far sites" against two of three on slide 3, where the headline and the notes agree and the slide text does not). The industrial unit and the landlord talks were held back and asked about. Storyboard question 2, which Maren answered only with "I'll get the weekly driving hours from Callum", was carried forward as still open with a [CHECK] in the script, as the revised step 2 of pass two asks. The slide 1 notes' instruction to open with the ask was followed before the headline's point was made. The last slide hands back to the chair. Every figure in the script appears under Facts used, the two worked-out comparisons show their working, and the answer about the phone call is marked as supplied by Maren.

**Nothing in the inputs called for a stop.** There was a slot, a goal and material; the slide labels matched; the storyboard was approved. The stop conditions, slides as pictures, and the case of a headline and slide text that disagree with no notes to decide were not exercised.

**Differences from the published example.**

- **Questions on the storyboard.** The run asked five: pace; what "call-out response" measures; whether the site that started in October is one of the nine (the Q3 figures predate it); whether "last year" is calendar 2025; and whether to mention that one refusal was in writing. The example asks two: how Maren knows about the second prospect, and whether she wants a weekly-hours figure. The run did not ask either of those.
- **The supporting points.** The run put the lost clients with the lost prospects as one point ("Distance is already costing us clients and new business"); the example puts them with the call-out times. The run's headlines carry the raw figures (22%, 3h10 against 1h25); the example's slide 3 headline carries the worked-out "more than twice as long".
- **Header lines.** The run added a "Working:" line under the scripted target, a note about its own system date on the Prepared line, and the chair's hand-over on the Slot line. The output format asks for none of these. Today's date in the brief was used, as the instructions require.
- **Rafe.** The run read the slide 4 note "Don't name them" as possibly covering Rafe, left his name out ("the other told us so on the phone") and asked. The example names him, reading Maren's "fine to say" as permission. The revised rule says to leave a name out and ask where it is unclear whom the line covers, so the run's reading is allowed; the example's reading rests on Maren's answer.
- **Questions on the talk track.** Five against the example's two. The run's extra three are Rafe and one question for each slide Maren needs to correct. The output format lists a notes conflict as a reason for a question, so the extra two are within it; the example lists those differences only under "Where the script follows your notes".
- **Length.** The run's script is 311 words (2:13), 67 under the target; the example's is 323 words (2:18), 55 under. The run added a line from the brief that the example does not have ("I'm not asking you to decide on the depot today, only to let me bring you the plan") and named it as the first cut.
- **Cues.** The run used [next slide] at the end of four slides and no [point to ...] cue; the example uses [point to the chart] once and no [next slide].

**Where the instructions still leave room to guess.**

1. Whether a presenter's answer such as "fine to say" lifts a "don't name them" line for a colleague named in the same note. The run and the example read it differently, and both readings are within the rule.
2. Whether a slide the presenter must correct is also a question under "To settle", or only a listed difference.
3. Whether a note such as "Keep it short" limits the slide's length. The run followed the notes' order on slide 1 (the ask first) but slide 1 came out its longest slide, at 86 words.

**Shortcomings in the output.**

- Pass one's headline 4, "Distance has already cost us two clients and two prospects in the west", goes a step past the notes for the two clients: the notes say they left over slow call-outs, which the talk attributes to distance. The script in pass two keeps to the notes ("both told us slow call-outs were why they left"). The published example had the same step in its script before it was revised (see the end).
- The header lines described above are outside the output format, which the instructions say to use exactly.

## Facts not in the inputs

- Pass one: the headline step described above, and the remark that a good-news figure "could blur the message", which is advice, not a fact. Nothing else.
- Pass two: none found. "Including the new one that started in October", "I call them the far sites" and "in the third quarter of this year" all come from Maren's notes and slides.

## Reviewer checklist, read against the run

1. The one message is stated in one sentence that names the ask. Yes, though the presenter would judge whether it is in her words.
2. Every figure, name and date in the script is under Facts used, and each matches its origin. Yes.
3. Nothing in the script comes from outside the material. Yes, for pass two.
4. Every difference between notes and slide is listed. Yes, both, with the on-screen warning; the slides are Maren's to correct.
5. Nothing marked confidential or not public is in the script. Yes.
6. Every [CHECK] has been answered and the script retimed. Not yet: Callum's figure is still to come.
7. The total is within the scripted target. Yes. A read-aloud rehearsal against a clock was not part of this run.
8. The last slide hands over to the chair. Yes.

## The earlier run, and what was changed

The first run, on 10 November 2026 in Claude Code with Claude Sonnet 5.5, used the template as first written. It ran pass two on its own storyboard, treated as approved with no answers to its questions, against slides whose headlines came from the published example. It produced both outputs in full and agreed with the example on the two notes-over-slide differences and the held-back landlord talks. It raised these points:

- Pass two asks for the presenter's answers, but the template did not say what to do with a storyboard question approved without an answer.
- "Far sites" was never defined in the notes, and the template had no step for a term the material uses without saying what it covers.
- It was unclear whether the note "Don't name them" covered Rafe; the rule about names covered only names the notes say not to use.
- Every headline on the slides differed from its own storyboard, so its question about retitled slides fired on all five. That was a result of the trial's set-up, which fed it slides built from a different storyboard, not of the template.
- The slide 1 notes say to open with the ask, while the instructions said to make the headline's point; the template did not say which comes first.
- The rule for when a gap earns a [CHECK] was not sharp.
- The word count did not say whether figures count in their written or spoken form.
- The template compared notes with the slide, but not a slide's headline with its own text.
- It found two lines in the published example's script that went beyond the notes: "Distance has already cost us two clients" and "in the part of the city where a second depot would sit". It also noted that the example, like the run, took the far sites to be the nine sites without the notes saying so.

Changed after the first run, before the run recorded above:

- **The template, in both the procedure and the pasted instructions.** A storyboard question approved without an answer stays open and gets a [CHECK] where the script needs it. A term the material leaves undefined becomes a question, with the reading used stated. A headline that disagrees with its own slide text is settled by the notes, or by neither and a [CHECK] if the notes are silent. A "don't name" line covers whom it refers to; a name given with no limit may be used; where it is unclear, the name is left out and asked about. Where the notes say how to run a slide, that comes first and the headline's point is still made. A [CHECK] goes only where the notes or storyboard say a figure is still to come or a needed sentence cannot be said without it; other gaps are questions only. Figures are written as they will be spoken where that form is longer, and counted as written. Slides supplied as pictures are read for their headline and text, with notes set to "none" and words that cannot be read asked for as text. The pasted instructions now also name the presenter's own contractions, and the voice rule was reworded.
- **The example.** Maren's notes now say the nine sites are all in the west and are what she calls the far sites. The script's slide 3 now gives the call-out times as the third quarter's, its closing line says "Slow call-outs at our far sites have already cost us two clients", and slide 4's closing line ends "the clients we want in the west". The counts were redone (323 words, 2:18, 55 under the target) and Facts used now lists the far sites and Maren's permission to mention Rafe.
- **The trial's set-up.** Pass two now receives the inputs the example says Maren supplied: her brief and notes, the storyboard she approved, her answers and her slides.

Nothing was changed after the run recorded above.

Added 10 November 2026, at the editorial review: one change was made to the template after this run. In the output format, the talk track's "To settle" line said to ask one question per "notes conflict"; it now says one question per conflict the notes do not settle. A slide the presenter's notes correct is listed only under "Where the script follows your notes", as in the example. This settles the second point under "Where the instructions still leave room to guess". The template has not been run again since, and the output above is unchanged.
