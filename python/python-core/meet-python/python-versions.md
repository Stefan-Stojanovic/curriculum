---
author: emmab
tags:
  - introduction
type: normal
category: must-know
practiceQuestion:
  formats:
    - free-form
  preferredFormat: free-form
  context: relative
  rubric:
    expectedPoint: "A cache is useful when a previously stored result can be retrieved or reused instead of generating or computing it again, usually improving speed or reducing cost."
    requiredConcepts:
      - "Conveys reusing or retrieving a stored result OR avoiding generating or computing the same result again."
    acceptedAnswers:
      - "A cache is useful when a saved result can be reused instead of generating the same result again."
      - "It helps when an existing answer can be retrieved faster and with less cost than recomputing it."
      - "Caching is useful when the same result is needed again and the stored version is still valid."
    hints:
      - "Think about what happens when the same answer or result is needed more than once."
      - "Compare retrieving an existing result with generating or computing it again."
      - "A cache is most useful when a valid stored result can be reused to avoid repeated work."
    tooVagueExamples:
      - "It makes things faster."
      - "Caches are useful."
      - "It saves time."
    incorrectExamples:
      - "It guarantees that data is always fresh."
      - "It is most useful when every request needs a completely new result."
---

# Cache results with a clear reuse point

---
## Content

A cache stores the result of work so future code can reuse it.

It helps when the same input is requested again and the saved result is still valid. Caching is not just saving data. A useful cache needs a lookup key, a place to store the result, and a rule for when the saved value should no longer be trusted.

---
## Practice

In your own words, when is a cache actually useful?

???

- It can retrieve and reuse a saved result instead of generating the same result again.
