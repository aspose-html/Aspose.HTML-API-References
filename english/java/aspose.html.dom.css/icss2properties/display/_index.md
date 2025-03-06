---
title: ICSS2Properties.Display
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. The values of this property have the following meanings
type: docs

url: /java/com.aspose.html.dom.css/icss2properties/display/
---
## ICSS2Properties.Display property

The values of this property have the following meanings:

block - This value causes an element to generate a principal block box.inline - This value causes an element to generate one or more inline boxes.list-item - This value causes an element (e.g., LI in HTML) to generate a principal block box and a list-item inline box. For information about lists and examples of list formatting, please consult the section on [lists](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#lists).marker - This value declares [generated content](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html) before or after a box to be a marker. This value should only be used with [:before and :after pseudo-elements](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#before-after-content) attached to block-level elements. In other cases, this value is interpreted as 'inline'. Please consult the section on [markers](https://www.w3.org/TR/1998/REC-CSS2-19980512/generate.html#markers) for more information.none - This value causes an element to generate no boxes in the [formatting structure](https://www.w3.org/TR/1998/REC-CSS2-19980512/intro.html#formatting-structure) (i.e., the element has no effect on layout). Descendant elements do not generate any boxes either; this behavior cannot be overridden by setting the ['display'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-display) property on the descendants. Please note that a display of 'none' does not create an invisible box; it creates no box at all. CSS includes mechanisms that enable an element to generate boxes in the formatting structure that affect formatting but are not visible themselves. Please consult the section on [visibility](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#visibility) for details.run-in and compact - These values create either block or inline boxes, depending on context. Properties apply to run-in and compact boxes based on their final status (inline-level or block-level). For example, the ['white-space'](https://www.w3.org/TR/1998/REC-CSS2-19980512/text.html#propdef-white-space) property only applies if the box becomes a block box.table, inline-table, table-row-group, [table-column](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#value-def-table-column), table-column-group, table-header-group, table-footer-group, table-row, table-cell, and table-caption - These values cause an element to behave like a table element (subject to restrictions described in the chapter on [tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html)).

```java
public String Display { get; set; }
```

### Return Value

display property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
