---
author: Stefan-Stojanovic

type: normal

category: caveat

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Failure Modes And Guardrails

---
## Content

AI systems often fail in ways that look plausible at first glance.

For the support-summary feature, common failure modes include:

- hallucinated facts that were not in the ticket;
- missing context from an earlier message;
- overconfident summaries of ambiguous requests;
- policy violations, such as promising a refund;
- unsafe automation, such as closing a case without review;
- unstable output across similar inputs.

Guardrails are the controls around that behavior.

Some guardrails constrain the input or output. Others change the workflow. A reliable system might require structured output, block policy-sensitive claims, route low-confidence cases to a human, log model inputs and outputs, monitor complaint patterns, or fall back to a shorter extractive summary when context is thin.

The important point is that guardrails should match the risk. A typo in a low-stakes draft may need little control. A wrong summary that triggers a customer-facing action may need review, escalation, and auditability.

---
## Revision

Guardrails should match the ??? of the AI system's failure.

- risk
- filename
- sprint length
