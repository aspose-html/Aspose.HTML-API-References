---
title: "Color-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.drawing.Color class. De Color-klasse stelt je in staat kleuren op te geven als Red-Green-Blue RGB-waarden, Hue-Saturation-Luminosity HSL-waarden, Hue-Saturation-Value HSV-waarden, Hue-Whiteness-Blackness HWB-waarden, lightness-A-B LAB-waarden, Luminance-Chroma-Hue LCH-waarden, Cyan-Magenta-Yellow-Key CMYK-waarden, Natural colors NCOL-waarden of met een kleurnaam. Een Alpha-kanaal is ook beschikbaar om transparantie aan te geven."
type: docs

url: /nl/java/com.aspose.html.drawing/color/
---
## Color class

De Color-klasse stelt je in staat kleuren op te geven als Red-Green-Blue (RGB)-waarden, Hue-Saturation-Luminosity (HSL)-waarden, Hue-Saturation-Value (HSV)-waarden, Hue-Whiteness-Blackness (HWB)-waarden, lightness-A-B (LAB)-waarden, Luminance-Chroma-Hue (LCH)-waarden, Cyan-Magenta-Yellow-Key (CMYK)-waarden, Natural colors (NCOL)-waarden, of met een kleurnaam. Een Alpha-kanaal is ook beschikbaar om transparantie aan te geven.

```java
public class Color
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Color](color/#constructor)() | Initialiseert een nieuw exemplaar van de `Color`-klasse. Standaard is de kleur zwart. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_5)(float, float, float) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| [Color](color/#constructor_3)(int, int, int) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |
| [Color](color/#constructor_6)(float, float, float, float) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-1 liggen. |
| [Color](color/#constructor_4)(int, int, int, int) | Initialiseert een nieuw exemplaar van de `Color`-klasse. Alle kleurcomponenten moeten binnen het bereik 0-255 liggen. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Vertegenwoordigt het alpha-component van de kleur. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Vertegenwoordigt het blauwe component van de kleur. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Vertegenwoordigt het groene component van de kleur. |
| [getRed](../../com.aspose.html.drawing/color/red/) Vertegenwoordigt het rode component van de kleur |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde cyaan-, magenta-, geel- en key (zwart) waarden. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Retourneert een nieuwe Color met de gevraagde cyaan-, magenta-, geel-, key (zwart) en alpha-waarden. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Retourneert een nieuwe Color met de gevraagde grijswaarde. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, verzadiging- en verzadigingwaarden. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, verzadiging-, verzadiging- en alpha-waarden. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, verzadiging- en waarde. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, verzadiging-, waarde- en alpha-waarden. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, witheid- en zwartheidwaarden. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde tint-, witheid- en zwartheidwaarden. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Retourneert een nieuwe Color met de gevraagde ARGB-waarde. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde lichtheid-, A- en B-waarden. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde lichtheid, A, B, alfa-waarden. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde luminantie, chroma, tintwaarden. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde luminantie, chroma, tint, alfa-waarden. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde lichtheid, A, B-waarden voor het OKLAB-model. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde lichtheid, A, B, alfa-waarden voor het OKLAB-model. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Retourneert een nieuwe Color met de gevraagde luminantie, chroma, tintwaarden voor het OKLAB-model. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde luminantie, chroma, tint, alfa-waarden voor het OKLAB-model. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw waarden. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw waarden. Alle kleurcomponenten moeten in het bereik 0-1 liggen. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw waarden. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw, alfa-waarden. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw, alfa-waarden. Alle kleurcomponenten moeten in het bereik 0-1 liggen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Retourneert een nieuwe Color met de gevraagde ged, groen, blauw, alfa-waarden. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Parseert een String die de CSS-kleur bevat en retourneert een nieuwe Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Retourneert een nieuwe Color met de gevraagde ARGB-waarde. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Maakt een kopie van de Color met de som van zijn luminantie en de delta-waarde. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Retourneert kleurcomponenten in het formaat van het opgegeven kleurmodel. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Bepaalt of de opgegeven `Color` gelijk is aan deze instantie. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Retourneert een nieuwe kleur die zich aan de tegenovergestelde kant van het kleurenwiel bevindt ten opzichte van het origineel. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Retourneert een hashcode. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Retourneert een tint van de Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Retourneert een luminantie van de Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Retourneert een verzadiging van de Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Encodeert de ARGB-componenten van de Color naar een int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Retourneert de naam van de kleur als deze overeenkomt met een kleur in de lijst met CSS-genaamde kleuren, of een lege String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Retourneert een Natural colors (NCol) gespecificeerde kleur met een kleurletter en een getal om de afstand (in procent) van de kleur te specificeren. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Retourneert een hexadecimale kleur die wordt gespecificeerd met: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Retourneert een String die de RGBA-kleur bevat gespecificeerd door: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Retourneert een hexadecimale kleur die wordt gespecificeerd met: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Retourneert een string die de RGB-kleur bevat die wordt gespecificeerd door: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Retourneert een string die bestaat uit de RGBA-componentwaarden. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Encodeert de ARGB-componenten van de kleur naar een unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Maakt een kopie van de kleur met de opgegeven alfa-component. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Maakt een kopie van de kleur met de opgegeven tint. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Maakt een kopie van de kleur met de opgegeven luminantie. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Maakt een kopie van de kleur met de opgegeven verzadiging. |

### Zie ook

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
