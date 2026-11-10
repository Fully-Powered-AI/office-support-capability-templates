# Meeting agenda, notes and follow-ups

Whoever runs the meeting walks in with an agenda where every topic has an outcome and a time, and walks out with a one-page record: what was decided, who owns each action and by when, and what is still open. Nothing reaches anyone until that person has read it and sends it.

*Capability template · Executive and office support · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/meeting-agenda-notes-and-follow-ups/)*

## The outcome

Every meeting you run ends in decisions and owners, on one page, the same day. People arrive knowing what will be decided and what to read first. They leave with their own actions in writing, each with a date. Next week’s meeting opens on what was promised, so nothing is discussed twice.

The record is not a transcript. It leaves out who argued what and keeps what the room settled. Where the notes show an action with no owner, two owners or no date, the capability says so and asks you. It never picks a name or a date for you, and it never sends, invites or updates anything.

## Who starts the work, and when

The person who runs the meeting starts it: a team lead, a project manager, an office manager, a chief of staff or an owner. They run it twice. The first time is a day or two before the meeting, with the topics. The second is straight after, with the notes, while everyone still remembers what they agreed to.

An executive assistant or coordinator can run it for them. The person who ran the meeting still reads the record and sends it.

## What they supply

- **Before the meeting:** the meeting’s name, date, start time and length; who is coming; the topics, each with who leads it and roughly how long it needs; and the actions still open from last time.
- **After the meeting:** the notes, typed or pasted in whatever shape they were taken, from one note-taker or several.
- **Once:** how long before a meeting reading goes out, and who receives the follow-up.

No calendar, mailbox or meeting tool is connected. Everything is pasted in by a person.

## What comes out

1.  **A draft agenda.** Decisions first, a time for every topic, reading to do beforehand, last time’s open actions and five minutes at the end to read every action back. If the topics do not fit the time, it says by how much and proposes the smallest change.
2.  **A meeting record.** Decisions, actions with one owner and a date each, parked items with what brings them back, open questions, and where last time’s actions stand.
3.  **A list of what to settle.** Every gap in the notes, as a question for the person who ran the meeting.
4.  **A follow-up draft.** One message for everyone invited, marked not ready while any gap is open.

A good record can be read in two minutes by someone who was not there, and every line in it traces to the notes.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the leadership meeting, the staff meeting and every meeting an assistant prepares for someone else.
- [Project and delivery](https://fullypowered.ai/functions/project-and-delivery/): the weekly project meeting, where an action without an owner becomes a late milestone.
- [Professional services](https://fullypowered.ai/industries/professional-services/): internal team and practice meetings, where senior time is the most expensive thing in the room.
- [Construction](https://fullypowered.ai/industries/construction/): the weekly operations or site coordination meeting, with trades, dates and equipment that depend on each other.
- [Software technology](https://fullypowered.ai/industries/software-technology/): planning and review meetings that end with a clear list of who does what.
- [Nonprofits](https://fullypowered.ai/industries/nonprofits/): staff and committee meetings where volunteers need their actions in writing.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): standing meetings that have run for years and deserve a sharper shape.

## What has to change for your company

Decide which meetings use it first; a weekly meeting with the same people is the best start. Set how far ahead reading goes out and how long the closing read-back takes. Agree who receives the follow-up, including people who were invited and absent. Name the subjects that stay out of a circulated record, such as an individual’s pay, performance or health. Choose where the record is kept so next week’s agenda can pick up the open actions. It runs in ChatGPT, Claude, Copilot or Gemini; decide which notes the assistant may be given.

## What has been checked

Fully Powered AI wrote this capability template. It was editorially reviewed on 9 November 2026. It was tried on its invented example in Claude on 9 November 2026, in two runs; the instructions were corrected between them, and the record of the second run is published with the template. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on the notes of three or four past meetings whose outcomes you already know, plus hard cases written in advance: an action nobody took, a topic that was talked about and not decided, two note-takers who disagree, an agenda that does not fit its time. The person who ran each meeting checks every decision and owner against what happened. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
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

- [Client-status update preparation](https://fullypowered.ai/capabilities/client-status-update-preparation/)
- [Weekly receivables summary](https://fullypowered.ai/capabilities/weekly-receivables-summary/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
