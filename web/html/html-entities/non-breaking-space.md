---
author: stefan.stojanovic

levels:
  - beginner
  - basic

type: normal

category: must-know

standards:
  web.markup-text.2: 10

aspects:
  - introduction
  - workout
  - deep
  
---
# Non-breaking Space

---
## Content

The HTML non-breaking space is a character entity used for either creating white space between words or web page elements, or to stop a browser from breaking a line where it shouldn't

To insert a non-breaking space you would use either the HTML entity *name* or the HTML entity *number* :

HTML Entity Number
```
&#160;
```
HTML Entity Name
```
&nbsp;
```

For instance, when you want to force a browser to not break a line at a certain place you would add a non-breaking space between words/characters you don't want to be separated on different lines. Let's say you have a name like this: `Mr. John Doe`, to force the browser to not split it, you would add spaces like so:

Input:
```
Mr.&nbsp;John&nbsp;Doe
```
Result:
```
Mr. John Doe
```

Another great use for the non-breaking space is forcing the browser to keep 2 pictures side-by-side.

Example:
```
<p>
<img src="http://i.picresize.com/images
  /2018/02/18/N8MeY.png"/>&nbsp;<img
  src="http://i.picresize.com/images
  /2018/02/18/N8MeY.png" /></p>
```

Result:

![alt text][logo]
![alt text][logo]

[logo]: http://i.picresize.com/images/2018/02/18/N8MeY.png


Also, the non-breaking space can be used to create white space. Like in the example above, the non-breaking space is used to create the white space separating the 2 pictures.

Furthermore, if you have a table with an empty cell within your web page, you should insert a non-breaking space character in the empty cell to prevent the cell from collapsing.

```
<td>&nbsp;</td>
```

**Note: You should never use the `non-breaking space` for indenting a paragraph. This is because some browsers ignore multiple instances of the non-breaking space so indenting this way may not always work. To create an indent for your paragraphs it is better to use CSS.** 

---
## Practice

Which statement is true regarding a non-breaking space:

???

* Prevents an empty cell in a table from collapsing in some browsers.
* Useful for creating indented paragraphs.
* Long strings of them are good ways of creating gaps of space.
* They are easier to read than a space character.

---
## Revision

What HTML character entity is used to prevent the browser from breaking the line between certain words or web page elements?

`<p>5???km</p>`

* `&nbsp;`
* `&ensp;`
* `&ltsp;`
* `empty space: " "`
* `&space`
* `&gap`

---
## Quiz

### How much do you know about displaying images?

What does the "&nbsp;" within this line of code do?

`<img src="image1.png" alt="">&nbsp;<img src="image2.png" alt="">`

* Adds an empty character of space between the images.
* Prevents the images from starting on a new line like word wrap.
* Removes any space between the images.
* Useful when pulling image files from a database.
