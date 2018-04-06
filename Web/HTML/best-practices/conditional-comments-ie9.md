---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

stub: true

tags:
  - deep
---
# Conditional Comments (ie9)
---
## Content

Conditional comments are conditional statements used in Internet Explorer versions 5 through 9.

There are two types of conditional comments. They are written as:

downlevel-hidden:
```
<!--[if expression]>
HTML goes here
<![endif]-->
```
downlevel-revealed
```
<![if expression]>
HTML goes here
<![endif]>
```

Downlevel-hidden will be revealed only for IE versions 5-9. This is because the syntax is similar to HTML comment syntax.

HTML comment syntax:
```
<!-- Comment goes here -->
```

This means that only browsers which support conditional comments won't ignore them as simple HTML comments and execute what's inside. 

Downlevel-revealed will be revealed for IE versions 5-9 plus every non IE browsers. However, for them do be executable HTMl code, they have to be written as:

```
<!--[if expression]><!--> 
HTML goes here
<!--<![endif]-->
```

---
## Practice

How are conditional comments written for versions of IE prior to IE10?

???

* <!--[if IE]> HTML CODE HERE <![endif]-->


---
## Revision

Conditional comments only work in Internet Explorer, versions prior to IE10.

???
* T