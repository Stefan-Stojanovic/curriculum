---
author: Stefan-Stojanovic
type: normal
category: caveat
revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone
---

# Failure Modes And Guardrails

---
## Content

AI failures are often plausible.

That is what makes them operationally dangerous. A bad output might not crash. It might look polished, fit the expected format, and still be wrong in a way that matters.

Common failure modes include:

- **Hallucinated facts:** The model invents details that were not in the source.
- **Missing context:** The model ignores a constraint, policy, permission, or recent change.
- **Policy violations:** The output recommends something the product should not allow.
- **Unsafe automation:** The system takes an action that should require approval.
- **Overconfident summaries:** The model hides uncertainty behind fluent language.
- **Unstable output:** Similar inputs produce materially different answers.

Guardrails are controls that reduce the chance or impact of those failures.

Some guardrails constrain what the model can produce, such as a strict output schema or a requirement to cite source fields. Some guardrails constrain what the system can do, such as blocking automatic action above a risk threshold. Others help operators notice problems, such as logs, monitoring, sampling, alerts, and escalation paths.

For the support-summary feature, a reasonable guardrail might be:

> If the ticket mentions billing, legal risk, account deletion, or conflicting source notes, the summary can draft internal notes but cannot send a customer-facing response without human review.

The point is not to eliminate all risk. The point is to make risky behavior visible, bounded, and recoverable.

---
## Revision

A guardrail should make risky AI behavior more visible, bounded, or ???.

- recoverable
- invisible
- surprising
