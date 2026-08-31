---
author: Stefan-Stojanovic

type: normal

category: must-know

practiceQuestion:
  formats:
    - free-form
  context: standalone
  rubric:
    expectedPoint: Splitting a request into a sequence lets the learner correct each step before it feeds the next one.
    requiredConcepts:
      - Each step can be corrected before it feeds the next one.
    acceptedAnswers:
      - You can correct each step before it feeds the next one.
      - You can review and correct each intermediate result before later steps build on it.
      - Splitting the work creates checkpoints that stop an early mistake from propagating through the whole output.
    hints:
      - What can you do after the themes are produced but before the slide text is written?
      - Explain what happens to later steps when an early error is fixed at that checkpoint.
    tooVagueExamples:
      - It gives you more control.
    incorrectExamples:
      - It guarantees that each individual step is accurate.
      - Its main benefit is avoiding pasting the source material more than once.

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Breaking It Into A Sequence

---
## Content

One task per message, each one feeding the next.

Start here:

```plain-text
Group these 20 exit survey responses into themes. Give me the theme, the number of responses in it, and one quoted line per theme.
```

You read the themes, merge two of them, rename another.

Then:

```plain-text
Using the six themes above, write four lines of slide text for the top three by response count. Neutral tone, no recommendations.
```

Recommendations come third, in their own message, which is where you want your own judgment sitting anyway.

The extra minute buys you somewhere to stand between the steps.

When something's off, you fix it there rather than running the whole thing again.

---
## Practice

Why can splitting a dependent task into a sequence produce a more reliable result?

???

- You can correct each step before it feeds the next one.
- give it less to hold in mind at any one time
- avoid pasting the material more than once
- get a more detailed answer overall

---
## Revision

You're breaking a five-part request into steps. The first prompt should ask for ???.

- the piece everything after it depends on
- the piece that takes longest
- the part you understand least
- the final output in rough form
