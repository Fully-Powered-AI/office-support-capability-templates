# Business trip plan

Capability template, version 0.1.0.

## Purpose

Prepare one plan for one traveller's business trip from the traveller's brief, the options the booker has found, the journey times and the travel policy. The plan fixes the dates and nights, shortlists the journey out, the journey back and the hotel with prices and the date each was checked, times every day around the fixed meetings, estimates the cost against the policy and lists the bookings still to make. Every gap becomes a question for the booker. The assistant compares and times; it never books, holds, pays, signs in anywhere or enters payment or passport details.

## When to use it and when not to

Use it once the meetings for a trip are fixed, usually two to four weeks ahead, for one traveller on a trip of one to five nights. Run it again whenever a meeting, a price or a date changes.

Do not use it for:

- a group trip, an offsite or an event. Run it once per traveller, or use the event plan capability for the event itself;
- visas, entry rules, vaccinations or other requirements to enter a country. The traveller checks those with the official government sources; the plan only records that they have been checked;
- an expense claim after the trip, or deciding whether a trip should happen at all;
- making, holding, changing or paying for any booking. People do that.

## Roles

- **Runs it:** the booker, usually an executive assistant, an office manager or a team coordinator, or a traveller who books for themselves.
- **Decides:** the traveller chooses among the options and confirms the timetable works for them. The booker settles every gap.
- **Approves exceptions:** the person the travel policy names, for anything over policy, before it is booked.
- **Books and pays:** the booker or the traveller, as the brief says, in the airline's, hotel's or travel tool's own pages.
- **The AI assistant:** compares, times and lists. It contacts nobody and books nothing.

## Inputs

Everything is pasted or attached by a person. No travel tool, booking site, calendar, mailbox or card is connected.

1. **The traveller's brief.** Today's date; the traveller's name and role; the booker; the destination; the date out and the date back; the airport or station the trip starts from; the fixed meetings, each with date, start, end and place; the traveller's requirements (for example a hotel within a set walk of a meeting, no overnight flights, carry-on only, an accessibility need, in the traveller's own words); the purpose and cost centre if there is one; who approves exceptions. If the destination, the date out or the date back is missing, stop and ask.
2. **The options,** as a pasted table or export. Default headers: Ref, Type, Provider, Details, Dates, Depart, Arrive, Price, Price covers, Cancellation, Checked on, Source. Type is Flight, Train or Hotel. Dates is one date for a journey and the check-in and check-out dates for a hotel. Times are local. If the headers do not match these, stop and ask which column is which before reading any row. A row with no price or no Checked on date is listed, used in nothing, and becomes a question.
3. **Journey times.** From home to the departure airport or station, from the arrival airport or station to the first place, between each pair of places, and back, each with the mode and any cost, as the booker's maps app or the traveller gives them. A time given as a range is planned on its longer end. A time is used only in the direction given unless the line says "either way"; the reverse journey otherwise has no time. A missing journey is never guessed.
4. **The travel policy,** or the excerpt that covers the trip. If none is supplied, write "policy not supplied" and check nothing against policy. Never invent a limit.
5. **Bookings already made,** by provider, date and booking reference only. If none, write "nothing supplied".
6. **Your settings:** [your airport margin] (default: at the departure airport 90 minutes before a domestic flight; 30 minutes from landing to leaving the arrival airport; 15 minutes at a station before a train), [your meeting margin] (default: arrive 15 minutes before each meeting), [your price age] (default: a price checked more than 3 days before today is checked again before booking) and [your direct sources] (default: the provider's own site, the company travel tool and a quote from the company's travel agency).

## The procedure

1. **Fix the trip dates.** Take the date out, the date back and the departure point exactly as the brief gives them. Count the nights and name the city for each. Never shorten or lengthen the stay to suit an option. When the brief changes, rebuild the whole plan from the new dates and name the change in the header.
2. **Check the meetings against the trip dates.** List each fixed meeting in date order. Flag a meeting that falls outside the trip dates, overlaps another meeting, has no place, or sits in a different town from the destination named in the brief.
3. **Read every option.** Check that it matches the trip's dates, the route and the departure point. Mark where its price came from: **Direct** (one of [your direct sources], for these dates), **Third-party** (another site, for these dates) or **From-price** (a "from" fare, an alert or any price not for these exact dates). A From-price is never used in the shortlist or the estimate. Mark RECHECK on any price checked more than [your price age] days before today.
4. **Set aside what cannot work,** before comparing anything, with the reason: dates that do not match the brief; a departure point other than the one in the brief (never swapped in, whatever its price); a journey that does not reach a fixed meeting with the meeting margin; a journey home that departs before the earliest workable departure (step 6); a hotel that breaks one of the traveller's requirements; a From-price; a row with no price or no checked date.
5. **Shortlist** the journey out, the journey back and the hotel. For each, name the option with the lowest total price that is left, as "Lowest that fits", and the next lowest as "Alternative", or write "none that fits". A hotel's total is the nightly rate times the nights plus the taxes and fees the row gives; if the row gives no taxes or fees, write "taxes not given" and count the rate only. Check each against the policy: within, over (and why, with the amount and the person who must approve it), or not covered by the policy supplied. Where a Lowest that fits option is over policy and a cheaper option was set aside, write in one line why the cheaper one does not work, ready for an exception request.
6. **Time each day** using the Lowest that fits options. Time forward from each fixed journey: leave home, at the departure point, departs, arrives, leaves the arrival point, each transfer with its mode and minutes. Time backward from each meeting: the latest time to leave the previous place is the meeting start, less the meeting margin, less the transfer. Where a journey leg fixes the arrival, state the spare minutes before the meeting margin; if they are below zero, write TIMING with the minutes short. For the journey home, the earliest workable departure is the end of the last meeting plus the transfer plus the airport or station margin. Use the cheapest supplied transfer mode that fits, and name the other in brackets. A transfer with no supplied time is written TRANSFER TIME NEEDED and becomes a question.
7. **Estimate the cost.** One line each for the journey out, the journey back, the hotel, ground transport, parking and meals, with the amount, where it came from (Direct, Third-party, supplied by the booker, or policy allowance) and the policy check. Meals are counted only at an allowance the policy gives. Total each currency separately; convert only at a rate the person supplies. List what is over policy and who must approve it before booking. List everything not priced: a transfer with no cost, bags or seats the brief needs and no row prices. Never guess a figure. Costs for personal days the traveller adds are shown apart and kept out of the total.
8. **List the bookings still to make.** For each shortlisted item: who books it (from the brief, or "booker not named"), the date it must be booked by (from the policy's advance-booking rule, a fare hold or a rate deadline in the row, or "no deadline supplied"), whether approval is needed, the cancellation terms as given, and the date after which its price must be checked again (the checked date plus [your price age]). List what is already booked.
9. **Count the gaps** and list them first, one question each: a missing journey time, a meeting flag, an option row with no price or date, a requirement the options cannot meet, a policy question the excerpt does not answer that decides whether an option fits or needs approval. A cost the excerpt does not mention is marked "not covered" on its line and is not a question by itself.
10. **Return the plan to the booker.** The traveller chooses; the booker books. When the booker answers a gap, update the plan, mark the answer "set by [name]" and recount.

## Exceptions and stop conditions

- **No destination, no date out or no date back:** stop and ask.
- **Option headers that do not match the defaults:** stop and ask which column is which.
- **An option priced for other dates or another departure point:** set it aside with the reason. Never adjust the trip to fit it, and never price it as if it were for the brief's dates.
- **No option fits a leg or the hotel:** write "none that fits", say which requirement or meeting rules each out, and put the question first.
- **Asked to book, hold, change, cancel or pay for anything, to sign in to a booking site or travel tool, or to fill in a booking form:** decline and return the plan for the booker.
- **Card numbers, passport numbers, loyalty account passwords or login codes in the inputs:** do not repeat them; tell the person to remove them from what they pasted. Never ask for any of them.
- **Asked whether a fare will fall, or whether to wait:** give no forecast. Say the price is as checked on its date, and show the booking deadline.
- **Asked about visas, entry rules or vaccinations:** decline; the traveller checks the official government sources, and the plan does not cover them.
- **A health or accessibility need in the brief:** treat it as a requirement, in the traveller's words, and give no advice about it.
- **The AI product can read public web pages and the person asks for more options:** add them only from pages that need no sign-in, each marked "found by the assistant" with the page and today's date as its checked date, and never go past a price display into a booking step.

## Output format

```
BUSINESS TRIP PLAN: [traveller (role)], [destination], [weekday date] to [weekday date]
Prepared [today's date] for [booker]. Purpose: [purpose, or "not stated"]. Cost centre: [code, or "not stated"].
Changes from the last plan: [what changed in the brief, or "first plan"].
Trip dates: out [weekday date], back [weekday date]. [n] nights: [date, city; date, city]. Starts from: [airport or station, as in the brief].
Policy: [what was supplied, or "policy not supplied: nothing is checked against policy"]. Exceptions approved by: [name (role), or "not stated"].
Settings: at the airport [n] min before departure, [n] min from landing to leaving; at each meeting [n] min early; prices checked again after [n] days. All times local.

To settle before booking: [n, or None]
[n]. [One question per gap.]

Fixed meetings
- [Weekday date], [start] to [end]. [Meeting]. At [place]. [FLAG: what is wrong.]

Shortlist
Journey out
- Lowest that fits: [Ref], [provider], [route], [depart] to [arrive], [price] ([what it covers]). [Direct / Third-party][, found by the assistant on (page)], checked [date]. [RECHECK.] Cancellation: [as given]. Policy: [within / over: reason and amount; approval from (name) / not covered].
- Alternative: [same fields, or "none that fits"].
Journey back
- Lowest that fits: [same fields].
- Alternative: [same fields, or "none that fits"].
Hotel
- Lowest that fits: [Ref], [hotel], [area and distance as given], [n] nights at [rate] = [subtotal], plus [taxes and fees, or "taxes not given"] = [total]. [Direct / Third-party], checked [date]. [RECHECK.] Cancellation: [as given]. Policy: [within / over: reason and amount; approval from (name) / not covered].
- Alternative: [same fields, or "none that fits"].
Exception reason: [one line where a Lowest that fits option is over policy and a cheaper option was set aside, or "none needed"].

Set aside, and why
- [Ref], [provider], [price as given]: [reason]. / None.

Day by day, if the Lowest that fits options are booked
[Weekday date]
- [time] [step]. [mode, n min, cost]
- [start] to [end] [meeting], [place]. [Spare before the meeting margin: n min. / TIMING: short by n min. / Leave [previous place] by [time]: mode, n min, cost.]
- [step]: TRANSFER TIME NEEDED (question [n]).

Cost estimate
- Journey out, [Ref]: [amount]. [Source]. Policy: [within / over by amount / not covered].
- Journey back, [Ref]: [amount]. [Source]. Policy: [...].
- Hotel, [Ref]: [amount]. [Source]. Policy: [...].
- Ground transport: [each priced transfer and its cost] = [amount]. Supplied by [name]. Policy: [...].
- Parking: [days x rate = amount, or "none"]. Supplied by [name]. Policy: [...].
- Meals: [days x allowance = amount, or "no allowance supplied"]. Policy allowance.
Total: [amount and currency, one line per currency].
Over policy: [line, amount, or "none"]. Approval needed before booking from [name]: [items, or "none"].
Not priced: [items, or "none"].
Personal costs, kept out of the total: [items and amounts, or "none"].

Bookings still to make
[n]. [Ref], [item], [price]. Booked by: [name, or "booker not named"]. Book by: [date (reason), or "no deadline supplied"]. Approval: [needed from name / not needed under the policy supplied / policy not supplied]. Cancellation: [as given]. Check the price again if booking after [date].
Already booked: [provider, date, reference, or "nothing supplied"].

Draft for [booker]. Nothing has been booked, held, paid or sent.
```

## Reviewer checklist

The booker checks, before the traveller sees it:

1. The dates out and back and the number of nights match the brief exactly, and every option used is for those dates.
2. Every option on the shortlist starts from the departure point in the brief; nothing from another airport or station was swapped in.
3. Every price on the shortlist and in the estimate shows where it came from and the date it was checked, and no From-price is used.
4. Every time in the day-by-day plan follows from the supplied journey times and the settings, and no journey time was guessed.
5. Every fixed meeting is reached with the meeting margin, or carries a TIMING flag.
6. The cost lines add up to the total, and each policy check matches the policy as pasted.
7. Every item over policy names its approver, and nothing over policy is listed as ready to book without that approval.
8. No card number, passport number or login detail appears anywhere in the plan.
9. The traveller has read the timetable and confirmed it works for them.

## Acceptance tests

Proposed tests. None has been run.

1. **Straightforward trip.** Two nights, three meetings, one flight each way and one hotel that fit the policy. Expected: dates and nights as in the brief, a shortlist with alternatives, spare minutes before each meeting, a total that adds up, nothing to settle.
2. **Flight lands too late.** The cheapest outbound flight lands 55 minutes after the first meeting starts. Expected: set aside with that reason; the next option that fits becomes Lowest that fits.
3. **Other airport.** The cheapest fare leaves from a different airport from the one in the brief. Expected: set aside as a different departure point, with its price shown; never on the shortlist.
4. **Wrong nights.** A hotel row is priced for three nights where the brief has two. Expected: set aside; the stay is not changed to three nights and the rate is not scaled down to two.
5. **From-price.** A fare alert gives "from $129" for the return route. Expected: set aside as a From-price; not in the estimate.
6. **Over the hotel cap.** The hotel nearest the meetings is above the nightly cap. Expected: if a cheaper hotel fits, the dearer one is the Alternative with "over" and the approver named; if none fits, it is Lowest that fits, over policy, with an exception reason and the approver.
7. **Missing journey time.** No time is supplied between two meetings. Expected: TRANSFER TIME NEEDED and a question; no time guessed.
8. **Headers do not match.** The options export has "Cost" and "Seen on" in place of Price and Checked on. Expected: stops and asks which column is which.
9. **Asked to book.** "Book F1 on the company card." Expected: declines and returns the plan for the booker.
10. **Card number in the inputs.** The pasted brief contains a card number. Expected: the number appears nowhere in the plan, and the person is told to remove it.
11. **Old price.** A hotel price checked six days before today. Expected: RECHECK on the shortlist line and a check-again date in the bookings list.
12. **No policy.** No policy is supplied. Expected: "policy not supplied" in the header, every policy check "not covered", no limit invented, meals "no allowance supplied".

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above. The block tells the assistant to use that format and does not repeat it.

```
You prepare one business trip plan for one traveller, for the person who
books the trip. You compare options, time each day and estimate the cost.
The traveller and the booker choose, book and pay. You never book, hold,
change, cancel or pay for anything, never sign in to a booking site or
travel tool, never fill in a booking form, and never send a message.
Never ask for a password, a login code, a card number or passport
details. If any of these appear in what you are given, do not repeat
them, and tell the person to remove them.

Work only from what the person pastes: the brief, the options, the
journey times, the travel policy, anything already booked and their
settings. If the destination, the date out or the date back is missing,
stop and ask. The options' default headers are: Ref, Type, Provider,
Details, Dates, Depart, Arrive, Price, Price covers, Cancellation,
Checked on, Source. If the headers do not match, stop and ask which
column is which before reading any row.

1. Fix the trip dates from the brief: date out, date back, each night and
   its city, and the departure point. Never change these to suit an
   option. When the brief changes, rebuild the whole plan from the new
   dates and name the change in the header.
2. List the fixed meetings in date order. Flag one outside the trip
   dates, overlapping another, with no place, or in a different town
   from the destination.
3. For each option, mark the price Direct ([your direct sources]; default
   the provider's own site, the company travel tool or the company's
   agency, for these dates), Third-party (another site, for these dates)
   or From-price (a "from" fare, an alert, or any price not for these
   exact dates). Mark RECHECK if it was checked more than [your price
   age] days before today (default 3).
4. Before comparing, set aside with the reason: wrong dates; a departure
   point other than the brief's (never swap one in); a journey that
   misses a fixed meeting with the meeting margin; a journey home that
   departs before the earliest workable departure (step 6); a hotel that
   breaks a requirement in the brief; a From-price; a row with no price
   or no checked date.
5. For the journey out, the journey back and the hotel, name the lowest
   total price left as "Lowest that fits" and the next as "Alternative",
   or "none that fits". Hotel total: nightly rate times nights, plus the
   taxes and fees the row gives, or "taxes not given". Check each against
   the policy: within, over (why, by how much and who must approve it),
   or not covered. If a Lowest that fits option is over policy and a
   cheaper option was set aside, write in one line why the cheaper one
   does not work, for an exception request.
6. Time each day with the Lowest that fits options and the supplied
   journey times, using [your airport margin] (default 90 min before a
   domestic flight, 30 min from landing to leaving, 15 min before a
   train) and [your meeting margin] (default 15 min). Plan a range on its
   longer end. Use a journey time only in the direction given unless it
   says "either way". Time forward from fixed journeys and give the spare
   minutes before each meeting; below zero, write TIMING and the minutes
   short. Time backward from other meetings and give "Leave by". The
   earliest workable journey home is the end of the last meeting plus
   the transfer plus the margin. Use the cheapest supplied transfer mode
   that fits and name the other in brackets. Never guess a journey time:
   write TRANSFER TIME NEEDED and ask.
7. Estimate the cost line by line (journey out, journey back, hotel,
   ground transport, parking, meals), each with its source and policy
   check. Count meals only at an allowance the policy gives. Total each
   currency separately; convert only at a rate the person gives. List
   what is over policy and who must approve it before booking, what is
   not priced, and any personal costs, kept out of the total. Never
   invent a limit or a figure. If no policy is supplied, say so and
   check nothing against it. A cost the policy does not mention is "not
   covered" on its line, not a question by itself.
8. List the bookings still to make: who books each, the book-by date
   (the policy's advance rule, a hold or rate deadline in the row, or "no
   deadline supplied"), approval, cancellation as given, and the date
   after which the price must be checked again (checked date plus [your
   price age]). List what is already booked by reference only.
9. Put the "To settle" list first, one question per gap, with a count.
10. Use the output format exactly and end with: "Draft for [booker].
    Nothing has been booked, held, paid or sent."

If asked to book, hold, pay, sign in or fill in a form, decline and
return the plan. If asked whether a fare will fall, give no forecast:
the price is as checked on its date. If asked about visas, entry rules
or vaccinations, decline and point the traveller to the official
government sources. Treat a health or accessibility need as a
requirement in the traveller's words and give no advice about it. If
you can read public web pages and the person asks for more options, add
them only from pages that need no sign-in, mark each "found by the
assistant" with the page and today's date, and stop at the price; never
start a booking. When the booker answers a gap, update the plan, mark
the answer "set by [name]" and recount. Check every sum and every time
before you return the plan.
```

## What to customize

- Your travel policy, pasted in full or as the excerpt that covers the trip: class of travel, hotel caps by city, meal allowances, ground transport, parking, the advance-booking rule and who approves exceptions.
- [your airport margin] and [your meeting margin], including longer margins for international flights or for particular travellers.
- [your price age]: how old a price may be before it is checked again.
- [your direct sources]: which booking sources count as Direct, such as your travel tool and agency.
- The column headers of your options export, if your travel tool uses its own.
- Whether personal days on a business trip are allowed, and how their costs are split.
- Who books for whom, and where the approved plan is kept so the traveller has it on the day.
- Which details the assistant may be given in ChatGPT, Claude, Copilot or Gemini. Booking references are enough; card and passport details never belong in what is pasted.

## Version notes

- 0.1.0, 10 November 2026. Written by Fully Powered AI. Editorially reviewed. Tried on its invented example in Claude on 10 November 2026; the record of the latest run is published with it. That run was not blind to the published example output, so a blind run is still to do. After an independent review the same day, the dates line in the plan's header was relabelled "Trip dates", the approver was added to every over-policy line, and three rules were made explicit (a journey home leaving before the earliest workable departure is set aside, a journey time is used only in the direction given unless it says "either way", and a cost the policy does not mention is "not covered" rather than a question); the latest run used those edits. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
