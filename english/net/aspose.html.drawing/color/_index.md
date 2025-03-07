---
title: Color Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Drawing.Color class. The Color class lets you specify colors as Red-Green-Blue RGB values Hue-Saturation-Luminosity HSL values Hue-Saturation-Value HSV values Hue-Whiteness-Blackness HWB values lightness-A-B LAB values Luminance-Chroma-Hue LCH values Cyan-Magenta-Yellow-Key CMYK values Natural colors NCOL values or with a color name. An Alpha channel is also available to indicate transparency
type: docs
weight: 2810
url: /net/aspose.html.drawing/color/
---
## Color class

The Color class lets you specify colors as Red-Green-Blue (RGB) values, Hue-Saturation-Luminosity (HSL) values, Hue-Saturation-Value (HSV) values, Hue-Whiteness-Blackness (HWB) values, lightness-A-B (LAB) values, Luminance-Chroma-Hue (LCH) values, Cyan-Magenta-Yellow-Key (CMYK) values, Natural colors (NCOL) values, or with a color name. An Alpha channel is also available to indicate transparency.

```csharp
public class Color
```

## Constructors

| Name | Description |
| --- | --- |
| [Color](color/#constructor)() | Initializes a new instance of the `Color` class. By default color is black. |
| [Color](color/#constructor_1)(*byte, byte, byte*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_5)(*float, float, float*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-1. |
| [Color](color/#constructor_3)(*int, int, int*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_2)(*byte, byte, byte, byte*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_6)(*float, float, float, float*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-1. |
| [Color](color/#constructor_4)(*int, int, int, int*) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |

## Properties

| Name | Description |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Represents the alpha component of the color. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Represents the blue component of the color. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Represents the green component of the color. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Represents the red component of the color |

## Methods

| Name | Description |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(*float, float, float, float*) | Returns a new Color with the requested cyan, magenta, yellow, key (black) values. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(*float, float, float, float, float*) | Returns a new Color with the requested cyan, magenta, yellow, key (black), alpha values. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(*float*) | Returns a new Color with the requested gray value. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(*float, float, float*) | Returns a new Color with the requested hue, saturation, saturation values. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(*float, float, float, float*) | Returns a new Color with the requested hue, saturation, saturation, alpha values. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(*float, float, float*) | Returns a new Color with the requested hue, saturation, value. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(*float, float, float, float*) | Returns a new Color with the requested hue, saturation, value, alpha. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(*float, float, float*) | Returns a new Color with the requested hue, whiteness, blackness values. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(*float, float, float, float*) | Returns a new Color with the requested hue, whiteness, blackness values. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(*int*) | Returns a new Color with the requested ARGB value. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(*float, float, float*) | Returns a new Color with the requested lightness, A, B values. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(*float, float, float, float*) | Returns a new Color with the requested lightness, A, B, alpha values. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(*float, float, float*) | Returns a new Color with the requested luminance, chroma, hue values. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(*float, float, float, float*) | Returns a new Color with the requested luminance, chroma, hue, alpha values. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(*float, float, float*) | Returns a new Color with the requested lightness, A, B values for OKLAB model. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(*float, float, float, float*) | Returns a new Color with the requested lightness, A, B, alpha values for OKLAB model. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(*float, float, float*) | Returns a new Color with the requested luminance, chroma, hue values for OKLAB model. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(*float, float, float, float*) | Returns a new Color with the requested luminance, chroma, hue, alpha values for OKLAB model. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(*byte, byte, byte*) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(*float, float, float*) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-1. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(*int, int, int*) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(*byte, byte, byte, byte*) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(*float, float, float, float*) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-1. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(*int, int, int, int*) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(*string*) | Parses string containing the CSS color and returns a new Color. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(*uint*) | Returns a new Color with the requested ARGB value. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(*float*) | Creates copy of the Color with Sum of its luminosity and the delta value. |
| [Convert](../../aspose.html.drawing/color/convert/)(*[ColorModel](../colormodel/)*) | Returns a color components in the format of the specified color model. |
| override [Equals](../../aspose.html.drawing/color/equals/)(*object*) | Determines whether the specified `Color` is equal to this instance. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Returns a new color that is on the opposite side of the color wheel from the original. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Returns a hash code. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Returns a Hue of the Color. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Returns a luminosity of the Color. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Returns a saturation of the Color. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Encodes the Color ARGB components into int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Returns the name of the color if it matches a color in the list of CSS named colors, or an empty string. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(*int*) | Returns a Natural colors (NCol) specified color using a color letter with a number to specify the distance (in percent) from the color. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Returns a Hexadecimal color is specified with: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Returns a string containing the RGBA color specified by: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Returns a hexadecimal color is specified with: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Returns a string containing the RGB color specified by: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Returns a string that consists of the RGBA component values. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Encodes the Color ARGB components into unsigned int. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(*float*) | Creates copy of the Color with specified alpha component. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(*float*) | Creates copy of the Color with specified Hue. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(*float*) | Creates copy of the Color with specified luminosity. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(*float*) | Creates copy of the Color with specified saturation. |

### See Also

* namespace [Aspose.Html.Drawing](../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../)
