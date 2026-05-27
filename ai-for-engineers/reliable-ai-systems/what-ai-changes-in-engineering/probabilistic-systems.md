---
author: Stefan-Stojanovic
type: normal
category: must-know
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Probabilistic Systems

---
## Content

Imagine a support-summary feature.

In a demo, it looks strong. You paste five clean tickets. The model identifies the customer issue, summarizes the recent history, and suggests a reasonable next step. The team can immediately see the value.

Production inputs are not that clean.

Users paste partial notes. One ticket contains two unrelated problems. Account data is stale. A customer writes in a style your test examples did not cover. A support agent adds an internal shortcut that the model interprets literally.

The feature may still be worth building. But the engineering problem has changed.

With deterministic code, you can often reason from a rule to an expected output. With AI behavior, you also need to reason from a distribution of possible outputs to an acceptable operating range. The system might be right often, wrong confidently, or useful only when the input stays inside a known boundary.

That is the core shift: a promising demo is evidence, but it is not production readiness.

Production readiness needs a clearer answer to questions like:

- Which inputs are in scope?
- What does a good output have to include or avoid?
- How often can the system be wrong before the feature becomes unsafe or too expensive?
- What happens when the model produces a plausible but harmful answer?

AI changes engineering because behavior quality becomes something you measure, constrain, and monitor. You do not just call a model. You design the system around the model's variance.

---
## Revision

A promising AI demo is useful evidence, but production readiness also requires measuring and constraining the model's ???.

- variance
- file size
- brand color
