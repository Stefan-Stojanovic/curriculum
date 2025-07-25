---
author: Stefan-Stojanovic
type: normal
category: coding

links:
  - >-
    [HTML <address>
    element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address){documentation}

webSetupCode:
  startingHtml: |
    <address>
      Authors Email:
      <a href="http://www.website.com/contact">
        www.website.com
      </a>.<br>
      Author address:<br>
      Company name<br>
      Some Street address<br>
      City, State<br>
      Country<br>
    </address>
    
---

# The address Element

---

## Content

The HTML `<address>` element is used to provide contact information about the author. This element is displayed as a block element and has a default styling like the `<i>` and `<em>` elements (the text is italic).

![address](https://img.enkipro.com/9ec8992af472e5a9d37e0d1f01a1d69a.png)

This element can contain different types of content:
 
- Physical address
- URL
- E-mail address
- Phone number
- Geographical coordinates
- And more...

The content of the `<address>` element should include the name of the person, people, or organization to which the contact information refers.

Address Example:

```html
<address>
  Authors Email:
  <a href="http://www.web.com/contact">
    www.web.com/contact
  </a>.<br>
  Author address:<br>
  Company name<br>
  Some Street address<br>
  City, State<br>
  Country
</address>
```

[View CodePen](https://codepen.io/enkidevs/pen/OEoaVN)

Beside representing contact information about the author of the document, the `<address>` element can be used with different types of context. When placed within a `<body>` element it represents information about the document. When placed within an `<article>` element it represents information about an article.

On the other hand, if you want to represent an arbitrary address (such as postal addresses), which are not related to the contact information, you should use the `<p>` element rather than the `<address>` element.
