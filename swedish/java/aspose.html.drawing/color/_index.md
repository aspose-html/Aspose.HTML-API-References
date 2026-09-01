---
title: "Color-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.drawing.Color-klass. Color-klassen låter dig ange färger som Red-Green-Blue RGB‑värden, Hue‑Saturation‑Luminosity HSL‑värden, Hue‑Saturation‑Value HSV‑värden, Hue‑Whiteness‑Blackness HWB‑värden, lightness‑A‑B LAB‑värden, Luminance‑Chroma‑Hue LCH‑värden, Cyan‑Magenta‑Yellow‑Key CMYK‑värden, Natural colors NCOL‑värden eller med ett färgnamn. En Alpha‑kanal finns också för att ange transparens."
type: docs

url: /sv/java/com.aspose.html.drawing/color/
---
## Color class

Klassen Color låter dig ange färger som Red-Green-Blue (RGB)-värden, Hue-Saturation-Luminosity (HSL)-värden, Hue-Saturation-Value (HSV)-värden, Hue-Whiteness-Blackness (HWB)-värden, lightness-A-B (LAB)-värden, Luminance-Chroma-Hue (LCH)-värden, Cyan-Magenta-Yellow-Key (CMYK)-värden, Natural colors (NCOL)-värden, eller med ett färgnamn. En alfa‑kanal finns också tillgänglig för att ange transparens.

```java
public class Color
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Color](color/#constructor)() | Initierar en ny instans av `Color`-klassen. Som standard är färgen svart. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_5)(float, float, float) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| [Color](color/#constructor_3)(int, int, int) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |
| [Color](color/#constructor_6)(float, float, float, float) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑1. |
| [Color](color/#constructor_4)(int, int, int, int) | Initierar en ny instans av `Color`-klassen. Alla färgkomponenter måste ligga i intervallet 0‑255. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Representerar alfakomponenten i färgen. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Representerar den blå komponenten i färgen. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Representerar den gröna komponenten i färgen. |
| [getRed](../../com.aspose.html.drawing/color/red/) Representerar den röda komponenten i färgen |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Returnerar en ny Color med de begärda cyan-, magenta-, gul- och key (svart)-värdena. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Returnerar en ny Color med de begärda cyan-, magenta-, gul- och key (svart)- samt alfa‑värdena. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Returnerar en ny Color med det begärda gråvärdet. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Returnerar en ny Color med de begärda nyans-, mättnads- och mättnadsvärdena. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Returnerar en ny Color med de begärda nyans-, mättnads- och mättnads‑ samt alfa‑värdena. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Returnerar en ny Color med de begärda nyans-, mättnads- och värdevärdena. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Returnerar en ny Color med de begärda nyans-, mättnads- och värde‑ samt alfa‑värdena. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Returnerar en ny Color med de begärda nyans-, vithets- och svarthetsvärdena. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Returnerar en ny Color med de begärda nyans-, vithets- och svarthetsvärdena. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Returnerar en ny Color med det begärda ARGB‑värdet. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Returnerar en ny Color med de begärda ljushets-, A‑ och B‑värdena. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Returnerar en ny Color med den begärda ljusheten, A, B, alfa-värdena. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Returnerar en ny Color med de begärda luminans-, kromatiska- och nyansvärdena. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Returnerar en ny Color med de begärda luminans-, kromatiska-, nyans- och alfa-värdena. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Returnerar en ny Color med den begärda ljusheten, A, B värden för OKLAB-modellen. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Returnerar en ny Color med den begärda ljusheten, A, B, alfa-värden för OKLAB-modellen. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Returnerar en ny Color med de begärda luminans-, kromatiska- och nyansvärdena för OKLAB-modellen. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Returnerar en ny Color med de begärda luminans-, kromatiska-, nyans- och alfa-värdena för OKLAB-modellen. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Returnerar en ny Color med de begärda ged-, grön- och blåvärdena. Alla färgkomponenter måste ligga i intervallet 0-255. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Returnerar en ny Color med de begärda ged-, grön- och blåvärdena. Alla färgkomponenter måste ligga i intervallet 0-1. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Returnerar en ny Color med de begärda ged-, grön- och blåvärdena. Alla färgkomponenter måste ligga i intervallet 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Returnerar en ny Color med de begärda ged-, grön-, blå- och alfa-värdena. Alla färgkomponenter måste ligga i intervallet 0-255. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Returnerar en ny Color med de begärda ged-, grön-, blå- och alfa-värdena. Alla färgkomponenter måste ligga i intervallet 0-1. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Returnerar en ny Color med de begärda ged-, grön-, blå- och alfa-värdena. Alla färgkomponenter måste ligga i intervallet 0-255. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Tolkar en String som innehåller CSS-färgen och returnerar en ny Color. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Returnerar en ny Color med det begärda ARGB‑värdet. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Skapar en kopia av Color med summan av dess luminans och delta-värdet. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Returnerar färgkomponenter i formatet för den angivna färgmodellen. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Avgör om den angivna `Color` är lika med detta objekt. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Returnerar en ny färg som ligger på motsatt sida av färghjulet från den ursprungliga. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Returnerar en hashkod. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Returnerar en Hue för Color. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Returnerar en luminans för Color. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Returnerar en mättnad för Color. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Kodar Color ARGB-komponenterna till int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Returnerar namnet på färgen om den matchar en färg i listan över CSS-namnade färger, eller en tom String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Returnerar en Natural colors (NCol) specificerad färg med en färgbokstav och ett tal för att ange avståndet (i procent) från färgen. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Returnerar en Hexadecimal färg som specificeras med: #RRGGBBAA. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Returnerar en String som innehåller RGBA-färgen specificerad av: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Returnerar en hexadecimal färg som anges med: #RRGGBB. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Returnerar en String som innehåller RGB‑färgen specificerad av: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Returnerar en String som består av RGBA‑komponentvärdena. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Kodar Color‑ARGB‑komponenterna till ett unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Skapar en kopia av Color med angiven alfa‑komponent. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Skapar en kopia av Color med angiven nyans. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Skapar en kopia av Color med angiven luminans. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Skapar en kopia av Color med angiven mättnad. |

### Se även

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
