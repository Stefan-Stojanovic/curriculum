---
author: Stefan-Stojanovic

type: normal

category: must-know

practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Reliability Tradeoffs

---
## Content

AI reliability is rarely one dial called "better."

For the customer-escalation summary feature, a larger model might produce stronger summaries, but it may also increase latency and cost. A stricter prompt might reduce risky claims, but it may omit useful detail. Human review may catch mistakes, but it adds operational load.

Engineers usually balance several constraints:

- **capability**: can the system perform the task well enough?
- **cost**: can the feature run at expected volume?
- **latency**: is the response fast enough for the workflow?
- **variance**: how much does quality change across cases?
- **failure impact**: what happens when the system is wrong?

These are system design tradeoffs, not prompt cleverness contests.

A low-impact internal draft can tolerate more variance. A customer-visible action, billing decision, security alert, incident update, or irreversible workflow step needs a higher quality bar and stronger controls.

The practical question is: what level of AI autonomy matches the evidence and the cost of being wrong?

---
## Practice

High-impact customer-visible actions need stronger ??? than internal drafts.

- controls
- colors
- slogans
