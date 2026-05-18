---
title: "Color-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.drawing.Color class. Die Color-Klasse ermöglicht es Ihnen, Farben als Rot-Grün-Blau RGB-Werte, Farbton‑Sättigung‑Luminanz HSL-Werte, Farbton‑Sättigung‑Helligkeit HSV-Werte, Farbton‑Weiß‑Schwarz HWB-Werte, Helligkeit‑A‑B LAB-Werte, Luminanz‑Chroma‑Farbton LCH-Werte, Cyan‑Magenta‑Gelb‑Schwarz CMYK-Werte, Natürliche Farben NCOL-Werte oder mit einem Farbnamen anzugeben. Ein Alpha‑Kanal ist ebenfalls verfügbar, um Transparenz anzuzeigen."
type: docs

url: /de/java/com.aspose.html.drawing/color/
---
## Color class

Die Klasse Color ermöglicht es, Farben als Rot-Grün-Blau (RGB)-Werte, Farbton‑Sättigung‑Luminanz (HSL)-Werte, Farbton‑Sättigung‑Wert (HSV)-Werte, Farbton‑Weiß‑Schwarz (HWB)-Werte, Lichtheit‑A‑B (LAB)-Werte, Luminanz‑Chroma‑Farbton (LCH)-Werte, Cyan‑Magenta‑Gelb‑Schlüssel (CMYK)-Werte, Natürliche Farben (NCOL)-Werte oder mit einem Farbnamen anzugeben. Ein Alpha‑Kanal ist ebenfalls verfügbar, um Transparenz anzugeben.

```java
public class Color
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Color](color/#constructor)() | Initialisiert eine neue Instanz der `Color`-Klasse. Standardmäßig ist die Farbe schwarz. |
| [Color](color/#constructor_1)(byte, byte, byte) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_5)(float, float, float) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑1 liegen. |
| [Color](color/#constructor_3)(int, int, int) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_2)(byte, byte, byte, byte) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |
| [Color](color/#constructor_6)(float, float, float, float) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑1 liegen. |
| [Color](color/#constructor_4)(int, int, int, int) | Initialisiert eine neue Instanz der `Color`-Klasse. Alle Farbkomponenten müssen im Bereich 0‑255 liegen. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getAlpha](../../com.aspose.html.drawing/color/alpha/) Stellt die Alpha-Komponente der Farbe dar. |
| [getBlue](../../com.aspose.html.drawing/color/blue/) Stellt die blaue Komponente der Farbe dar. |
| [getGreen](../../com.aspose.html.drawing/color/green/) Stellt die grüne Komponente der Farbe dar. |
| [getRed](../../com.aspose.html.drawing/color/red/) Stellt die rote Komponente der Farbe dar |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromCmyk](../../com.aspose.html.drawing/color/fromcmyk/)(float, float, float, float) | Gibt ein neues Color mit den angeforderten Cyan-, Magenta-, Gelb- und Key (Schwarz)-Werten zurück. |
| static [FromCmyka](../../com.aspose.html.drawing/color/fromcmyka/)(float, float, float, float, float) | Gibt ein neues Color mit den angeforderten Cyan-, Magenta-, Gelb-, Key (Schwarz)- und Alpha-Werten zurück. |
| static [FromGray](../../com.aspose.html.drawing/color/fromgray/)(float) | Gibt ein neues Color mit dem angeforderten Grauwert zurück. |
| static [FromHsl](../../com.aspose.html.drawing/color/fromhsl/)(float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Sättigungs- und Sättigungswerten zurück. |
| static [FromHsla](../../com.aspose.html.drawing/color/fromhsla/)(float, float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Sättigungs-, Sättigungs- und Alpha-Werten zurück. |
| static [FromHsv](../../com.aspose.html.drawing/color/fromhsv/)(float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Sättigungs- und Wertwerten zurück. |
| static [FromHsva](../../com.aspose.html.drawing/color/fromhsva/)(float, float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Sättigungs-, Wert- und Alpha-Werten zurück. |
| static [FromHwb](../../com.aspose.html.drawing/color/fromhwb/)(float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Weißheits- und Schwarzheitswerten zurück. |
| static [FromHwba](../../com.aspose.html.drawing/color/fromhwba/)(float, float, float, float) | Gibt ein neues Color mit den angeforderten Farbton-, Weißheits- und Schwarzheitswerten zurück. |
| static [FromInt](../../com.aspose.html.drawing/color/fromint/)(int) | Gibt ein neues Color mit dem angeforderten ARGB-Wert zurück. |
| static [FromLab](../../com.aspose.html.drawing/color/fromlab/)(float, float, float) | Gibt ein neues Color mit den angeforderten Lightness-, A- und B-Werten zurück. |
| static [FromLaba](../../com.aspose.html.drawing/color/fromlaba/)(float, float, float, float) | Gibt eine neue Color mit den angeforderten Helligkeit-, A-, B- und Alpha-Werten zurück. |
| static [FromLch](../../com.aspose.html.drawing/color/fromlch/)(float, float, float) | Gibt eine neue Color mit den angeforderten Luminanz-, Chroma- und Farbtonwerten zurück. |
| static [FromLcha](../../com.aspose.html.drawing/color/fromlcha/)(float, float, float, float) | Gibt eine neue Color mit den angeforderten Luminanz-, Chroma-, Farbton- und Alpha-Werten zurück. |
| static [FromOklab](../../com.aspose.html.drawing/color/fromoklab/)(float, float, float) | Gibt eine neue Color mit den angeforderten Helligkeit-, A- und B-Werten für das OKLAB-Modell zurück. |
| static [FromOklaba](../../com.aspose.html.drawing/color/fromoklaba/)(float, float, float, float) | Gibt eine neue Color mit den angeforderten Helligkeit-, A-, B- und Alpha-Werten für das OKLAB-Modell zurück. |
| static [FromOklch](../../com.aspose.html.drawing/color/fromoklch/)(float, float, float) | Gibt eine neue Color mit den angeforderten Luminanz-, Chroma- und Farbtonwerten für das OKLAB-Modell zurück. |
| static [FromOklcha](../../com.aspose.html.drawing/color/fromoklcha/)(float, float, float, float) | Gibt eine neue Color mit den angeforderten Luminanz-, Chroma-, Farbton- und Alpha-Werten für das OKLAB-Modell zurück. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb)(byte, byte, byte) | Gibt eine neue Color mit den angeforderten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_2)(float, float, float) | Gibt eine neue Color mit den angeforderten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgb](../../com.aspose.html.drawing/color/fromrgb/#fromrgb_1)(int, int, int) | Gibt eine neue Color mit den angeforderten ged-, Grün- und Blauwerten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba)(byte, byte, byte, byte) | Gibt eine neue Color mit den angeforderten ged-, Grün-, Blau- und Alpha-Werten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_2)(float, float, float, float) | Gibt eine neue Color mit den angeforderten ged-, Grün-, Blau- und Alpha-Werten zurück. Alle Farbkomponenten müssen im Bereich 0-1 liegen. |
| static [FromRgba](../../com.aspose.html.drawing/color/fromrgba/#fromrgba_1)(int, int, int, int) | Gibt eine neue Color mit den angeforderten ged-, Grün-, Blau- und Alpha-Werten zurück. Alle Farbkomponenten müssen im Bereich 0-255 liegen. |
| static [FromString](../../com.aspose.html.drawing/color/fromString/)(String) | Parst einen String, der die CSS-Farbe enthält, und gibt eine neue Color zurück. |
| static [FromUint](../../com.aspose.html.drawing/color/fromuint/)(uint) | Gibt ein neues Color mit dem angeforderten ARGB-Wert zurück. |
| [addLuminosity](../../com.aspose.html.drawing/color/addluminosity/)(float) | Erstellt eine Kopie der Color mit der Summe ihrer Luminosität und dem Delta-Wert. |
| [convert](../../com.aspose.html.drawing/color/convert/)(ColorModel) | Gibt die Farbkomponenten im Format des angegebenen Farbmodells zurück. |
| [equals](../../com.aspose.html.drawing/color/equals/)(object) | Bestimmt, ob das angegebene `Color` gleich dieser Instanz ist. |
| [getComplementary](../../com.aspose.html.drawing/color/getcomplementary/)() | Gibt eine neue color zurück, die sich auf der gegenüberliegenden Seite des Farbkreises vom Original befindet. |
| [getHashCode](../../com.aspose.html.drawing/color/gethashcode/)() | Gibt einen Hashcode zurück. |
| [getHue](../../com.aspose.html.drawing/color/gethue/)() | Gibt einen Farbton des Color zurück. |
| [getLuminosity](../../com.aspose.html.drawing/color/getluminosity/)() | Gibt eine Luminosität des Color zurück. |
| [getSaturation](../../com.aspose.html.drawing/color/getsaturation/)() | Gibt eine Sättigung des Color zurück. |
| [toInt](../../com.aspose.html.drawing/color/toint/)() | Kodiert die ARGB-Komponenten des Color in einen int. |
| [toName](../../com.aspose.html.drawing/color/toname/)() | Gibt den Namen des color zurück, wenn er mit einem color in der Liste der benannten CSS-Farben übereinstimmt, oder einen leeren String. |
| [toNaturalColorString](../../com.aspose.html.drawing/color/tonaturalcolorString/)(int) | Gibt eine Natural colors (NCol) angegebene Farbe zurück, die einen Farbbuchstaben mit einer Zahl verwendet, um die Entfernung (in Prozent) von der Farbe anzugeben. |
| [toRgbaHexString](../../com.aspose.html.drawing/color/torgbahexString/)() | Gibt eine Hexadezimalfarbe zurück, die mit: #RRGGBBAA angegeben wird. |
| [toRgbaString](../../com.aspose.html.drawing/color/torgbaString/)() | Gibt einen String zurück, der die RGBA-Farbe enthält, die angegeben ist durch: rgba(R, G, B, A). |
| [toRgbHexString](../../com.aspose.html.drawing/color/torgbhexString/)() | Gibt eine hexadezimale Farbe zurück, die mit: #RRGGBB angegeben wird. |
| [toRgbString](../../com.aspose.html.drawing/color/torgbString/)() | Gibt einen String zurück, der die RGB-Farbe enthält, die angegeben wird durch: rgb(R, G, B). |
| [toString](../../com.aspose.html.drawing/color/toString/)() | Gibt einen String zurück, der aus den RGBA-Komponentenwerten besteht. |
| [toUint](../../com.aspose.html.drawing/color/touint/)() | Kodiert die ARGB-Komponenten der Farbe in einen unsigned int. |
| [withAlpha](../../com.aspose.html.drawing/color/withalpha/)(float) | Erstellt eine Kopie der Farbe mit dem angegebenen Alpha‑Komponente. |
| [withHue](../../com.aspose.html.drawing/color/withhue/)(float) | Erstellt eine Kopie der Farbe mit dem angegebenen Farbton. |
| [withLuminosity](../../com.aspose.html.drawing/color/withluminosity/)(float) | Erstellt eine Kopie der Farbe mit der angegebenen Leuchtkraft. |
| [withSaturation](../../com.aspose.html.drawing/color/withsaturation/)(float) | Erstellt eine Kopie der Farbe mit der angegebenen Sättigung. |

### Siehe auch

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
