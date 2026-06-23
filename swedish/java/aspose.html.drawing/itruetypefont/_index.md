---
title: "ITrueTypeFont‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.drawing.ITrueTypeFont‑gränssnitt. Deklarerar metoder för att arbeta med TrueType‑font"
type: docs

url: /sv/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Deklarerar metoder för att arbeta med TrueType-typsnitt.

```java
public interface ITrueTypeFont
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Returnerar storleken på fontdata i byte |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Hämta namnet på teckensnittsfamiljen. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Detta bör vara en kombination av "FamilyName" och "SubFamilyName". Undantag: om teckensnittet är "Regular" enligt "SubFamilyName", använd då endast familjenamnet som finns i "FamilyName". Ett undantag från ovanstående definition av Full font name gäller för Microsoft‑plattformens strängar för CFF OpenType‑fonter: i detta fall måste Full font name‑strängen vara identisk med PostScript‑FontName i CFF Name‑INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Font‑subfamiljenamnet särskiljer teckensnittet i en grupp med samma Font‑Family‑namn. Detta antas hantera stil (italic, oblique) och vikt (light, bold, black, etc.). Ett teckensnitt utan särskilda skillnader i vikt eller stil (t.ex. medium vikt, inte italic och fsSelection‑bit 6 satt) bör ha String‑värdet "Regular" lagrat på denna position. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Returnerar ascent, i punkter. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Öppna strömmen med fontdata. Anroparen ansvarar för att disponera strömmen. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Returnerar descent, i punkter. |

### Se även

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
