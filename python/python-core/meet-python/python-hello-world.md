---
author: Stefan-Stojanovic

type: normal

category: discussion

practiceQuestion:
  formats:
    - free-form
  context: standalone
  rubric:
    expectedPoint: AI copied a different difference between the examples from the one the learner intended.
    requiredConcepts:
      - AI copied the wrong difference between the examples.
    acceptedAnswers:
      - AI copied a different difference than the one you meant.
      - AI inferred the wrong contrast between the examples and copied brevity instead of fixing the original problem.
      - Because the intended difference was not named, the assistant focused on another visible feature of the examples.
    hints:
      - Besides the original problem, what other visible difference could AI notice between the two examples?
      - Explain why placing two examples side by side still leaves a choice about what to copy.
    tooVagueExamples:
      - AI misunderstood the examples.
    incorrectExamples:
      - AI ignored the weak example completely.
      - AI ran out of space to follow both examples.

revisionQuestion:
  formats:
    - fill-in-the-gap
  context: standalone

---

# Naming The Difference

---
## Content

Two examples side by side still leave AI to work out what you meant by the contrast.

It usually guesses right. Usually.

One sentence takes the guessing away:

```plain-text
The difference is that the good one names what the money paid for, while the weak one thanks in general terms and hints at the next gift.
```

Leave that out and it may decide the lesson was "be shorter".

Then you get short notes that still hint at the next gift, and you're back where you started with less text.

> ‼️ When output half-follows your example, the usual cause is that it copied a different feature than the one you had in mind.

---
## Practice

You show a strong and a weak example, but the new drafts are only shorter and still have the original problem. What did AI get wrong?

???

- AI copied a different difference than the one you meant.

---
## Revision

Your prompt now holds a good example and a counter-example. The line worth adding underneath them is ???.

- what actually separates the two
- a reminder to follow the good one closely
- a note saying which of the two is the one to copy
- a third example in the same style
