---
title: Class Color
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Drawing.Color klas. Mit der ColorKlasse können Sie Farben als RotGrünBlau RGBWerte FarbtonSättigungsLuminanz HSLWerte FarbtonSättigungsWert HSVWerte FarbtonWeißSchwarz HWBWerte angeben Werte LightnessAB LABWerte LuminanceChromaHue LCHWerte CyanMagentaYellowKey CMYKWerte Natural Colors NCOLWerte oder mit einem Farbnamen . Ein AlphaKanal ist ebenfalls verfügbar um Transparenz anzuzeigen.
type: docs
weight: 2640
url: /de/net/aspose.html.drawing/color/
---
## Color class

Mit der Color-Klasse können Sie Farben als Rot-Grün-Blau (RGB)-Werte, Farbton-Sättigungs-Luminanz (HSL)-Werte, Farbton-Sättigungs-Wert (HSV)-Werte, Farbton-Weiß-Schwarz (HWB)-Werte angeben )-Werte, Lightness-AB (LAB)-Werte, Luminance-Chroma-Hue (LCH)-Werte, Cyan-Magenta-Yellow-Key (CMYK)-Werte, Natural Colors (NCOL)-Werte, oder mit einem Farbnamen . Ein Alpha-Kanal ist ebenfalls verfügbar, um Transparenz anzuzeigen.

```csharp
public class Color
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Color](color/#constructor)() | Initialisiert eine neue Instanz von`Color` class. Standardfarbe ist schwarz. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initialisiert eine neue Instanz von`Color`class. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| [Color](color/#constructor_5)(float, float, float) | Initialisiert eine neue Instanz von`Color` class. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| [Color](color/#constructor_3)(int, int, int) | Initialisiert eine neue Instanz von`Color`class. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initialisiert eine neue Instanz von`Color`class. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| [Color](color/#constructor_6)(float, float, float, float) | Initialisiert eine neue Instanz von`Color` class. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| [Color](color/#constructor_4)(int, int, int, int) | Initialisiert eine neue Instanz von`Color`class. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alpha](../../aspose.html.drawing/color/alpha/) { get; } | Stellt die Alpha-Komponente der Farbe dar. |
| [Blue](../../aspose.html.drawing/color/blue/) { get; } | Repräsentiert die blaue Komponente der Farbe. |
| [Green](../../aspose.html.drawing/color/green/) { get; } | Repräsentiert die grüne Komponente der Farbe. |
| [Red](../../aspose.html.drawing/color/red/) { get; } | Repräsentiert die rote Komponente der Farbe |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromCmyk](../../aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Cyan, Magenta, Gelb und Schlüssel (Schwarz) zurück. |
| static [FromCmyka](../../aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Cyan, Magenta, Gelb, Key (Schwarz) und Alpha zurück. |
| static [FromGray](../../aspose.html.drawing/color/fromgray/)(float) | Gibt eine neue Farbe mit dem angeforderten Grauwert zurück. |
| static [FromHsl](../../aspose.html.drawing/color/fromhsl/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Farbton-, Sättigungs- und Sättigungswerten zurück. |
| static [FromHsla](../../aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Farbton, Sättigung, Sättigung und Alpha zurück. |
| static [FromHsv](../../aspose.html.drawing/color/fromhsv/)(float, float, float) | Gibt eine neue Farbe mit dem angeforderten Farbton, der Sättigung und dem Wert zurück. |
| static [FromHsva](../../aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Gibt eine neue Farbe mit dem angeforderten Farbton, Sättigung, Wert, Alpha zurück. |
| static [FromHwb](../../aspose.html.drawing/color/fromhwb/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Farbton, Weißgrad und Schwarzwert zurück. |
| static [FromHwba](../../aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Farbton, Weißgrad und Schwarzwert zurück. |
| static [FromInt](../../aspose.html.drawing/color/fromint/)(int) | Gibt eine neue Farbe mit dem angeforderten ARGB-Wert zurück. |
| static [FromLab](../../aspose.html.drawing/color/fromlab/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Helligkeits-, A- und B-Werten zurück. |
| static [FromLaba](../../aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Helligkeits-, A-, B- und Alpha-Werten zurück. |
| static [FromLch](../../aspose.html.drawing/color/fromlch/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Luminanz-, Chroma- und Farbtonwerten zurück. |
| static [FromLcha](../../aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Luminanz, Chroma, Farbton und Alpha zurück. |
| static [FromOklab](../../aspose.html.drawing/color/fromoklab/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Helligkeits-, A- und B-Werten für das OKLAB-Modell zurück. |
| static [FromOklaba](../../aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Helligkeits-, A-, B- und Alpha-Werten für das OKLAB-Modell zurück. |
| static [FromOklch](../../aspose.html.drawing/color/fromoklch/)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Luminanz-, Chroma- und Farbtonwerten für das OKLAB-Modell zurück. |
| static [FromOklcha](../../aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Luminanz, Chroma, Farbton und Alpha für das OKLAB-Modell zurück. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Green und Blue zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Green und Blue zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgb](../../aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Green und Blue zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Grün, Blau und Alpha zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Grün, Blau und Alpha zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgba](../../aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Gibt eine neue Farbe mit den angeforderten Werten für Ged, Grün, Blau und Alpha zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromString](../../aspose.html.drawing/color/fromstring/)(string) | Analysiert die Zeichenfolge, die die CSS-Farbe enthält, und gibt eine neue Farbe zurück. |
| static [FromUint](../../aspose.html.drawing/color/fromuint/)(uint) | Gibt eine neue Farbe mit dem angeforderten ARGB-Wert zurück. |
| [AddLuminosity](../../aspose.html.drawing/color/addluminosity/)(float) | Erstellt eine Kopie der Farbe mit der Summe ihrer Leuchtkraft und dem Deltawert. |
| [Convert](../../aspose.html.drawing/color/convert/)(ColorModel) | Gibt eine Farbkomponente im Format des angegebenen Farbmodells zurück. |
| override [Equals](../../aspose.html.drawing/color/equals/)(object) | Bestimmt, ob die angegebene`Color` ist gleich dieser Instanz. |
| [GetComplementary](../../aspose.html.drawing/color/getcomplementary/)() | Gibt eine neue Farbe zurück, die sich auf der dem Original entgegengesetzten Seite des Farbkreises befindet. |
| override [GetHashCode](../../aspose.html.drawing/color/gethashcode/)() | Gibt einen Hash-Code zurück. |
| [GetHue](../../aspose.html.drawing/color/gethue/)() | Gibt einen Farbton der Farbe zurück. |
| [GetLuminosity](../../aspose.html.drawing/color/getluminosity/)() | Gibt eine Helligkeit der Farbe zurück. |
| [GetSaturation](../../aspose.html.drawing/color/getsaturation/)() | Gibt eine Sättigung der Farbe zurück. |
| [ToInt](../../aspose.html.drawing/color/toint/)() | Kodiert die Farb-ARGB-Komponenten in int. |
| [ToName](../../aspose.html.drawing/color/toname/)() | Gibt den Namen der Farbe zurück, wenn sie mit einer Farbe in der Liste der benannten CSS-Farben übereinstimmt, oder mit einer leeren Zeichenfolge. |
| [ToNaturalColorString](../../aspose.html.drawing/color/tonaturalcolorstring/)(int) | Gibt eine in natürlichen Farben (NCol) angegebene Farbe zurück, wobei ein Farbbuchstabe mit einer Zahl verwendet wird, um den Abstand (in Prozent) von der Farbe anzugeben. |
| [ToRgbaHexString](../../aspose.html.drawing/color/torgbahexstring/)() | Gibt eine hexadezimale Farbe zurück, die angegeben ist mit: #RRGGBBAA. |
| [ToRgbaString](../../aspose.html.drawing/color/torgbastring/)() | Gibt einen String zurück, der die RGBA-Farbe enthält, die angegeben wird durch: rgba(R, G, B, A). |
| [ToRgbHexString](../../aspose.html.drawing/color/torgbhexstring/)() | Gibt eine hexadezimale Farbe zurück, die angegeben ist mit: #RRGGBB. |
| [ToRgbString](../../aspose.html.drawing/color/torgbstring/)() | Gibt einen String zurück, der die RGB-Farbe enthält, die angegeben wird durch: rgb(R, G, B). |
| override [ToString](../../aspose.html.drawing/color/tostring/)() | Gibt eine Zeichenfolge zurück, die aus den RGBA-Komponentenwerten besteht. |
| [ToUint](../../aspose.html.drawing/color/touint/)() | Kodiert die Farb-ARGB-Komponenten in unsigned int. |
| [WithAlpha](../../aspose.html.drawing/color/withalpha/)(float) | Erstellt eine Kopie der Farbe mit der angegebenen Alpha-Komponente. |
| [WithHue](../../aspose.html.drawing/color/withhue/)(float) | Erstellt eine Kopie der Farbe mit dem angegebenen Farbton. |
| [WithLuminosity](../../aspose.html.drawing/color/withluminosity/)(float) | Erstellt eine Kopie der Farbe mit angegebener Helligkeit. |
| [WithSaturation](../../aspose.html.drawing/color/withsaturation/)(float) | Erstellt eine Kopie der Farbe mit der angegebenen Sättigung. |

### Siehe auch

* namensraum [Aspose.Html.Drawing](../../aspose.html.drawing/)
* Montage [Aspose.HTML](../../)


