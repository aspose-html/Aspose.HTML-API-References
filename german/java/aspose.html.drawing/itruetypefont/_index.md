---
title: "ITrueTypeFont‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.drawing.ITrueTypeFont‑Schnittstelle. Deklariert Methoden zur Arbeit mit TrueType‑Schrift."
type: docs

url: /de/java/com.aspose.html.drawing/itruetypefont/
---
## ITrueTypeFont interface

Deklariert Methoden zur Arbeit mit TrueType‑Schriftarten.

```java
public interface ITrueTypeFont
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getDataSize](../../com.aspose.html.drawing/itruetypefont/datasize/) Gibt die Größe der Schriftartdaten in Bytes zurück. |
| [getFamilyName](../../com.aspose.html.drawing/itruetypefont/familyname/) Gibt den Namen der Schriftfamilie zurück. |
| [getFullFontName](../../com.aspose.html.drawing/itruetypefont/fullfontname/) Dies sollte eine Kombination aus \"FamilyName\" und \"SubFamilyName\" sein. Ausnahme: Wenn die Schriftart \"Regular\" ist, wie in \"SubFamilyName\" angegeben, dann verwende nur den Familiennamen aus \"FamilyName\". Eine Ausnahme von der obigen Definition des vollständigen Schriftnamens gilt für Microsoft‑Plattform‑Strings für CFF‑OpenType‑Schriften: In diesem Fall muss der String des vollständigen Schriftnamens identisch sein mit dem PostScript‑FontName im CFF‑Name‑INDEX. |
| [getSubFamilyName](../../com.aspose.html.drawing/itruetypefont/subfamilyname/) Der Subfamilienname der Schrift unterscheidet die Schrift in einer Gruppe mit demselben Schriftfamiliennamen. Dies soll Stil (kursiv, schräg) und Gewicht (leicht, fett, schwarz usw.) adressieren. Eine Schrift ohne besondere Unterschiede in Gewicht oder Stil (z. B. mittleres Gewicht, nicht kursiv und fsSelection‑Bit 6 gesetzt) sollte den String \"Regular\" an dieser Stelle speichern. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [getAscent](../../com.aspose.html.drawing/itruetypefont/getascent/)(float) | Gibt den Aufstieg in Punkten zurück. |
| [getData](../../com.aspose.html.drawing/itruetypefont/getdata/)() | Öffnet den Stream mit Schriftartdaten. Der Aufrufer ist für das Freigeben des Streams verantwortlich. |
| [getDescent](../../com.aspose.html.drawing/itruetypefont/getdescent/)(float) | Gibt den Abstieg in Punkten zurück. |

### Siehe auch

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
