---
author: jordanfish

levels:

  - basic

  - advanced

  - medium

type: normal

category: hack


links:

  - '[github.com](https://github.com/AllThingsSmitty/css-protips){website}'


---

# Equal width table cells

---
## Content

Use `table-layout: fixed` to keep a table's cells at equal width:
```
#second-table {
  table-layout: fixed;
}
```
This is how the table would look without the property:

![NOtablelayout.svg](%3C?xml%20version=%221.0%22%20encoding=%22UTF-8%22%20standalone=%22no%22?%3E%0A%3Csvg%20width=%22100%25%22%20height=%22auto%22%20viewBox=%220%200%20620%20210%22%0A%20xmlns=%22http://www.w3.org/2000/svg%22%20xmlns:xlink=%22http://www.w3.org/1999/xlink%22%20%20version=%221.2%22%20baseProfile=%22tiny%22%3E%0A%3Cdesc%3ECreated%20by%20HiQPdf%3C/desc%3E%0A%3Cdefs%3E%0A%3C/defs%3E%0A%3Cg%20fill=%22none%22%20stroke=%22black%22%20stroke-width=%221%22%20fill-rule=%22evenodd%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20%3E%0A%0A%3Cg%20fill=%22#596193%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L620,8%20L620,208%20L8,208%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L620,8%20L620,9%20L8,9%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,207%20L620,207%20L620,208%20L8,208%20L8,207%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L9,8%20L9,208%20L8,208%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M619,8%20L620,8%20L620,208%20L619,208%20L619,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,11%20L151,11%20L151,12%20L11,12%20L11,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,74%20L151,74%20L151,75%20L11,75%20L11,74%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,11%20L12,11%20L12,75%20L11,75%20L11,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M150,11%20L151,11%20L151,75%20L150,75%20L150,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,11%20L293,11%20L293,12%20L153,12%20L153,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,74%20L293,74%20L293,75%20L153,75%20L153,74%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,11%20L154,11%20L154,75%20L153,75%20L153,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M292,11%20L293,11%20L293,75%20L292,75%20L292,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,11%20L617,11%20L617,12%20L295,12%20L295,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,74%20L617,74%20L617,75%20L295,75%20L295,74%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,11%20L296,11%20L296,75%20L295,75%20L295,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,11%20L617,11%20L617,75%20L616,75%20L616,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,77%20L151,77%20L151,78%20L11,78%20L11,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,139%20L151,139%20L151,140%20L11,140%20L11,139%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,77%20L12,77%20L12,140%20L11,140%20L11,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M150,77%20L151,77%20L151,140%20L150,140%20L150,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,77%20L293,77%20L293,78%20L153,78%20L153,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,139%20L293,139%20L293,140%20L153,140%20L153,139%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,77%20L154,77%20L154,140%20L153,140%20L153,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M292,77%20L293,77%20L293,140%20L292,140%20L292,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,77%20L617,77%20L617,78%20L295,78%20L295,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,139%20L617,139%20L617,140%20L295,140%20L295,139%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,77%20L296,77%20L296,140%20L295,140%20L295,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,77%20L617,77%20L617,140%20L616,140%20L616,77%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,142%20L151,142%20L151,143%20L11,143%20L11,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,204%20L151,204%20L151,205%20L11,205%20L11,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,142%20L12,142%20L12,205%20L11,205%20L11,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M150,142%20L151,142%20L151,205%20L150,205%20L150,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,142%20L293,142%20L293,143%20L153,143%20L153,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,204%20L293,204%20L293,205%20L153,205%20L153,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M153,142%20L154,142%20L154,205%20L153,205%20L153,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M292,142%20L293,142%20L293,205%20L292,205%20L292,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,142%20L617,142%20L617,143%20L295,143%20L295,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,204%20L617,204%20L617,205%20L295,205%20L295,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M295,142%20L296,142%20L296,205%20L295,205%20L295,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,142%20L617,142%20L617,205%20L616,205%20L616,142%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2226%22%20y=%2250%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3EFirst%20Name%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22168.5%22%20y=%2250%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3ELast%20Name%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22414%22%20y=%2250%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3EHobbies%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2222%22%20y=%22115%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EMike%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22164%22%20y=%22115%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3ESmith%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22306%22%20y=%22115%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3ERunning%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2222%22%20y=%22180%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EAnn%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22164%22%20y=%22180%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EDoe%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22306%22%20y=%22180%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EReading%20and%20listening%20to%20music%3C/text%3E%0A%3C/g%3E%0A%0A%3C/g%3E%0A%3C/svg%3E%0A)

And with it:

![WITHtablelayout.svg](%3C?xml%20version=%221.0%22%20encoding=%22UTF-8%22%20standalone=%22no%22?%3E%0A%3Csvg%20width=%22100%25%22%20height=%22auto%22%20viewBox=%220%200%20620%20210%22%0A%20xmlns=%22http://www.w3.org/2000/svg%22%20xmlns:xlink=%22http://www.w3.org/1999/xlink%22%20%20version=%221.2%22%20baseProfile=%22tiny%22%3E%0A%3Cdesc%3ECreated%20by%20HiQPdf%3C/desc%3E%0A%3Cdefs%3E%0A%3C/defs%3E%0A%3Cg%20fill=%22none%22%20stroke=%22black%22%20stroke-width=%221%22%20fill-rule=%22evenodd%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20%3E%0A%0A%3Cg%20fill=%22#596193%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L620,8%20L620,208%20L8,208%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L620,8%20L620,9%20L8,9%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,207%20L620,207%20L620,208%20L8,208%20L8,207%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M8,8%20L9,8%20L9,208%20L8,208%20L8,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M619,8%20L620,8%20L620,208%20L619,208%20L619,8%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,11%20L211,11%20L211,12%20L11,12%20L11,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,65%20L211,65%20L211,66%20L11,66%20L11,65%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,11%20L12,11%20L12,66%20L11,66%20L11,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M210,11%20L211,11%20L211,66%20L210,66%20L210,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,11%20L414,11%20L414,12%20L213,12%20L213,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,65%20L414,65%20L414,66%20L213,66%20L213,65%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,11%20L214,11%20L214,66%20L213,66%20L213,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M413,11%20L414,11%20L414,66%20L413,66%20L413,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,11%20L617,11%20L617,12%20L416,12%20L416,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,65%20L617,65%20L617,66%20L416,66%20L416,65%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,11%20L417,11%20L417,66%20L416,66%20L416,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,11%20L617,11%20L617,66%20L616,66%20L616,11%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,68%20L211,68%20L211,69%20L11,69%20L11,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,121%20L211,121%20L211,122%20L11,122%20L11,121%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,68%20L12,68%20L12,122%20L11,122%20L11,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M210,68%20L211,68%20L211,122%20L210,122%20L210,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,68%20L414,68%20L414,69%20L213,69%20L213,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,121%20L414,121%20L414,122%20L213,122%20L213,121%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,68%20L214,68%20L214,122%20L213,122%20L213,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M413,68%20L414,68%20L414,122%20L413,122%20L413,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,68%20L617,68%20L617,69%20L416,69%20L416,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,121%20L617,121%20L617,122%20L416,122%20L416,121%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,68%20L417,68%20L417,122%20L416,122%20L416,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,68%20L617,68%20L617,122%20L616,122%20L616,68%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,124%20L211,124%20L211,125%20L11,125%20L11,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,204%20L211,204%20L211,205%20L11,205%20L11,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M11,124%20L12,124%20L12,205%20L11,205%20L11,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M210,124%20L211,124%20L211,205%20L210,205%20L210,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,124%20L414,124%20L414,125%20L213,125%20L213,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,204%20L414,204%20L414,205%20L213,205%20L213,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M213,124%20L214,124%20L214,205%20L213,205%20L213,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M413,124%20L414,124%20L414,205%20L413,205%20L413,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,124%20L617,124%20L617,125%20L416,125%20L416,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,204%20L617,204%20L617,205%20L416,205%20L416,204%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M416,124%20L417,124%20L417,205%20L416,205%20L416,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Cpath%20vector-effect=%22none%22%20fill-rule=%22evenodd%22%20d=%22M616,124%20L617,124%20L617,205%20L616,205%20L616,124%22/%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2256%22%20y=%2246%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3EFirst%20Name%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22259%22%20y=%2246%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3ELast%20Name%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22474.5%22%20y=%2246%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22700%22%20font-style=%22normal%22%20%0A%20%3EHobbies%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2222%22%20y=%22102%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EMike%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22224%22%20y=%22102%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3ESmith%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22427%22%20y=%22102%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3ERunning%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%2222%22%20y=%22171%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EAnn%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22224%22%20y=%22171%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EDoe%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22427%22%20y=%22158%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3EReading%20and%3C/text%3E%0A%3C/g%3E%0A%0A%3Cg%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22#ffffff%22%20stroke-opacity=%221%22%20stroke-width=%221%22%20stroke-linecap=%22square%22%20stroke-linejoin=%22bevel%22%20transform=%22matrix%281,0,0,1,0,0%29%22%0A%3E%0A%3Ctext%20fill=%22#ffffff%22%20fill-opacity=%221%22%20stroke=%22none%22%20xml:space=%22preserve%22%20x=%22427%22%20y=%22184%22%20font-family=%22'Roboto',sans-serif%22%20font-size=%2222%22%20font-weight=%22400%22%20font-style=%22normal%22%20%0A%20%3Elistening%20to%20music%3C/text%3E%0A%3C/g%3E%0A%0A%3C/g%3E%0A%3C/svg%3E%0A)

---
## Revision

What does the following CSS property do? ???
```css
table-layout: fixed;
```

* Maintains table cells at an equal width. 
* Stops the table size from being altered.
* Stops the table layout from being altered.
