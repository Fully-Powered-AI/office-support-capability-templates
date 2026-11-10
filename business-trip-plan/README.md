# Business trip plan

The assistant hands the traveller one plan for one business trip: dates and nights fixed from the brief, travel and hotel options with prices and the day each was checked, a day-by-day timetable around the meetings, the cost against travel policy and the bookings still to make. Nothing is booked or paid.

*Capability template · Executive and office support · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/business-trip-plan/)*

## The outcome

A trip that used to live in a dozen browser tabs and a chain of messages fits on one page. The traveller sees when they leave, where they sleep, how they get from the airport to the first meeting and how much slack each connection has. The booker sees which flight and hotel fit the meetings and the policy, what each costs, how fresh each price is, and the date each booking has to be made by.

Problems surface before money is spent: a flight that lands after the first meeting starts, a hotel priced for the wrong nights, a fare from a different airport, a room over the nightly cap. Each is set aside with its reason, or written as a question for the booker. The capability compares and times; the traveller and the booker choose, book and pay. It never fills in a booking form, holds a seat or touches a card.

## Who starts the work, and when

An executive assistant, an office manager or a team coordinator starts it as soon as the meetings for a trip are fixed, usually two to four weeks ahead. Travellers who book for themselves can run it too. It runs again when anything moves: a meeting changes, a fare goes up, the traveller adds a night. The traveller reads the plan before anything is booked, and anything over policy goes to the person who approves exceptions.

## What they supply

- **The traveller's brief.** Who is travelling, where, the dates out and back, the airport or station they leave from, the fixed meetings with times and places, and anything they need, such as a hotel within walking distance.
- **The options found.** Flights, trains and hotels, pasted from the airline's or hotel's own site, the company travel tool, an agency quote or another site, each with its price and the day it was checked.
- **Journey times.** From the airport to the first meeting and between each place, as the traveller's maps app gives them.
- **The travel policy,** or the part of it that covers this trip: class of travel, the hotel cap, meal allowances, how far ahead to book, and who approves an exception.
- **Anything already booked,** by reference only. No card numbers and no passport details.

## What comes out

1. **The trip dates.** Dates out and back, each night and where it is spent, and the airport the trip starts from.
2. **A shortlist.** For the journey out, the journey back and the hotel: the lowest-priced option that fits the meetings and the traveller's needs, one alternative, and every option left out with the reason.
3. **The day-by-day timetable.** Every leg, transfer and meeting, with the time to leave and the spare minutes before each meeting.
4. **The cost estimate.** Each line against the policy, the total, what is over policy and who must approve it, and what has not been priced.
5. **The bookings still to make.** Who books each one, the date it must be booked by and when its price should be checked again.

A good plan lets the traveller get through the trip without opening another document, and every price in it can be traced to where it was found and when.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the assistant who arranges travel for one leader or for a whole team.
- [Sales](https://fullypowered.ai/functions/sales/): client visits and sales trips, where a missed first meeting costs more than the fare.
- [Professional services](https://fullypowered.ai/industries/professional-services/): consultants and partners on site with clients, with the trip often charged back to the client.
- [Engineering firms](https://fullypowered.ai/industries/engineering-firms/): site visits and project meetings far from the office.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/): plant visits, supplier audits and customer reviews.
- [Software technology](https://fullypowered.ai/industries/software-technology/): customer workshops, partner meetings and conference trips.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): a travel policy already exists and every trip should be checked against it the same way.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): more people travel than one office manager can plan by hand.

## What has to change for your company

Paste in your own travel policy; the capability invents no limits of its own and checks nothing against a policy it has not been given. Set the margins your travellers want: how early to be at the airport, how long to allow after landing and how early to arrive at a meeting. Decide how old a price may be before it has to be checked again. Name who books, who approves an exception and where the approved plan is kept. Agree which booking sources count as direct. It runs in ChatGPT, Claude, Copilot or Gemini from what you paste in, and needs no connection to a travel tool, a booking site or a card.

## What has been checked

Fully Powered AI wrote this capability template. It was editorially reviewed on 10 November 2026. It was tried on its invented example in Claude on 10 November 2026; the record of the latest run is published with it and lists the ambiguities it met. The record says plainly that the run was not blind to the published example output, so a blind run is still to do. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on two or three past trips whose bookings you already know, plus hard cases written in advance: a flight that lands after the first meeting, a hotel quoted for the wrong nights, a fare from another airport, a room over the cap, a journey time nobody supplied. The booker checks every time and figure before anyone relies on the plan. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete capability template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the capability drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related capabilities

- [Meeting agenda, notes and follow-ups](../meeting-agenda-notes-and-follow-ups/)
- [Event plan](https://fullypowered.ai/capabilities/event-plan/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
