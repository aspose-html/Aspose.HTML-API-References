---
title: ICSS2Properties.Overflow
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. This property specifies whether the content of a block-level element is clipped when it overflows the elements box which is acting as a containing block for the content. Values have the following meanings
type: docs
weight: 790
url: /java/com.aspose.html.dom.css/icss2properties/overflow/
---
## ICSS2Properties.Overflow property

This property specifies whether the content of a block-level element is clipped when it overflows the element's box (which is acting as a containing block for the content). Values have the following meanings:

visible - This value indicates that content is not clipped, i.e., it may be rendered outside the block box.hidden - This value indicates that the content is clipped and that no scrolling mechanism should be provided to view the content outside the clipping region; users will not have access to clipped content. The size and shape of the clipping region is specified by the ['clip'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visufx.html#propdef-clip) property.scroll - This value indicates that the content is clipped and that if the user agent uses scrolling mechanism that is visible on the screen (such as a scroll bar or a panner), that mechanism should be displayed for a box whether or not any of its content is clipped. This avoids any problem with scrollbars appearing and disappearing in a dynamic environment. When this value is specified and the target medium is 'print' or 'projection', overflowing content should be printed.auto - The behavior of the 'auto' value is user agent-dependent, but should cause a scrolling mechanism to be provided for overflowing boxes.

```java
public String Overflow { get; set; }
```

### Return Value

overflow property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.Dom.Css](../../icss2properties/)
* package [Aspose.HTML](../../../)
