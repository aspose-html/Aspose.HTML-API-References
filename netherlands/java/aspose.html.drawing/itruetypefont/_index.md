---
title: "ITrueTypeFont Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.drawing.ITrueTypeFont interface. Declareert methoden voor het werken met TrueType-lettertype."
type: docs

url: /nl/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Declareert methoden voor het werken met TrueType-lettertype.

```java
public interface ITrueTypeFont
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Retourneert de grootte van de lettertypegegevens in bytes |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Haal de naam van de lettertypefamilie op. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Dit moet een combinatie zijn van "FamilyName" en "SubFamilyName". Uitzondering: als het lettertype "Regular" is zoals aangegeven in "SubFamilyName", gebruik dan alleen de familienaam die in "FamilyName" staat. Een uitzondering op de bovenstaande definitie van de volledige lettertype‑naam is voor Microsoft‑platformstrings voor CFF OpenType-lettertypen: in dit geval moet de volledige lettertype‑naam exact gelijk zijn aan de PostScript FontName in de CFF Name‑INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) De naam van de subfamilie van het lettertype onderscheidt het lettertype in een groep met dezelfde lettertypefamilienaam. Dit wordt verondersteld stijl (cursief, schuin) en gewicht (licht, vet, zwart, enz.) aan te geven. Een lettertype zonder specifieke verschillen in gewicht of stijl (bijv. gemiddeld gewicht, niet cursief en fsSelection‑bit 6 ingesteld) moet de string "Regular" op deze positie opslaan. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Retourneert de ascent, in punten. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Open de stream met lettertypegegevens. De aanroeper is verantwoordelijk voor het vrijgeven van de stream. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Retourneert de descent, in punten. |

### Zie ook

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
