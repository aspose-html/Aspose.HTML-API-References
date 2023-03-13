---
title: Class Color
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Drawing.Color klass. Med klassen Färg kan du ange färger som RödGrönBlå RGB värden NyansMättnadLuminositet HSL värden NyansMättnadValue HSV värden_B HueHvithet BlackHvithet  värden ljushetAB LAB värden LuminanceChromaHue LCH värden CyanMagentaYellowKey CMYK värden Naturliga färger NCOL färgnamn_x00 . En alfakanal är också tillgänglig för att indikera transparens.
type: docs
weight: 2640
url: /sv/net/aspose.html.drawing/color/
---
## Color class

Med klassen Färg kan du ange färger som Röd-Grön-Blå (RGB) värden, Nyans-Mättnad-Luminositet (HSL) värden, Nyans-Mättnad-Value (HSV) värden,_B Hue-Hvithet (Black-Hvithet) ) värden, ljushet-AB (LAB) värden, Luminance-Chroma-Hue (LCH) värden, Cyan-Magenta-Yellow-Key (CMYK) värden, Naturliga färger (NCOL) färgnamn,_x00 . En alfakanal är också tillgänglig för att indikera transparens.

```csharp
public class Color
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Color](color/#constructor)() | Initierar en ny instans av`Color` class. Som standard är färgen svart. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initierar en ny instans av`Color`class. Alla färgkomponenter måste vara i intervallet 0-255. |
| [Color](color/#constructor_5)(float, float, float) | Initierar en ny instans av`Color` class. Alla färgkomponenter måste vara i intervallet 0-1. |
| [Color](color/#constructor_3)(int, int, int) | Initierar en ny instans av`Color`class. Alla färgkomponenter måste vara i intervallet 0-255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initierar en ny instans av`Color`class. Alla färgkomponenter måste vara i intervallet 0-255. |
| [Color](color/#constructor_6)(float, float, float, float) | Initierar en ny instans av`Color` class. Alla färgkomponenter måste vara i intervallet 0-1. |
| [Color](color/#constructor_4)(int, int, int, int) | Initierar en ny instans av`Color`class. Alla färgkomponenter måste vara i intervallet 0-255. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Representerar alfakomponenten i färgen. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Representerar den blå komponenten i färgen. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Representerar den gröna komponenten i färgen. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Representerar den röda komponenten i color |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Returnerar en ny färg med de begärda värdena för cyan, magenta, gul, nyckel (svart). |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Returnerar en ny färg med de begärda värdena för cyan, magenta, gul, nyckel (svart), alfa. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Returnerar en ny färg med det begärda gråvärdet. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Returnerar en ny färg med de begärda värdena för nyans, mättnad och mättnad. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Returnerar en ny färg med önskad nyans, mättnad, mättnad, alfavärden. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Returnerar en ny färg med önskad nyans, mättnad, värde. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Returnerar en ny färg med önskad nyans, mättnad, värde, alpha. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Returnerar en ny färg med de begärda värdena för nyans, vithet, svärta. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Returnerar en ny färg med de begärda värdena för nyans, vithet, svärta. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Returnerar en ny färg med det begärda ARGB-värdet. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Returnerar en ny färg med den begärda ljusheten, A, B-värden. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Returnerar en ny färg med den begärda ljusheten, A, B, alfavärden. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Returnerar en ny färg med de begärda värdena för luminans, chroma, nyans. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Returnerar en ny färg med de begärda värdena för luminans, chroma, nyans, alfa. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Returnerar en ny färg med den begärda ljusheten, A, B-värden för OKLAB-modellen. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Returnerar en ny färg med den begärda ljusheten, A, B, alfavärden för OKLAB-modellen. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Returnerar en ny färg med de begärda värdena för luminans, chroma, nyans för OKLAB-modellen. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Returnerar en ny färg med de begärda luminans-, chroma-, nyans-, alfavärdena för OKLAB-modellen. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Returnerar en ny färg med de begärda ged, gröna, blå värdena. Alla färgkomponenter måste vara i intervallet 0-255. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Returnerar en ny färg med de begärda ged, gröna, blå värdena. Alla färgkomponenter måste vara i intervallet 0-1. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Returnerar en ny färg med de begärda ged, gröna, blå värdena. Alla färgkomponenter måste vara i intervallet 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Returnerar en ny färg med de begärda ged, gröna, blå, alfavärdena. Alla färgkomponenter måste vara i intervallet 0-255. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Returnerar en ny färg med de begärda ged, gröna, blå, alfavärdena. Alla färgkomponenter måste vara i intervallet 0-1. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Returnerar en ny färg med de begärda ged, gröna, blå, alfavärdena. Alla färgkomponenter måste vara i intervallet 0-255. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Analyserar sträng som innehåller CSS-färgen och returnerar en ny färg. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Returnerar en ny färg med det begärda ARGB-värdet. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Skapar en kopia av färgen med summan av dess ljusstyrka och deltavärdet. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Returnerar en färgkomponent i formatet för den angivna färgmodellen. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Bestämmer om den angivna`Color` är lika med denna instans. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Returnerar en ny färg som finns på motsatt sida av färghjulet från originalet. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Returnerar en hashkod. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Returnerar en nyans av färgen. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Returnerar en ljusstyrka av färgen. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Returnerar en mättnad av färgen. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Kodar Color ARGB-komponenterna till int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Returnerar namnet på färgen om den matchar en färg i listan över CSS-namngivna färger, eller en tom sträng. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Returnerar en naturlig färg (NCol) specificerad färg med hjälp av en färgbokstav med en siffra för att ange avståndet (i procent) från färgen. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Returnerar en hexadecimal färg anges med: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Returnerar en sträng som innehåller RGBA-färgen specificerad av: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Returnerar en hexadecimal färg som anges med: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Returnerar en sträng som innehåller RGB-färgen specificerad av: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Returnerar en sträng som består av RGBA-komponentvärdena. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Kodar Color ARGB-komponenterna till osignerad int. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Skapar en kopia av färgen med angiven alfakomponent. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Skapar kopia av färgen med specificerad nyans. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Skapar en kopia av färgen med specificerad ljusstyrka. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Skapar en kopia av färgen med specificerad mättnad. |

### Se även

* namnutrymme [Aspose.Html.Drawing](../../aspose.html.drawing/)
* hopsättning [Aspose.HTML](../../)


