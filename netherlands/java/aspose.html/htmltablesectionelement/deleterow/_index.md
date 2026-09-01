---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLTableSectionElement methode. Verwijder een rij uit deze sectie"
type: docs

url: /nl/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Verwijder een rij uit deze sectie.

```java
public void DeleteRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | De index van de te verwijderen rij, of -1 om de laatste rij te verwijderen. Deze index begint bij 0 en is alleen relatief ten opzichte van de rijen die zich binnen deze sectie bevinden, niet alle rijen in de tabel. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Opgetreden als de opgegeven index groter dan of gelijk is aan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
