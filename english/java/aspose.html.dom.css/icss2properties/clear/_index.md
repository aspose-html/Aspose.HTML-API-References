---
title: ICSS2Properties.Clear
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. This property indicates which sides of an elements boxes may not be adjacent to an earlier floating box. It may be that the element itself has floating descendants the clear property has no effect on those
type: docs
weight: 320
url: /net/com.aspose.html.dom.css/icss2properties/clear/
---
## ICSS2Properties.Clear property

This property indicates which sides of an element's box(es) may not be adjacent to an earlier floating box. (It may be that the element itself has floating descendants; the 'clear' property has no effect on those.)

This property may only be specified for block-level elements (including floats). For compact and run-in boxes, this property applies to the final block box to which the compact or run-in box belongs.

Values have the following meanings when applied to non-floating block boxes:

left - The top margin of the generated box is increased enough that the top border edge is below the bottom outer edge of any left-floating boxes that resulted from elements earlier in the source document.right - The top margin of the generated box is increased enough that the top border edge is below the bottom outer edge of any right-floating boxes that resulted from elements earlier in the source document.both - The generated box is moved below all floating boxes of earlier elements in the source document..none - No constraint on the box's position with respect to floats.

```java
public String Clear { get; set; }
```

### Return Value

clear property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.Dom.Css](../../icss2properties/)
* package [Aspose.HTML](../../../)
