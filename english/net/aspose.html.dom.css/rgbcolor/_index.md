---
title: RGBColor Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.RGBColor class. The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence modifications made to the CSSPrimitiveValue objects modify the style property
type: docs
weight: 790
url: /net/aspose.html.dom.css/rgbcolor/
---
## RGBColor class

The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence, modifications made to the CSSPrimitiveValue objects modify the style property.

A specified RGB color is not clipped (even if the number is outside the range 0-255 or 0%-100%). A computed RGB color is clipped depending on the device.

Even if a style sheet can only contain an integer for a color value, the internal storage of this integer is a float, and this can be used as a float in the specified or the computed style.

A color percentage value can always be converted to a number and vice versa.

```csharp
public class RGBColor : DOMObject
```

## Public Members
## Properties

| Name | Description |
| --- | --- |
| [Alpha](../../aspose.html.dom.css/rgbcolor/alpha/) { get; } | Gets the alpha component value of this Color structure. |
| [Blue](../../aspose.html.dom.css/rgbcolor/blue/) { get; } | Gets the blue component value of this Color structure. |
| [Green](../../aspose.html.dom.css/rgbcolor/green/) { get; } | Gets the green component value of this Color structure. |
| [Red](../../aspose.html.dom.css/rgbcolor/red/) { get; } | Gets the red component value of this Color structure. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [ToNative](../../aspose.html.dom.css/rgbcolor/tonative/)() | Converts to the native color object. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### See Also

* class [DOMObject](../../aspose.html.dom/domobject/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
