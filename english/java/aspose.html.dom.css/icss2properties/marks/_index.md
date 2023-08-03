---
title: ICSS2Properties.Marks
second_title: Aspose.HTML for Java API Reference
description: ICSS2Properties property. In high-quality printing marks are often added outside the page box. This property specifies whether cross marks or crop marks or both should be rendered just outside the page box edge
type: docs
weight: 690
url: /net/com.aspose.html.dom.css/icss2properties/marks/
---
## ICSS2Properties.Marks property

In high-quality printing, marks are often added outside the page box. This property specifies whether cross marks or crop marks or both should be rendered just outside the [page box](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#page-box) edge.

Crop marks indicate where the page should be cut. Cross marks (also known as register marks or registration marks) are used to align sheets.

Marks are visible only on absolute page boxes (see the ['size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-size) property). In relative page boxes, the page box will be aligned with the target and the marks will be outside the printable area.

The size, style, and position of cross marks depend on the user agent.

```java
public String Marks { get; set; }
```

### Return Value

marks property

### See Also

* interface [ICSS2Properties](../)
* package [com.aspose.html.Dom.Css](../../icss2properties/)
* package [Aspose.HTML](../../../)
