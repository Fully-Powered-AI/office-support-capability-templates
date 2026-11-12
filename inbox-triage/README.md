# Inbox triage

The owner, or the assistant who keeps their inbox, starts the day knowing what needs a reply today, what can wait and until when, and what belongs to someone else, with a draft or a forwarding note for each. Nothing is sent, archived, deleted or moved, and no mailbox login is needed.

*Workflow template · Executive and office support · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflow templates/inbox-triage/)*

## The outcome

The morning begins with one page. The few messages that cannot wait until tomorrow sit at the top, each with a line on what waiting would cost and a reply already drafted the way the owner writes. Everything else has a place: a colleague who should deal with it, with a note ready to forward; a date it should be answered by; or a count of receipts, newsletters and sales pitches that need nothing at all.

Promises are on the page too: anything the owner undertook to deliver that falls due today or has already slipped, whether or not anyone has chased it.

The risky messages are kept apart. A sudden change of a supplier's bank details, a request for a login, a legal letter: each is set aside for the owner, undrafted, the sender's address checked against earlier mail, and the safe next step named. The owner makes every decision and sends every reply from their own mailbox.

## Who starts the work, and when

An executive assistant, an office manager or the owner runs it first thing in the morning, or after a day or two away, and again in the afternoon on what has arrived since. The owner reads the list, decides what the drafts leave open, and sends. Where the owner allows it, the assistant sends the approved replies and forwards the notes.

## What they supply

- **The messages:** an export from the mail program as a spreadsheet, or messages pasted in. The export needs six columns: date, sender, recipients, copies, subject and text. If the names differ, the workflow template stops and asks which is which.
- **Who is who:** whose inbox it is, the business's email domain and the colleagues' names.
- **A routing list:** which kinds of message go to which colleague, such as supplier invoices to the bookkeeper.
- **Recent promises** the owner made that may not show in the messages.
- **Two or three replies** the owner was happy with, so the drafts sound like them.

No mailbox, calendar or password is needed. Everything is handed over by a person.

## What comes out

One triage page in a fixed order:

1. **Held for the owner,** undrafted: payment and bank-detail changes, login requests, legal letters, each with the check to make.
2. **Reply today,** most costly first, each with its draft and any forwarding note.
3. **For someone else,** each with its handler and a forwarding note.
4. **Can wait,** each with a reply-by date and a draft.
5. **Already covered** by a colleague, **promises** with their status, **private** messages listed by sender only, and the **no reply needed** count.
6. **Questions** for the person who ran it, such as a message with no sender.

A draft never puts a figure, a deadline or an undertaking in the owner's mouth. Anything the owner has not yet said, and every decision that is theirs, is left as a gap in square brackets.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the assistant who keeps a director's or partner's inbox moving.
- [Leadership](https://fullypowered.ai/functions/leadership/): owners and managing directors who answer most of the firm's important mail themselves.
- [Professional services](https://fullypowered.ai/industries/professional-services/): partners whose clients expect an answer the same day.
- [Real estate](https://fullypowered.ai/industries/real-estate/): property managers fielding tenants, building owners, contractors and suppliers in one inbox.
- [Construction](https://fullypowered.ai/industries/construction/): owners juggling site problems, approvals and supplier invoices between visits.
- [Finance and investment](https://fullypowered.ai/industries/finance-and-investment/): the assistant to a partner who must keep investors, advisers and portfolio companies answered.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): where the owner is still the address everyone writes to.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): when mail grows faster than the owner's mornings.

## What has to change for your company

Write your routing list: which messages go to whom, and who covers when they are away. Decide what counts as urgent for you: your end of day, how long a reply may wait, the spending amount that needs the owner the same day, and the senders who always come first. Name the subjects that stay private. Agree whether the assistant may send replies the owner has approved, or only the owner sends. Map your mail program's export columns once. Choose the two or three replies that set the owner's voice. It runs in ChatGPT, Claude, Copilot or Gemini from an export or pasted messages; decide which mail the assistant may be given.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 10 November 2026. It was tried on its invented example in Claude on 9 November 2026, in one run by a model that had not written it, and the record of that run is published with it. Afterwards the example's drafts were corrected where they went beyond the messages, and the template was clarified on the points the run had to settle for itself, such as which of two urgent replies comes first. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on two or three past mornings whose mail the owner remembers, plus hard cases written in advance: a supplier's bank details changing from a lookalike address, a customer writing for the second time, an approval due today, a promise with no message about it, an export whose columns are named differently. The owner checks every group and every draft before anyone relies on it. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 10 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
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
- [Customer reply drafting](https://fullypowered.ai/workflow templates/customer-reply-drafting/)
- [Supplier bill review and payment-run preparation](https://fullypowered.ai/workflow templates/supplier-bill-review-and-payment-run-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
