---
title: Class Color
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Drawing.Color klas. Met de klasse Color kunt u kleuren opgeven als roodgroenblauw RGBwaarden HueSaturationLuminosity HSLwaarden HueSaturationValue HSVwaarden HueWhitenessBlackness HWB  waarden lichtheidAB LAB waarden LuminantieChromaHue LCH waarden CyanMagentaYellowKey CMYK waarden Natuurlijke kleuren NCOL waarden of met een kleurnaam . Er is ook een alfakanaal beschikbaar om transparantie aan te geven.
type: docs
weight: 2640
url: /nl/net/aspose.html.drawing/color/
---
## Color class

Met de klasse Color kunt u kleuren opgeven als rood-groen-blauw (RGB)-waarden, Hue-Saturation-Luminosity (HSL)-waarden, Hue-Saturation-Value (HSV)-waarden, Hue-Whiteness-Blackness (HWB ) waarden, lichtheid-AB (LAB) waarden, Luminantie-Chroma-Hue (LCH) waarden, Cyan-Magenta-Yellow-Key (CMYK) waarden, Natuurlijke kleuren (NCOL) waarden, of met een kleurnaam . Er is ook een alfakanaal beschikbaar om transparantie aan te geven.

```csharp
public class Color
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Color](color/#constructor)() | Initialiseert een nieuw exemplaar van het`Color` class. Standaard is de kleur zwart. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initialiseert een nieuw exemplaar van het`Color`class. Alle kleurcomponenten moeten in het bereik 0-255. liggen |
| [Color](color/#constructor_5)(float, float, float) | Initialiseert een nieuw exemplaar van het`Color` class. Alle kleurcomponenten moeten in het bereik 0-1. liggen |
| [Color](color/#constructor_3)(int, int, int) | Initialiseert een nieuw exemplaar van het`Color`class. Alle kleurcomponenten moeten in het bereik 0-255. liggen |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initialiseert een nieuw exemplaar van het`Color`class. Alle kleurcomponenten moeten in het bereik 0-255. liggen |
| [Color](color/#constructor_6)(float, float, float, float) | Initialiseert een nieuw exemplaar van het`Color` class. Alle kleurcomponenten moeten in het bereik 0-1. liggen |
| [Color](color/#constructor_4)(int, int, int, int) | Initialiseert een nieuw exemplaar van het`Color`class. Alle kleurcomponenten moeten in het bereik 0-255. liggen |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Vertegenwoordigt de alfacomponent van de kleur. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Vertegenwoordigt de blauwe component van de kleur. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Vertegenwoordigt de groene component van de kleur. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Vertegenwoordigt de rode component van de kleur |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor cyaan, magenta, geel, key (zwart). |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor cyaan, magenta, geel, sleutel (zwart), alfa. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Retourneert een nieuwe kleur met de gevraagde grijswaarde. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor tint, verzadiging en verzadiging. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor tint, verzadiging, verzadiging en alfa. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde tint, verzadiging, waarde. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde tint, verzadiging, waarde, alfa. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor tint, witheid en zwartheid. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor tint, witheid en zwartheid. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Retourneert een nieuwe kleur met de gevraagde ARGB-waarde. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde helderheid, A-, B-waarden. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde lichtheid, A, B, alfawaarden. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde luminantie-, chroma- en tintwaarden. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor luminantie, chroma, tint en alfa. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde lichtheid, A- en B-waarden voor het OKLAB-model. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde lichtheid, A, B, alpha-waarden voor OKLAB-model. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde luminantie-, chroma- en tintwaarden voor het OKLAB-model. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor luminantie, chroma, tint en alfa voor het OKLAB-model. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen en blauw. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen en blauw. Alle kleurcomponenten moeten in het bereik 0-1 liggen. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen en blauw. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen, blauw en alfa. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen, blauw en alfa. Alle kleurcomponenten moeten in het bereik 0-1 liggen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Retourneert een nieuwe kleur met de gevraagde waarden voor ged, groen, blauw en alfa. Alle kleurcomponenten moeten in het bereik 0-255 liggen. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Parseert tekenreeks die de CSS-kleur bevat en retourneert een nieuwe kleur. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Retourneert een nieuwe kleur met de gevraagde ARGB-waarde. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Maakt een kopie van de kleur met de som van de helderheid en de deltawaarde. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Retourneert kleurcomponenten in de indeling van het opgegeven kleurmodel. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Bepaalt of de opgegeven`Color` is gelijk aan deze instantie. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Retourneert een nieuwe kleur die zich aan de andere kant van het kleurenwiel bevindt dan het origineel. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Retourneert een hash-code. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Retourneert een tint van de kleur. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Retourneert een helderheid van de kleur. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Retourneert een verzadiging van de kleur. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Codeert de Color ARGB-componenten in int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Retourneert de naam van de kleur als deze overeenkomt met een kleur in de lijst met CSS-benoemde kleuren, of met een lege tekenreeks. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Retourneert een door natuurlijke kleuren (NCol) gespecificeerde kleur met behulp van een kleurletter met een cijfer om de afstand (in procenten) van de kleur op te geven. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Retourneert een hexadecimale kleur die is gespecificeerd met: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Retourneert een tekenreeks met de RGBA-kleur gespecificeerd door: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Retourneert een hexadecimale kleur gespecificeerd met: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Retourneert een tekenreeks met de RGB-kleur gespecificeerd door: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Retourneert een tekenreeks die bestaat uit de RGBA-componentwaarden. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Codeert de Color ARGB-componenten in unsigned int. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Maakt een kopie van de kleur met opgegeven alfacomponent. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Maakt een kopie van de kleur met opgegeven tint. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Maakt een kopie van de kleur met opgegeven helderheid. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Maakt een kopie van de kleur met gespecificeerde verzadiging. |

### Zie ook

* naamruimte [Aspose.Html.Drawing](../../aspose.html.drawing/)
* montage [Aspose.HTML](../../)


