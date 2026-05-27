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
- extracting fields from contracts
- suggesting code changes
- reviewing policy-sensitive content

Write down four things:

1. The intended output
2. What could go wrong
3. What evidence would show it is good enough
4. Who is affected when it is wrong
5. What should trigger review, fallback, or escalation

For example:

> Feature: customer-escalation summary  
> Intended output: a short summary for the on-call engineer  
> Risk: it invents a root cause  
> Evidence: eval cases with known source facts pass the no-invention check  
> Impact: the wrong team may investigate the wrong issue  
> Review trigger: billing, legal, angry customer, missing source context, or high-severity incident

This is a small version of the engineering habit behind reliable AI systems: define the job, name the failure, gather evidence, and choose controls that match the impact.

If you want to stress-test your answer, post it in the comments and ask Enki AI which failure mode or guardrail you may be underestimating.

---
## Practice

For your chosen AI feature, a useful risk sketch should include output, failure risk, evidence, affected owner or user, and review or fallback ???.

- trigger
- color
- title

---
## Revision

Reliable AI design starts by defining the job, naming the failure, gathering evidence, and choosing ??? that match the impact.

- controls
- colors
- slogans
