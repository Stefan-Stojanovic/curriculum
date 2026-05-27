---
author: Stefan-Stojanovic
type: normal
category: discussion
practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Choose Your System Risk

---
## Content

Pick one AI-powered feature or workflow you might build, review, or operate.

It does not need to be ambitious. A useful example could be:

- summarizing customer tickets;
- classifying inbound support requests;
- drafting release notes from merged pull requests;
- extracting fields from invoices;
- suggesting incident-response next steps.

Now write a short risk brief for that system:

1. **Intended output:** What should the AI produce?
2. **Likely failure:** What could go wrong in a way that matters?
3. **Evidence of quality:** What eval, sample, or acceptance criteria would show it is good enough?
4. **Review or fallback trigger:** When should a human review, the system refuse, or a safer path take over?

For example:

> Intended output: summarize a support ticket for the next agent.
>
> Likely failure: the summary invents a promise the company never made.
>
> Evidence of quality: eval cases with messy notes, conflicting details, and expected summaries checked against source text.
>
> Review or fallback trigger: any billing, legal, account-deletion, or conflicting-source case requires human review.

If you want to pressure-test your brief, post it in the comments and ask Enki AI what risk or guardrail you may be missing.

---
## Practice

For an AI feature, the review or fallback trigger should describe when a human reviews, the system refuses, or a safer path ???.

- takes over
- disappears
- rewrites history

---
## Revision

Before shipping an AI-powered workflow, name the intended output, likely failure, evidence of quality, and review or ??? trigger.

- fallback
- decoration
- marketing
