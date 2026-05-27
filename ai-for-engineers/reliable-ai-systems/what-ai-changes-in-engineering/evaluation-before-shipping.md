---
author: enki-ai

type: normal

category: must-know

practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Evaluation Before Shipping

---
## Content

A demo asks:

> Can this work once?

An eval asks:

> Does this work well enough on the cases we expect, including the cases most likely to hurt us?

Before shipping an AI feature, define the evidence you need. For a support-summary system, that might include:

- sample tickets from real traffic;
- expected summaries for common and difficult cases;
- checks for invented facts;
- checks for missing critical details;
- thresholds for acceptable quality;
- examples that must trigger review or fallback.

Evals do not make AI perfectly predictable. They make the risk visible enough for engineering judgment.

Without evals, teams argue from anecdotes: one impressive demo, one embarrassing failure, or whichever example someone saw last.

---
## Practice

An eval helps a team move from "it worked on my example" to "we have ??? that it is good enough."

- evidence
- excitement
- access
- permission

---
## Revision

Evals should include expected cases and risky cases, not only the clean examples used in a ???.

- demo
- database
- cache
- sprint
