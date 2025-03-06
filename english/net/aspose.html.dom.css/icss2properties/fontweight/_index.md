---
title: ICSS2Properties.FontWeight
second_title: Aspose.HTML for .NET API Reference
description: ICSS2Properties FontWeight property. The font-weight property specifies the weight of the font. Values have the following meanings
type: docs
weight: 540
url: /net/aspose.html.dom.css/icss2properties/fontweight/
---
## ICSS2Properties.FontWeight property

The 'font-weight' property specifies the weight of the font. Values have the following meanings:

100 to 900 - These values form an ordered sequence, where each number indicates a weight that is at least as dark as its predecessor.normal - Same as '400'.bold - Same as '700'.bolder - Specifies the next weight that is assigned to a font that is darker than the inherited one. If there is no such weight, it simply results in the next darker numerical value (and the font remains unchanged), unless the inherited value was '900', in which case the resulting weight is also '900'.lighter - Specifies the next weight that is assigned to a font that is lighter than the inherited one. If there is no such weight, it simply results in the next lighter numerical value (and the font remains unchanged), unless the inherited value was '100', in which case the resulting weight is also '100'.

```csharp
public string FontWeight { get; set; }
```

### Return Value

font-weight property

### See Also

* interface [ICSS2Properties](../)
* namespace [Aspose.Html.Dom.Css](../../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../../)
