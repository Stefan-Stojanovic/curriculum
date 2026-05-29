---
author: Stefan-Stojanovic

type: normal

category: caveats

practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Failure Modes And Guardrails

---
## Content

Once you know what the AI feature should do, ask how it can fail.

Common AI failure modes include hallucinated facts, missing context, policy violations, unsafe automation, overconfident summaries, and unstable output across similar inputs.

For the customer-escalation summary feature, a hallucinated fact might say the customer already tried a fix they never mentioned. Missing context might ignore that the customer is asking about billing, not product behavior. Unsafe automation might page engineering for a case that should stay in support.

Guardrails are controls that reduce the chance or impact of those failures.

They can include prompt constraints, checks against required source fields, fallback behavior, human review, logging, monitoring, and escalation.

A guardrail is not decoration. It should be tied to a specific failure mode and a specific consequence.

For example, if the summary lacks source evidence for a root cause, the system should not invent one. It might mark the root cause as unknown, route the case for review, or ask for more context before escalation.

---
## Practice

A useful guardrail connects a failure ??? to a concrete consequence.

- mode
- menu
- slogan

---
## Revision

When source context is missing, safer systems use fallback behavior or human ??? before action.

- review
- celebration
- compression
