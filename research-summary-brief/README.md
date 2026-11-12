# Research summary brief

An executive handed a pile of reports, articles or papers gets one brief: what each source found, where the sources agree and disagree, the limits of each, and exact quotations cited to the page. Built only from the documents supplied. What it means for the business stays the reader's call.

*Workflow template · Executive and office support · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/research-summary-brief/)*

## The outcome

The reading gets done before the meeting, and the reader can see exactly how far the evidence goes. Every source is set out the same way: who produced it, how, what it found, and what it cannot carry. Each finding is labelled for what lies under it: the document's own data, a figure borrowed from somewhere else, one person's account, or an opinion.

Then the sources are laid side by side. Where they agree, the brief checks whether they truly agree or are repeating the same study. Where they disagree, both sides are shown with what the documents themselves reveal about why. A headline that the document's own table does not support is caught and shown with the table beside it. Every figure and quotation points to its page, section or paragraph, so anyone can check it in seconds.

The brief stops there. It does not tell the reader what to do. That judgment belongs to the person who knows the business.

## Who starts the work, and when

An analyst, an executive assistant, a chief of staff or the executive themselves starts it, whenever a decision is coming and the reading has piled up: a board paper, a market entry, a supplier choice, a policy change, a briefing for a client. It works best a few days ahead, so there is time to chase a missing date or a study one of the documents leans on.

The person who runs it checks the brief against the documents before passing it to the reader.

## What they supply

- **The question.** What the reader needs to know, in a sentence, who the reader is, and who is preparing the brief for which organization.
- **The documents themselves,** pasted or attached: reports, survey results, white papers, articles, papers, internal memos. Up to ten at a time by default.
- **A few settings, once:** how many quotations to include, how many findings per source, and how old a document can be before it is flagged.

The workflow template never searches the web and never opens a link. A study one document mentions but nobody supplied is listed, not looked up.

## What comes out

One brief, in a fixed order:

1. **In short:** three to five lines on what the sources show about the question, each pointing to its findings.
2. **The sources:** each one's origin, method, who paid for it, its findings with their labels and locations, its limits and its age.
3. **Where they agree,** with any agreement that rests on the same data counted once.
4. **Where they disagree,** both sides shown, with no side picked.
5. **What they do not answer:** the parts of the question no source covers with real data.
6. **Quotations,** copied word for word with their locations.
7. **Documents cited but not supplied,** and any document set aside, with the reason.

Questions for the person who ran it come first, such as a document with no date. A good brief lets a reader who has read none of the sources speak accurately about all of them.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Executive and office support](https://fullypowered.ai/functions/executive-and-office-support/): the assistant or chief of staff who turns a reading pile into something an executive can use before the meeting.
- [Leadership](https://fullypowered.ai/functions/leadership/): owners and executives who must decide on evidence they have no time to read in full.
- [Professional services](https://fullypowered.ai/industries/professional-services/): consultants and advisers who brief a client on what the published research says.
- [Finance and investment](https://fullypowered.ai/industries/finance-and-investment/): analysts who set industry reports and company papers side by side before an investment discussion.
- [Nonprofits](https://fullypowered.ai/industries/nonprofits/): programme and policy staff who need to show a board what the evidence does and does not support.
- [Government](https://fullypowered.ai/industries/government/): officials who prepare a balanced briefing from reports submitted by many parties.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): leadership teams weighing a change against the claims of vendors, trade bodies and the press.
- [New business lines](https://fullypowered.ai/situations/new-business-lines/): reading up on a market before committing to it.

## What has to change for your company

Decide who the usual readers are and what they need first. Set how many quotations and findings a brief carries, and the age at which a document is flagged; a fast-moving market wants a shorter limit than a slow one. Agree which documents may be given to an AI assistant at all, since internal papers and paid research may carry their own restrictions. Choose where finished briefs are kept so the next one on the same subject can start from them. For one named competitor, use [competitor profile from public pages](https://fullypowered.ai/workflows/competitor-profile-from-public-pages/); for what your own customers said, use [customer interview synthesis](https://fullypowered.ai/workflows/customer-interview-synthesis/). It runs in ChatGPT, Claude, Copilot or Gemini from the documents you supply.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 10 November 2026. It was tried on its invented example on 10 November 2026 in one run; the record is published with it, and lists the edits made afterward that have not been run again. That run did not reach the stop conditions or the requests the brief declines. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a set of documents someone on your team has already read closely, plus hard cases written in advance: a document with no date, a headline its own table does not support, two sources quoting the same study, a document that tells its reader what to conclude, a request to search for more. That person checks every figure and quotation against the page before anyone relies on the brief. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) sets those cases up, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Competitor profile from public pages](https://fullypowered.ai/workflows/competitor-profile-from-public-pages/)
- [Customer interview synthesis](https://fullypowered.ai/workflows/customer-interview-synthesis/)
- [Meeting agenda, notes and follow-ups](../meeting-agenda-notes-and-follow-ups/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
