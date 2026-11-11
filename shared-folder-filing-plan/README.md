# Shared folder filing plan

The office coordinator gets a plan for tidying a shared folder: a proposed folder structure, every file's move with its owner named, and the duplicates and access questions to settle first. Owners approve their own moves; nothing is moved, renamed or deleted.

*Capability template · Executive and office support · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/shared-folder-filing-plan/)*

## The outcome

Tidying a shared folder usually stalls on the same few worries: whose file is this, will moving it lock somebody out, is there already a copy somewhere. This capability puts those worries on one page before anybody touches a file. You get the folder structure your own filing conventions imply, a list of moves with each document's owner named beside it, and a short list of questions, each addressed to one person.

Moves that are clear are marked ready for the owner to approve. Moves that are not are held, with the reason and the question that releases them: no owner recorded, a link that anyone could be using, a file whose current sharing does not match its new folder, a record your conventions say must not move without a named person's confirmation. Files that look like copies of each other are never decided for you. Both go to their owners.

The plan never opens a file, never guesses an owner and never invents a folder your conventions do not name. A file that no rule covers is listed as such, so the rule can be added or the file placed by a person.

## Who starts the work, and when

The office manager, office coordinator or executive assistant starts it when a shared folder has grown past what anyone can find things in, before a move to a new drive, or as a yearly tidy. The coordinator reviews the plan first and sends it on. Each document's owner approves the moves of their own documents. Whoever holds a restricted category of record confirms those moves too.

## What they supply

- **The folder inventory:** an export of the folder you are authorized to see, one row per file, with its path, name, size, last modified date, owner, who it is shared with and whether it is shared by link. If the columns are named differently, the assistant stops and asks.
- **Your filing conventions:** the destination folders and who may see each, numbered filing rules, and any restricted records with the person who confirms their moves.
- **The settings:** the folder being tidied, today's date and the coordinator.

Nothing is connected to your drive. Everything is pasted or attached by a person, and the assistant works from names and dates in the export, never from what is inside the files.

## What comes out

One filing plan for the coordinator, in a fixed order: the proposed folder structure with file counts; the list of moves, each with its rule, owner, approver and status; the ready moves grouped by owner; the files that stay where they are; the duplicates to resolve; the files no rule covers; and a numbered list of questions. The counts add up to the rows supplied, and the plan says so. It ends by stating that nothing has been moved, renamed, deleted or re-shared.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the coordinator who is asked to sort out the shared drive and wants owners, not guesses, deciding what moves.
- [Professional services](https://fullypowered.ai/industries/professional-services/): client and internal folders that have grown side by side for years.
- [Engineering firms](https://fullypowered.ai/industries/engineering-firms/): project folders, safety documents and supplier papers that belong in different places with different audiences.
- [Nonprofits](https://fullypowered.ai/industries/nonprofits/): shared folders passed between staff and volunteers, where nobody remembers who owns what.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): a drive that has outlived several office managers and several naming habits.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): the point where the founders' folder structure no longer holds a team.

## What has to change for your company

Write down your own folder structure and filing rules before the first run; the capability adds none of its own. Decide who may see each destination folder and write the groups exactly as they appear in your drive's sharing list, because they are compared word for word. Name the restricted records and who confirms their moves. Choose the age after which untouched files go to an archive folder, and the order of the rules, since the first match wins. It is written to run in ChatGPT, Claude, Copilot or Gemini, from an export you supply; it needs no connection to your drive.

## What has been checked

Fully Powered AI wrote this capability template. It was editorially reviewed on 10 November 2026. It was tried once on its invented example, in Claude on 10 November 2026; that run was not fully blind, because the example's published output was in view, and the published trial record says so. It has not yet been tested in a client environment or as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on one real folder you already understand, plus hard cases written in advance: a file with no owner, two files with the same name and size, a file shared by link, a file shared with a group that its new folder does not include, a record in a restricted category. The coordinator checks every proposed destination and every owner against the rules before anyone relies on the plan. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Staff newsletter and FAQ roundup](../staff-newsletter-and-faq-roundup/)
- [Departing-employee knowledge capture](https://fullypowered.ai/capabilities/departing-employee-knowledge-capture/)
- [Decision log](../decision-log/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
