---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLTableSectionElement methode. Voeg een rij toe aan deze sectie. De nieuwe rij wordt onmiddellijk ingevoegd direct vóór de huidige indexth‑rij in deze sectie. Als index -1 is of gelijk aan het aantal rijen in deze sectie, wordt de nieuwe rij toegevoegd"
type: docs

url: /nl/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Voeg een rij toe aan deze sectie. De nieuwe rij wordt onmiddellijk vóór de huidige `index`-de rij in deze sectie ingevoegd. Als `index` -1 is of gelijk aan het aantal rijen in deze sectie, wordt de nieuwe rij toegevoegd.

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | Het rijnummer waar een nieuwe rij moet worden ingevoegd. Deze index begint bij 0 en is alleen relatief ten opzichte van de rijen die zich binnen deze sectie bevinden, niet alle rijen in de tabel. |

### Retourwaarde

De nieuw aangemaakte rij.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Opgetreden als de opgegeven index groter is dan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
