---
title: Color Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Drawing.Color class. The Color class lets you specify colors as Red-Green-Blue RGB values Hue-Saturation-Luminosity HSL values Hue-Saturation-Value HSV values Hue-Whiteness-Blackness HWB values lightness-A-B LAB values Luminance-Chroma-Hue LCH values Cyan-Magenta-Yellow-Key CMYK values Natural colors NCOL values or with a color name. An Alpha channel is also available to indicate transparency
type: docs
weight: 2650
url: /net/com.aspose.html.drawing/color/
---
## Color class

The Color class lets you specify colors as Red-Green-Blue (RGB) values, Hue-Saturation-Luminosity (HSL) values, Hue-Saturation-Value (HSV) values, Hue-Whiteness-Blackness (HWB) values, lightness-A-B (LAB) values, Luminance-Chroma-Hue (LCH) values, Cyan-Magenta-Yellow-Key (CMYK) values, Natural colors (NCOL) values, or with a color name. An Alpha channel is also available to indicate transparency.

```java
public class Color
```

## Constructors

| Name | Description |
| --- | --- |
| [Color](color/#constructor)() | Initializes a new instance of the `Color` class. By default color is black. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Initializes a new instance of the `Color` class. All color components must be in the range 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Initializes a new instance of the `Color` class. All color components must be in the range 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Initializes a new instance of the `Color` class. All color components must be in the range 0-255. |

## Properties

| Name | Description |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Represents the alpha component of the color. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Represents the blue component of the color. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Represents the green component of the color. |
| [getRed](../../com.aspose.html.drawing/color/red/) Represents the red component of the color |

## Methods

| Name | Description |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Returns a new Color with the requested cyan, magenta, yellow, key (black) values. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Returns a new Color with the requested cyan, magenta, yellow, key (black), alpha values. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Returns a new Color with the requested gray value. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Returns a new Color with the requested hue, saturation, saturation values. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Returns a new Color with the requested hue, saturation, saturation, alpha values. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Returns a new Color with the requested hue, saturation, value. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Returns a new Color with the requested hue, saturation, value, alpha. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Returns a new Color with the requested hue, whiteness, blackness values. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Returns a new Color with the requested hue, whiteness, blackness values. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Returns a new Color with the requested ARGB value. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Returns a new Color with the requested lightness, A, B values. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Returns a new Color with the requested lightness, A, B, alpha values. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Returns a new Color with the requested luminance, chroma, hue values. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Returns a new Color with the requested luminance, chroma, hue, alpha values. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Returns a new Color with the requested lightness, A, B values for OKLAB model. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Returns a new Color with the requested lightness, A, B, alpha values for OKLAB model. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Returns a new Color with the requested luminance, chroma, hue values for OKLAB model. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Returns a new Color with the requested luminance, chroma, hue, alpha values for OKLAB model. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Returns a new Color with the requested ged, green, blue values. All color components must be in the range 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Returns a new Color with the requested ged, green, blue, alpha values. All color components must be in the range 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Parses String containing the CSS color and returns a new Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Returns a new Color with the requested ARGB value. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Creates copy of the Color with Sum of its luminosity and the delta value. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Returns a color components in the format of the specified color model. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Determines whether the specified `Color` is equal to this instance. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Returns a new color that is on the opposite side of the color wheel from the original. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Returns a hash code. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Returns a Hue of the Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Returns a luminosity of the Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Returns a saturation of the Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Encodes the Color ARGB components into int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Returns the name of the color if it matches a color in the list of CSS named colors, or an empty String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Returns a Natural colors (NCol) specified color using a color letter with a number to specify the distance (in percent) from the color. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Returns a Hexadecimal color is specified with: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Returns a String containing the RGBA color specified by: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Returns a hexadecimal color is specified with: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Returns a String containing the RGB color specified by: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Returns a String that consists of the RGBA component values. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Encodes the Color ARGB components into unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Creates copy of the Color with specified alpha component. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Creates copy of the Color with specified Hue. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Creates copy of the Color with specified luminosity. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Creates copy of the Color with specified saturation. |

### See Also

* package [com.aspose.html.Drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
