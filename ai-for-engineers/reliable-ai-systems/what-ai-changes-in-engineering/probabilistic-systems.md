---
author: Stefan-Stojanovic

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

# Probabilistic Systems

---
## Content

Imagine a support-summary feature.

In a demo, it looks strong. A long customer thread goes in. The model returns a short summary with the customer's issue, the attempted fixes, and a suggested next step.

Then production traffic arrives.

Users paste messy logs, partial conversations, screenshots transcribed badly, angry messages, old ticket history, and private notes. Most summaries may still be useful. One confident wrong summary, though, can send support down the wrong path or misstate what the customer was promised.

That is the shift AI brings into engineering: useful behavior with variable output.

Traditional code can still fail, but its behavior is usually bounded by explicit branches. AI behavior depends on inputs, model behavior, context quality, prompt design, retrieval, and sampling. Similar inputs can produce different wording, different emphasis, or different mistakes.

You do not solve this by hoping the model is smart enough. You engineer the surrounding system so variable behavior has limits, evidence, and recovery paths.

---
## Practice

An AI support-summary feature can be useful in production, but engineers must account for ??? output.

- variable
- compiled
- encrypted

---
## Revision

A polished AI demo is not enough evidence for production because real inputs are more ??? than demo inputs.

- varied
- scripted
- deterministic
