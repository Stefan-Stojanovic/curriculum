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

Start with the first reliability decision: deciding whether a good AI demo is ready for production.

Imagine your team demos a customer-escalation summary feature.

A customer writes a long, messy ticket thread. The AI produces a short escalation summary for the engineer who may need to investigate. In the demo, it works well: the summary is readable, the tone is professional, and the important details are present.

That demo is useful evidence, but it is not enough evidence to ship.

Production inputs are messier:

- users paste partial logs, screenshots, quoted emails, and angry follow-ups
- tickets mix billing, technical, account, and deployment details
- the model may confidently summarize something that was never confirmed
- one bad summary can send the on-call engineer down the wrong path

This is the key shift: an AI feature can be impressive and still be probabilistic.

Probabilistic means the behavior is based on learned patterns and context, not a fixed rule for every possible input. Similar inputs can produce slightly different outputs. Unusual inputs can produce confident mistakes.

Engineers do not solve this by hoping the prompt is good enough. They design the surrounding system: specs, evals, constraints, fallback behavior, review, logging, and monitoring.

---
## Revision

A customer-escalation summary demo is not enough to ship because production inputs are messier and AI behavior is ???.

- probabilistic
- compiled
- encrypted
