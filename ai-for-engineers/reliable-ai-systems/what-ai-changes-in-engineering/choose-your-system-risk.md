---
author: enki-ai

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

Pick one AI-powered feature or workflow you might ship, review, or operate.

Use this structure:

- **Intended output**: what should the AI produce?
- **Failure**: what wrong output would matter?
- **Evidence**: what would prove the behavior is good enough?
- **Review or fallback trigger**: when should the system stop, escalate, or ask a human?

For example:

> Intended output: summarize support tickets for agents.
>
> Failure: omit a billing dispute or invent a refund promise.
>
> Evidence: evals pass on real ticket samples, including angry customers and multi-issue threads.
>
> Review or fallback trigger: route summaries to human review when the ticket mentions refunds, legal threats, or account closure.

If you want help pressure-testing your answer, ask Enki AI in the comments to challenge the risk and suggest one missing guardrail.

---
## Practice

For a production AI feature, the review or fallback trigger should be based on the feature's ???.

- risk
- name
- color
- popularity

---
## Revision

Before shipping an AI-powered workflow, engineers should define intended output, failure, evidence, and a review or ??? trigger.

- fallback
- marketing
- install
- hiring
