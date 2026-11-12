# Executive week-ahead calendar review

Workflow template, version 0.1.0.

## Purpose

Prepare one brief on the executive's coming working week, from a calendar export the assistant supplies: the clashes, the journeys and runs of meetings with too little time between them, the meetings with no stated purpose, the meetings whose preparation has no time set aside, the invitations still unanswered, and proposed time reservations for the executive's stated priorities. Each problem ends as a decision for the executive or a question for an organiser. The executive and the assistant choose what changes. The AI assistant never accepts, declines, moves, cancels or sends an invitation, and never adds anything to the calendar.

## When to use it and when not to

Use it once a week, on the last working day or two before the week it reviews, when the assistant and the executive sit down to plan the week. Run it again when the calendar changes enough to matter, such as a new board date or a meeting moved by a client.

Do not use it:

- to find a time for one new meeting, or to prepare a move and the notice that goes with it. Those are separate pieces of work;
- to write a meeting's agenda, notes or follow-ups. Use the meeting agenda, notes and follow-ups workflow template;
- to plan or price a trip. A journey that needs a flight, a train or a hotel goes to the business trip plan workflow template; this review only checks the time between places;
- to sort the inbox. Use the inbox triage workflow template;
- to judge how anyone spends their time, or to score an executive's or a team's workload. The brief describes one week's calendar and nothing else.

## Roles

- **Runs it:** the executive assistant, chief of staff or office manager who keeps the executive's calendar.
- **States the priorities and makes the decisions:** the executive.
- **Answers questions about purpose and preparation:** each meeting's organiser, asked by the assistant.
- **Changes the calendar:** the assistant, after the executive decides. Accepting, declining, moving and adding time are always done by a person.
- **The AI assistant:** checks and proposes. It contacts nobody and changes nothing.

## Inputs

Everything is pasted or attached by the person who runs it. No calendar or mailbox is connected, and the template never asks for a password or a login code.

1. **The calendar export** for the week, one row per event, with these default headers: `Date, Start, End, Title, Location, Organiser, Attendees, Response, Purpose`.
   - Date as YYYY-MM-DD. Start and End in 24-hour time, all in one time zone. Start and End blank for an all-day event.
   - Location: a place name, `Video`, or blank.
   - Attendees: everyone invited except the executive, separated by semicolons. Blank for the executive's own time, such as a preparation block. If the organiser is also the only name listed, as exports often do, the event is still a meeting.
   - Response: `Accepted`, `Tentative`, `Not answered`, `Declined` or `Organiser`.
   - Purpose: the purpose or agenda line from the invitation, or blank.
   - A private event shows `Private` or `Busy` as its title.
   - If there is no export, stop. If any default header is missing or named differently, stop, show the headers found beside the defaults, and ask which column is which; do not guess. Extra columns are not used and are named in the brief's header. If a Response value is not one of the five, or the export shows more than one time zone, stop and ask.
2. **The executive's priorities for the week,** in the executive's order, with the default headers `Priority, Hours wanted, Time of day`. Time of day is `Morning`, `Afternoon` or `Any`. If a header does not match, stop and ask. If there are no priorities, the brief says "No priorities supplied" and proposes no reservations. A priority with no hours is listed as not placed. The template never invents a priority.
3. **The preparation list:** meetings that need preparation, with the default headers `Meeting, Date, Preparation needed, Minutes`. Meeting is the title exactly as it appears in the export. If a header does not match, stop and ask. If there is no list, the brief says "Preparation list not supplied" and checks no preparation.
4. **Travel times** between the places the executive goes, with the default headers `From, To, Minutes`. Each line counts in both directions. If a header does not match, stop and ask. If none are supplied, every change of place is reported as "travel time not supplied". The template never estimates a journey.
5. **The settings,** with these defaults where none are given:
   - the week: Monday to Friday after the date of the export;
   - working days Monday to Friday, working hours [your working hours] (default 08:30 to 18:00);
   - the base: [your base place] (default `Office`), where the executive works between meetings;
   - protected times, such as a school run, with day and times (default: none);
   - the shortest break worth keeping between meetings: [your break] (default 10 minutes);
   - the longest run of meetings without that break: [your run limit] (default 3 hours);
   - reservations between [your shortest block] and [your longest block] (defaults 60 and 120 minutes);
   - morning from the start of working hours to 12:00, afternoon from 12:00 to the end;
   - preparation time is labelled `Prep: ` followed by the meeting's title;
   - all-day events that mean the executive is away: titles containing `Out of office`, `Holiday`, `Leave` or `Away`.

## The procedure

1. **Read the export.** Check the headers and values as set out under Inputs. Leave out every `Declined` row and count them. Sort the rest by date and start time.
2. **Sort each event into one kind.** A *private event* has the title `Private` or `Busy`. *Own time* has no attendees and is not private. A *meeting* has at least one attendee and is not private. A private event is shown only as "Private event" with its times; its title, place, attendees and purpose are never repeated.
3. **Week at a glance.** For each working day: the number of meetings; the time they cover, counting meetings only, with overlaps counted once and time outside working hours included; and the free time inside working hours, which is working hours less the time covered by every event, private events and own time included, and by protected time. Proposed reservations do not change these figures. Write all-day events on their day's line.
4. **Conflicts.** Two events conflict when one starts before the other ends; one ending as the next starts is not a conflict. Events and protected times that overlap one another form one conflict, listing all of them. A meeting on a day with an all-day "away" event conflicts with it. A meeting or own time that starts before or ends after working hours, or falls on a day that is not a working day, is a conflict marked "outside working hours". Private events outside working hours are not flagged.
5. **Travel.** For each meeting with a named place (not `Video`, not blank), take the next meeting with a named place on the same day. If the two places differ and the meetings do not overlap: the gap is the second start less the first end. If no travel time is supplied for that pair, report "travel time not supplied". If the gap is shorter than the travel time, report the gap, the travel time and the minutes short. A meeting with a blank location gets one line, "location not stated; travel not checked".
6. **Breaks.** Join meetings into a run while each next meeting starts less than [your break] after the latest end so far. A run longer than [your run limit], from its first start to its last end, is reported with the number of meetings, its length and how far it is over.
7. **Purpose.** Each meeting with a blank Purpose is listed. If the executive organised it, it becomes a decision for the executive. Otherwise it becomes a question for the organiser, for the assistant to ask.
8. **Preparation.** For each line of the preparation list, find the meeting by its title and date. If it is not in the export, write "not in the calendar export". Otherwise add up the own time titled `Prep: ` and the meeting's title that ends before the meeting starts, on the meeting's day or the working day before it, if that day is in the week. If the total is at least the minutes needed, write "covered". If not, the minutes short become a preparation reservation in step 10.
9. **Invitations not yet answered.** List every event whose Response is `Not answered` or `Tentative`. If it is already part of a conflict or a travel and breaks item, point to that item; its decision also asks for the answer. Otherwise it gets its own decision.
10. **Free gaps for reservations.** A free gap is time inside working hours that no event, protected time or reservation already proposed covers. It begins [your break] after the end of whatever comes before it, or, when that is a meeting at another named place, after the travel time back to the base, if that is longer. It ends the same way before whatever comes next. The break is kept on both sides of every proposed reservation, as it is around every other event. At the start and the end of working hours no break is kept, but this applies only where nothing at another place follows: when the next event is at another named place, even one that starts exactly when working hours end, the gap ends the travel time from the base before it, and that rule wins. When the gap lies between two events at different named places, neither of them the base, it begins after the travel time from the first place to the base and ends the travel time from the base to the second place before it. When any travel time needed is not supplied, the gap is not offered. Own time, private events, protected times and meetings with a blank location count as being at the base; video meetings need only the break.
11. **Place the preparation reservations first,** in the date order of their meetings. Each is exactly the minutes short. Look on the meeting's day, in gaps that end before the meeting, and on the working day before it, if that day is in the week. Take the latest gap with enough room, so a gap on the meeting's day wins over one on the working day before, and place the reservation so it ends where the gap ends. If no gap has room, write "no slot found".
12. **Then place the priorities,** in the executive's order. For each, go through the working days in order and, within each day, the gaps from earliest. Use only the part of a gap inside the priority's time of day. The length is the smallest of [your longest block], the hours still wanted, and the usable part of the gap rounded down to whole quarter hours. Place it at the start of the usable part only if it is at least [your shortest block], or if it equals all the hours still wanted. At most one reservation per priority per day. Each reservation placed counts as busy for the next. If time is still wanted after the last day, report how much and say no other slot of [your shortest block] or more is free in that time of day.
13. **Number the items** in each section by day and time, and write the decisions. One decision for each conflict, each travel and breaks item, each purpose item the executive organised, and each invitation not already inside another item. Order them by day, then by the item's time: a conflict's earliest start, a travel gap's first end, a run's start, any other item's start; at the same time, conflicts first, then travel and breaks, then purpose, then invitations. The last decision covers all the proposed reservations and any shortfall. Each decision gives the facts and asks the question. Recommend nothing unless the executive asks.
14. **Return the brief** to the person who ran it. The executive decides; the assistant makes the calendar changes and asks the organisers' questions. When answers come back, run the review again on the new export.

## Exceptions and stop conditions

- **No export, a header that does not match, an unknown Response value or more than one time zone:** stop and ask. Do not guess which column is which.
- **A row whose end is before its start, or whose date is outside the week:** stop on that row and ask.
- **Asked to accept, decline, move, cancel or send an invitation, or to add a reservation to the calendar:** decline, and return the brief for the assistant to act on once the executive decides.
- **Asked which meeting matters more, or which to drop:** lay out the facts in the decision and leave the choice to the executive. Give a view only when the executive asks for one, and label it as a view.
- **Asked to estimate a journey:** decline and report "travel time not supplied" until someone gives the time.
- **Asked to judge the executive's or anyone's workload or performance:** decline; the brief describes the calendar for one week only.
- **An event's title or purpose concerns one person's health, pay, performance or a personal matter:** show it as "Private event" with its times only.
- **The export, notes or priorities contain a password, a login code or a meeting passcode:** do not repeat it; say in the header which input it is in, so the person removes it from the source.
- **A journey needs travel booked, or a meeting needs an agenda written:** say so in that item's decision and point to the business trip plan or the meeting agenda, notes and follow-ups workflow template. Do not do that work here.

## Output format

```
WEEK-AHEAD CALENDAR REVIEW: [executive (role)], week of [weekday date]

For: [assistant] and [executive]. Prepared [weekday date of the export] from the calendar export of [date, time] ([n] events; [n] declined, left out), [n] priorities / no priorities supplied, the preparation list ([n] lines) / preparation list not supplied, [n] travel times / no travel times supplied. [Columns not used: names.] [Remove from [input]: it contains a password, login code or passcode.]
Settings: times in [time zone]; working days [days], [start] to [end]; base [place]; protected [day start to end (name)] / none; break [n] min; longest run [time]; reservations [n] to [n] min; morning [start] to 12:00, afternoon 12:00 to [end].

Week at a glance
[Weekday date]: [n] meetings, [time] of meetings; [time] free in working hours. [All day: title.]

Conflicts: [n / None]
C[n]. [Weekday date]. [Event] ([start] to [end], [place], from [organiser], [response]) / Private event ([start] to [end]) overlaps [event (same details) / Private event (start to end) / protected time, start to end (name) / all-day away event (title)]. Decision [n].
C[n]. [Weekday date]. [Event] ([start] to [end], [place], from [organiser], [response]) is outside working hours, which end at [time] / start at [time]. Decision [n].

Travel and breaks: [n / None]
T[n]. [Weekday date]. [Event] ends [time] at [place]; [event] starts [time] at [place]. Gap [n] min; travel [n] min: short by [n] min. / Travel time not supplied. Decision [n].
T[n]. [Weekday date], [start] to [end]. [n] meetings with no break of [n] min: [time], over the [time] limit by [time]. Decision [n].
T[n]. [Weekday date] [start], [event]: location not stated; travel not checked. Decision [n].

Purpose not stated: [n / None]
M[n]. [Weekday date] [start] to [end], [event], from [organiser]. No purpose in the invitation. Decision [n]. / Question [n] for the organiser.

Preparation: [n / None / Preparation list not supplied]
P[n]. [Weekday date] [start], [meeting]. Needs: [preparation] ([n] min). Set aside: [title, weekday start to end ([n] min)] / none. Covered. / Short by [n] min: proposed R[n]. / Short by [n] min: no slot found. / Not in the calendar export.

Invitations not yet answered: [n / None]
I[n]. [Weekday date] [start] to [end], [event], from [organiser]: [Not answered / Tentative]. See C[n] / T[n]. / Decision [n].

Proposed time reservations: [n / None / No priorities supplied]
R[n]. [Weekday date], [start] to [end] ([n] min). [Priority / Prep: meeting].
[Priority]: wanted [time]; proposed [time] ([R numbers]). [Short by [time]: no other [morning / afternoon / working-hours] slot of [n] min or more is free.] / Not placed: hours not stated.

Decisions for [executive]: [n / None]
[n]. [Item numbers], [weekday date]. [The facts.] [The question.] [View, as asked by [executive]: ...]

Questions for organisers, for [assistant] to ask: [n / None]
[n]. [Organiser], about [event], [weekday date] [start] to [end]: what is the meeting for, and should [executive] read or bring anything?

Draft for [assistant] and [executive]. No invitation has been accepted, declined, moved or sent, and nothing has been added to the calendar.
```

"Prepared" is the date of the export, not the date of the run. A decision carries the date of its item; the last decision, on the reservations, spans several days and has no date. The count of events is every row in the export, declined rows included; the declined rows are then counted again as left out. Times are written as `[n] h [n] min`, leaving out a part that is zero. A section with nothing in it prints its heading with "None".

## Reviewer checklist

The assistant checks, before the brief goes to the executive:

1. Every event in the export appears where it should: declined rows counted and left out, private events shown only by their times. (Assistant)
2. Each day's meeting count, meeting time and free time can be added up again from the export. (Assistant)
3. Every conflict is a real overlap or a real time outside working hours, and none is missing. (Assistant)
4. Every travel time used was supplied, and no journey was estimated. (Assistant)
5. Every proposed reservation sits in free time, keeps the break and the journey around it, and stays inside the priority's time of day. (Assistant)
6. Every decision gives its facts and asks a question, and none recommends an answer the executive did not ask for. (Assistant)
7. Nothing in the brief reads as if a change has already been made. (Executive)

## Acceptance tests

Proposed tests. None has been run.

1. **Ordinary week.** No overlaps, every travel time supplied and long enough, every meeting with a purpose. Expected: every section but the glance and reservations says "None"; reservations placed by the rules.
2. **Header mismatch.** The export has `Subject` in place of `Title`. Expected: stops, shows found and default headers, asks which column is which.
3. **Overlap.** Supplier A service review 15:00 to 16:00, tentative, and Finance weekly 15:30 to 16:30. Expected: one conflict listing both; the invitation listed as tentative and pointed to the conflict; one decision.
4. **Back to back.** Four meetings from 09:00 to 12:30 with no gap. Expected: one run of 3 h 30 min, over the 3 h limit by 30 min.
5. **Short journey.** A meeting at Client B offices ends 11:00; the next at the Office starts 11:15; travel 30 minutes. Expected: gap 15 min, short by 15 min.
6. **Journey not supplied.** Two places with no travel time between them. Expected: "travel time not supplied"; no estimate; no reservation offered in that gap.
7. **No purpose.** A "Catch-up" with a blank purpose from another organiser. Expected: a question for that organiser, not a decision.
8. **Preparation partly set aside.** Needs 90 minutes; a 60-minute `Prep:` block exists. Expected: short by 30 min and a 30-minute reservation in the latest gap before the meeting.
9. **Not enough free time.** A priority wanting 4 hours of mornings with only 3 h 15 min usable. Expected: the reservations placed and "short by 45 min".
10. **Private event.** A `Private` event that overlaps a meeting. Expected: the conflict shows "Private event" and its times only.
11. **Asked to act.** "Decline the vendor demo and put the budget blocks in." Expected: declines and returns the brief for the assistant to act on.
12. **Away all day.** An all-day "Out of office" on Friday with a meeting at 10:00. Expected: the meeting listed as a conflict with the away event.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
You prepare a week-ahead calendar review for an executive and their
assistant. You check and propose; people decide. You never accept,
decline, move, cancel or send an invitation, never add anything to a
calendar, never contact anyone and never change any record. You work
only from what the person pastes or attaches, and you never ask for a
password, a login code or access to a calendar or mailbox.

Inputs: the calendar export (headers Date, Start, End, Title, Location,
Organiser, Attendees, Response, Purpose); the priorities (Priority,
Hours wanted, Time of day); the preparation list (Meeting, Date,
Preparation needed, Minutes); travel times (From, To, Minutes, either
direction); and the settings. If the export is missing, a header in the
export, the priorities, the preparation list or the travel times is
missing or named differently, a Response is not Accepted, Tentative,
Not answered, Declined or Organiser, the export shows more than one
time zone, a row ends before it starts, or a row is dated outside the
week, stop: show what you found and ask. Never guess a column. Name
any extra columns in the header as not used. If priorities, the
preparation list or travel times are missing, say so in the header and
continue. A priority with no hours is listed as "Not placed: hours not
stated".

Defaults unless the settings say otherwise: the week is Monday to Friday
after the export date; working hours 08:30 to 18:00; base Office; no
protected times; break 10 min; longest run 3 h; reservations 60 to 120
min; morning to 12:00, afternoon from 12:00; preparation time titled
"Prep: " and the meeting title; away words Out of office, Holiday,
Leave, Away.

1. Count every row as an event. Leave out Declined rows and count
   them. A Private or Busy title is a private event: show only
   "Private event" and its times. No attendees and not private is own
   time. Anything else is a meeting.
2. Week at a glance, per working day: meetings, the time they cover
   (meetings only; overlaps once, outside hours included), and free
   time in working hours (working hours less every event, private
   events and own time included, and protected times). Ignore
   reservations here. Show all-day events on their day.
3. Conflicts: events and protected times that overlap (touching is not
   overlap) form one conflict. A meeting on a day with an all-day away
   event conflicts with it. A meeting or own time outside working hours
   is a conflict marked so; a private event outside hours is not.
4. Travel: for each meeting at a named place (not Video, not blank),
   take the next one at a named place the same day. If the places
   differ and they do not overlap: gap = second start - first end. No
   supplied time: "travel time not supplied". Gap shorter than the
   time: give gap, time and minutes short. Never estimate a journey. A
   meeting with a blank location: "location not stated; travel not
   checked".
5. Breaks: join meetings while each starts less than the break after
   the latest end so far. Report a run longer than the limit, with the
   number of meetings, its length and how far over.
6. Purpose: each meeting with a blank Purpose. If the executive
   organised it, it is a decision; otherwise a question for its
   organiser.
7. Preparation: match each list line by title and date. Add up "Prep: "
   own time ending before the meeting, that day or the working day
   before if it is in the week. Enough: "covered". Not enough: the
   minutes short become a reservation. Not found: "not in the calendar
   export".
8. Invitations: list every Not answered or Tentative event. If it is in
   a conflict or a travel and breaks item, point there; otherwise it
   gets its own decision.
9. Free gaps: time in working hours with no event, protected time or
   earlier reservation. A gap starts the break after what comes before,
   or the travel time back to base if that was a meeting at another
   named place and the time is longer; it ends the same way before what
   comes next. Keep the break on both sides of every reservation. No
   break at the start or end of working hours, except that when the next
   event is at another named place, even one starting exactly when
   working hours end, the gap ends the travel time from the base before
   it. Between two different named places, neither the base, the gap
   begins after the travel time from the first to the base and ends the
   travel time from the base to the second before it. If any travel time
   needed is not supplied, skip the gap. Own time, private events,
   protected times and blank-location meetings are at the base; video
   meetings need only the break.
10. Preparation reservations first, by meeting date: exactly the minutes
    short, in the latest gap with room that ends before the meeting, on
    its day or the working day before if that day is in the week (a gap
    on the meeting's day wins); place it to end where the gap ends. None: "no slot found".
11. Then priorities in the executive's order: day by day, earliest gap
    first, only the part inside the time of day. Length = the smallest
    of the longest block, the hours still wanted, and the usable gap
    rounded down to whole quarter hours. Place it at the start of the
    usable part if it is at least the shortest block or equals all the
    hours still wanted. One per priority per day. Each counts as busy
    for the next. Report any shortfall.
12. Number items by day and time. One decision per conflict, travel and
    breaks item, purpose item the executive organised, and invitation
    not inside another item; order by day, then the item's time (a
    conflict's earliest start, a travel gap's first end, a run's start,
    otherwise the event's start; at the same time C, T, M, I). The last
    decision covers all reservations and any shortfall, and has no date. Give the facts
    and ask the question. Recommend nothing unless the executive asks.
13. Use the output format exactly; "Prepared" is the weekday date of
    the export. Print "None" under an empty section.
    End with: "No invitation has been accepted, declined, moved or
    sent, and nothing has been added to the calendar."

If asked to accept, decline, move, cancel or send anything, or to add a
reservation, decline and return the brief for the assistant to act on.
If asked which meeting matters more, give the facts and leave the choice
to the executive. If asked to judge anyone's workload or performance,
decline. Show any event about one person's health, pay, performance or a
personal matter as "Private event". Never repeat a password, login code
or meeting passcode found in the inputs; tell the person to remove it.
Check every figure against the export before you return the brief.
```

## What to customize

- [your working hours], working days and the time zone the export uses.
- [your base place], and the travel times between it and the places the executive goes most.
- Protected times, such as a school run, a standing lunch or a weekly no-meeting afternoon.
- [your break] and [your run limit].
- [your shortest block] and [your longest block], where morning ends and afternoon starts, and whether a priority may take more than one reservation a day.
- The label the calendar uses for preparation time, and the all-day titles that mean the executive is away.
- Whether the executive wants a view on conflicts, or only the facts.
- Which calendar fields the assistant may export, and which events are always shown as private.
- Which assistant products may be given the export: ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI from its own published map of executive and office support work. Editorially reviewed. Tried once on its invented example in Claude on 10 November 2026, by a model that did not write it, with the record published; not yet tested in a client environment.
