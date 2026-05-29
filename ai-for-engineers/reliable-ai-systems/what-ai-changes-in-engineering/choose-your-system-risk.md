---
author: Stefan-Stojanovic

type: normal

category: discussion

practiceQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Choose Your System Risk

---
## Content

Now apply the reliability frame to a system you might build, ship, or operate.

Pick one AI-powered feature or workflow. It can be real or hypothetical:

- summarizing support tickets
- drafting incident updates
- ranking search results
- triaging security alerts

Write down four things:

1. The intended output
2. What could go wrong
3. What evidence would show it is good enough
4. What should trigger review, fallback, or escalation

Example sketch:

- Feature: customer-escalation summary
- Intended output: a short summary for the on-call engineer
- Risk: it invents a root cause
- Evidence: eval cases with known source facts pass a no-invention check
- Review trigger: missing source context, billing risk, or high-severity incident

This is a small version of the engineering habit behind reliable AI systems: define the job, name the failure, gather evidence, and choose controls that match the impact of being wrong.

If you want to stress-test your answer, post it in the comments and ask Enki AI which failure mode or guardrail you may be underestimating.

---
## Practice

A review ??? tells the system when to pause, fall back, or escalate.

- trigger
- color
- title

---
## Revision

Reliable AI design chooses ??? that match the impact of being wrong.

- controls
- colors
- slogans
