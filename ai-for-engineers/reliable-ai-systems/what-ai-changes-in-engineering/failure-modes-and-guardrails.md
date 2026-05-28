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

Common AI failure modes include:

- hallucinated facts
- missing context
- policy violations
- unsafe automation
- overconfident summaries

For the customer-escalation summary feature, a hallucinated fact might say the customer already tried a fix they never mentioned. Missing context might ignore that the customer is asking about billing, not product behavior. Unsafe automation might page an engineering team for a case that should stay in support.

Guardrails are controls that reduce the chance or impact of those failures.

They can include:

- constraints in the prompt or system instructions
- checks against required source fields
- fallback behavior when inputs are incomplete
- human review for high-impact cases
- logging of inputs, outputs, model versions, prompts, and decisions
- escalation when confidence is low or policy risk is high

Monitoring for drift, complaints, or unusual failure patterns can show whether those guardrails are still working after release.

A guardrail is not decoration. It should be tied to a specific failure mode and a specific consequence.

---
## Practice

A useful guardrail should connect to a specific failure ??? and consequence.

- mode
- menu
- slogan

---
## Revision

If a customer-escalation summary lacks enough source context, a safer system may trigger fallback behavior or human ???.

- review
- celebration
- compression
