---
author: enki-ai

type: normal

category: caveat

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

AI failures are not always loud.

A system may return an answer that is confident, formatted correctly, and still wrong. Common failure modes include:

- hallucinated facts;
- missing context;
- policy violations;
- unsafe automation;
- overconfident summaries;
- unstable output across similar inputs.

Guardrails reduce the blast radius when these failures appear.

Useful guardrails can include structured output, constrained inputs, retrieval limits, human review, fallback behavior, logging, monitoring, and escalation.

The point is not to wrap every AI feature in every control. The point is to choose controls that match the system's risk.

---
## Practice

A guardrail is most useful when it reduces the ??? of a likely or high-impact failure.

- blast radius
- font size
- sprint count
- prompt length

---
## Revision

Human review, fallback behavior, logging, and escalation are examples of AI system ???.

- guardrails
- demos
- tokens
- benchmarks
