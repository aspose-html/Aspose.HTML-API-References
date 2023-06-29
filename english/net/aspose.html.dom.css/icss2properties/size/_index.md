---
title: ICSS2Properties.Size
second_title: Aspose.HTML for .NET API Reference
description: ICSS2Properties property. This property specifies the size and orientation of a page box
type: docs
weight: 990
url: /net/aspose.html.dom.css/icss2properties/size/
---
## ICSS2Properties.Size property

This property specifies the size and orientation of a page box.

The size of a page box may either be "absolute" (fixed size) or "relative" (scalable, i.e., fitting available sheet sizes). Relative page boxes allow user agents to scale a document and make optimal use of the target size.

Three values for the ['size'](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html#propdef-size) property create a relative page box:

auto - The page box will be set to the size and orientation of the target sheet.landscape - Overrides the target's orientation. The page box is the same size as the target, and the longer sides are horizontal.portrait - Overrides the target's orientation. The page box is the same size as the target, and the shorter sides are horizontal.

```csharp
public string Size { get; set; }
```

### Return Value

size property

### See Also

* interface [ICSS2Properties](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
