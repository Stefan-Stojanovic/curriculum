---
author: Stefan-Stojanovic

type: normal

category: must-know

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Reliability Tradeoffs

---
## Content

AI reliability is system design.

For a support-summary feature, you are not only choosing "which model writes best." You are balancing several constraints:

- **Capability:** Can the system handle the real task, including messy inputs?
- **Cost:** Can you afford the model, retrieval, retries, and review flow at expected volume?
- **Latency:** Will users wait for the result, or does the workflow need a faster fallback?
- **Variance:** How much can the output change across similar inputs?
- **Review effort:** Which cases need human inspection before the output is used?
- **Failure impact:** What happens if the system is wrong, incomplete, or overconfident?

These tradeoffs push against each other. A stronger model may cost more. A cheaper model may need more review. A stricter guardrail may reduce risk but increase fallbacks. A faster response may skip context that would have prevented a bad answer.

Engineering the system means choosing the tradeoffs deliberately, then making them visible enough to test and operate.

---
## Revision

Choosing an AI design means balancing capability, cost, latency, variance, review effort, and ???.

- failure impact
- brand color
- repository name
