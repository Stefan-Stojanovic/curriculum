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

AI reliability is a system-design problem.

The question is rarely "Can the model do this at all?" A better question is:

> Can this system do the job well enough, often enough, at the right cost and latency, with the right controls around failure?

Engineers usually have to balance several constraints:

- **Capability:** Can the model handle the task and domain?
- **Cost:** Can the product afford the number and size of calls needed?
- **Latency:** Can users tolerate the response time?
- **Variance:** How much does output quality change across similar inputs?
- **Review effort:** Who checks the output, and how often?
- **Failure impact:** What happens when the system is confidently wrong?

These constraints push against each other.

A stronger model might improve quality but raise cost and latency. A cheaper model might be acceptable if the output is low stakes or always reviewed. Full automation might be reasonable for drafting internal labels, but reckless for issuing refunds, changing permissions, or sending regulated advice.

Prompt quality matters, but it is not the whole reliability story. You also need product boundaries, evals, fallback paths, rate limits, logging, monitoring, and humans where judgment is required.

Treat the model as one component inside a larger control system. Reliability comes from the full design, not from hoping the model is clever enough every time.

---
## Revision

AI reliability depends on the full system design, not only on the ???.

- prompt
- folder name
- button color
