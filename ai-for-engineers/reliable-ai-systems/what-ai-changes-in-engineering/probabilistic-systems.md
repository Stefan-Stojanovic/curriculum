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

Start with a common release mistake: treating a good AI demo as proof that the feature is ready for production.

Imagine your team demos a customer-escalation summary feature. A customer writes a long support thread. The AI produces a short summary for the engineer who may need to investigate. In the demo, it works well: the summary is readable, professional, and mostly complete.

That demo is useful evidence, but it is not enough evidence to ship.

Production inputs are messier. Users paste partial logs, quoted emails, screenshots, angry follow-ups, and details from several products. A model may confidently summarize something that was never confirmed. One wrong summary can send the on-call engineer down the wrong path.

This is the key shift: an AI feature can be impressive and still be probabilistic.

Probabilistic means the behavior is based on learned patterns and context, not a fixed rule for every possible input. Similar inputs can produce slightly different outputs. Unusual inputs can produce confident mistakes.

Engineers do not solve this by hoping the prompt is good enough. They design the surrounding system: specs, evals, constraints, fallback behavior, review, logging, and monitoring.

---
## Revision

A good demo is not enough because production inputs vary and AI behavior can be ??? across cases.

- probabilistic
- compiled
- encrypted
