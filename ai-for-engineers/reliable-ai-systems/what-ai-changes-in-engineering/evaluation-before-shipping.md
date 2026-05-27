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

# Evaluation Before Shipping

---
## Content

"It worked on my example" is not an eval.

Before shipping the support-summary feature, you need acceptance criteria. For example:

- The summary names the correct customer problem.
- It does not invent commitments, refunds, outages, or policy exceptions.
- It separates known facts from suggested next steps.
- It flags low-context tickets for review instead of guessing.
- It stays within a useful length for the support workflow.

Then you need test cases that reflect production, not only clean demos. Include short tickets, long tickets, contradictory messages, missing context, angry users, noisy logs, and cases where the correct behavior is to refuse a confident summary.

An eval does not prove the system will never fail. It gives you evidence about known risks before users depend on the output.

That evidence helps you decide whether to ship, change the prompt, use a different model, add retrieval, require review, or narrow the feature scope.

---
## Practice

An eval should test realistic cases against clear ???.

- acceptance criteria
- release dates
- model rumors

---
## Revision

The main difference between a demo and an eval is that an eval uses realistic cases and predefined ???.

- success criteria
- marketing copy
- variable names
