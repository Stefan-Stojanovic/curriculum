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

# Reliability Tradeoffs

---
## Content

AI reliability is a system design problem, not a prompt cleverness contest.

When you add model behavior to a product, you usually trade among:

- **capability**: can the model handle the task?
- **cost**: what does each call add at expected volume?
- **latency**: can users or downstream systems wait?
- **variance**: how stable is output across similar inputs?
- **review effort**: who checks uncertain or high-impact output?
- **failure impact**: what happens when the output is wrong?

A stronger model might reduce missed details but increase cost and latency. A cheaper model might be fine for internal drafts but risky for customer-visible decisions. Human review can improve quality but slow the workflow.

The engineering move is to match the control level to the consequence of failure.

---
## Practice

For AI systems, a larger model may improve capability while increasing cost and ???.

- latency
- determinism
- file size
- syntax

---
## Revision

Review effort, fallback behavior, and escalation should increase when the failure impact is ???.

- higher
- prettier
- hidden
- random
