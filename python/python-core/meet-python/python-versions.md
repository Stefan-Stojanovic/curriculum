---
author: emmab
tags:
  - introduction
type: normal
category: must-know
links:
  - >-
    [Python 3 Vs Python
    2](https://learntocodewith.me/programming/python/python-2-vs-python-3/){website}
practiceQuestion:
  formats:
    - free-form
  preferredFormat: free-form
  context: relative
  rubric:
    expectedPoint: "A cache is useful when the app can reuse a stored result instead of repeating expensive work."
    requiredConcepts:
      - "reuse a stored result"
      - "avoid repeating expensive work"
    tooVagueExamples:
      - "It makes things faster."
    incorrectExamples:
      - "It guarantees data is always fresh."
---

# Cache results with a clear reuse point

---
## Content

A cache stores the result of expensive work so future code can reuse it.

It helps when the same input is requested again and the saved result is still valid. Caching is not just saving data. A useful cache needs a lookup key, a place to store the result, and a rule for when the saved value should no longer be trusted.

---
## Practice

In your own words, when is a cache actually useful?

???

- It can reuse a stored result and avoid repeating expensive work.
