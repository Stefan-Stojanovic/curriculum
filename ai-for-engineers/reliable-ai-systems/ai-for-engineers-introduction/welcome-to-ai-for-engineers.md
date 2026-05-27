---
author: Stefan-Stojanovic

type: normal

category: must-know

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Welcome to AI For Engineers

---
## Content

AI For Engineers is about building and operating AI-powered systems, not just using AI tools.

In normal software, a function should usually return the same output for the same input. With generative AI, the behavior can vary. The model may handle an ambiguous request well, miss context, invent a detail, or respond differently after a small input change.

That does not make AI unusable. It means reliability has to be designed around the model instead of assumed from the code path.

In this course, you will practice thinking about AI features as production systems with:

- clear specs for acceptable output;
- evals that measure behavior before release;
- cost and latency constraints;
- guardrails for risky cases;
- logs, monitoring, and escalation paths;
- human review where automation should not act alone.

The goal is practical judgment: know what AI can safely do, what evidence you need before shipping, and where the system should slow down or ask for help.

---
## Revision

AI-powered systems need different reliability habits because model behavior can be ???, not fully deterministic.

- probabilistic
- compiled
- cached
