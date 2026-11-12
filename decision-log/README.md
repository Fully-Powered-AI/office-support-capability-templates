# Decision log

Your chief of staff keeps one register of what the leadership actually approved, across every meeting and message: each decision with who approved it, each action with one owner and a date, what is overdue, and a flag wherever a new decision clashes with an earlier one or revives a rejected idea.

*Workflow template · Executive and office support · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/decision-log/)*

## The outcome

Everyone can see what the leadership settled, and only that. One register holds every approved decision with its date, its approver, the reason given and the options turned down, and every action that follows from it, each with one owner and one date. A conversation that sounded like agreement never becomes a decision by accident: anything that was only discussed stays out, listed apart, until an approver says yes.

The register checks itself as it grows. When a new decision cuts across one already in force, brings back an idea the leadership turned down, or hands the same work to a second person, the workflow template flags it with the earlier entry beside it and the choices open. Overdue actions and reviews coming due are on the same page every week. The person who keeps the register approves every entry and makes every change; the AI assistant enters nothing and sends nothing.

## Who starts the work, and when

The person who keeps the register starts it: a chief of staff, an executive assistant, an office manager or a company secretary. A company secretary can keep it as a working register of what was approved; minutes that must follow a set form and be formally adopted stay where they are, and this register does not replace them. The register keeper runs it after each leadership meeting, whenever a decision is approved between meetings by email or on paper, and once a week to see what is overdue and what comes due next.

The approvers, usually the chief executive and anyone with a delegated limit, settle the flags about their own decisions. The register keeper takes those questions to them.

## What they supply

- **The register so far,** as two spreadsheet exports, one of decisions and one of actions, or nothing at all to start a new one. The default column headers are set out in the template; if a header differs, the assistant stops and asks.
- **The new material:** approved meeting records, approvers' emails and signed papers, each showing who approved what and when.
- **Status updates** from action owners, each with who reported it and when.
- **Once:** the company or team the register is for, who may approve which kinds of decision, how far ahead to look for actions coming due, and which subjects stay out of the register.

No mailbox, calendar or drive is connected. Everything is pasted in by a person.

## What comes out

1. **Proposed entries,** one decision each, with the approver, the date, the reason given, the options turned down, the review date and the actions.
2. **Flags** for a contradiction, a revived proposal, the same work under two owners, or an approver outside their limit, each with the earlier entry and the choices.
3. **What was not entered,** because it was only discussed, with who would have to approve it.
4. **Status changes, overdue actions, and actions and reviews coming due.**
5. **The register changes to make,** each with the question it waits on.

Every open question comes first, written for the register keeper to take to the approver. A good update can be checked against its sources in a few minutes, and nobody finds a decision in the register they did not make.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the chief of staff or executive assistant who is asked, every week, "did we decide that?"
- [Leadership](https://fullypowered.ai/functions/leadership/): a leadership team that approves decisions in meetings, emails and papers and wants one place that says what stands.
- [Professional services](https://fullypowered.ai/industries/professional-services/): a partners' or management group whose decisions on pricing, terms and staffing need to hold from one month to the next.
- [Software technology](https://fullypowered.ai/industries/software-technology/): leadership teams that move fast and revisit the same choices more often than they mean to.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/): decisions on shifts, capacity, pricing and suppliers that run for months and touch each other.
- [Nonprofits](https://fullypowered.ai/industries/nonprofits/): a leadership team and its committees, where a decision taken in one room has to be known in another.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): the point where decisions outnumber the people who remember them.
- [Private equity & portfolios](https://fullypowered.ai/situations/private-equity-and-portfolios/): a portfolio company whose owners expect a clear account of what the leadership approved and what is being done about it.

## What has to change for your company

Name who keeps the register and who may approve which kinds of decision, with any spending or scope limit. Decide what counts as approval in your company: a mark in the meeting record, an email from the approver, a signed paper. Set how far ahead to look for actions coming due and how often the overdue list is run. Name the subjects that stay out of the register, such as one person's pay or performance, and where those are kept instead. Keep the default columns or tell the assistant yours. Agree where the register lives and who may read it. It runs in ChatGPT, Claude, Copilot or Gemini; decide which papers and messages the assistant may be given.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 10 November 2026. It was tried once on its invented example in Claude on 10 November 2026, and the record of that run is published with it. The run produced every part of the update, and the path that keeps an item about one person's pay out of the register was reached; none of the stop conditions was, and the eleven acceptance tests in the template were not run. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on two or three months of past leadership material whose decisions you already know, plus hard cases written in advance: an agreement with no approver named, a new decision that reverses an earlier one, an idea the leadership turned down coming back in different words, the same work given to two people, a register export with different column names. The register keeper checks every entry against its source before anything is entered. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 10 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Meeting agenda, notes and follow-ups](../meeting-agenda-notes-and-follow-ups/)
- [Internal change announcement](https://fullypowered.ai/workflows/internal-change-announcement/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
