---
title: RGBColor Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.css.RGBColor class. The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence modifications made to the CSSPrimitiveValue objects modify the style property
type: docs

url: /java/com.aspose.html.dom.css/rgbcolor/
---
## RGBColor class

The RGBColor interface is used to represent any RGB color value. This interface reflects the values in the underlying style property. Hence, modifications made to the CSSPrimitiveValue objects modify the style property.

A specified RGB color is not clipped (even if the number is outside the range 0-255 or 0%-100%). A computed RGB color is clipped depending on the device.

Even if a style sheet can only contain an integer for a color value, the internal storage of this integer is a float, and this can be used as a float in the specified or the computed style.

A color percentage value can always be converted to a number and vice versa.

```java
public class RGBColor : DOMObject
```

## Properties

| Name | Description |
| --- | --- |
| [getAlpha](../../com.aspose.html.dom.css/rgbcolor/alpha/) Gets the alpha component value of this Color structure. |
| [getBlue](../../com.aspose.html.dom.css/rgbcolor/blue/) Gets the blue component value of this Color structure. |
| [getGreen](../../com.aspose.html.dom.css/rgbcolor/green/) Gets the green component value of this Color structure. |
| [getRed](../../com.aspose.html.dom.css/rgbcolor/red/) Gets the red component value of this Color structure. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [toNative](../../com.aspose.html.dom.css/rgbcolor/tonative/)() | Converts to the native color object. |

## Remarks

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Reference

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### See Also

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
