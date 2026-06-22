---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML voor Java API-referentie"
description: "HTMLTableElement methode. Verwijder een tabelrij."
type: docs

url: /nl/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Verwijder een tabelrij.

```java
public void DeleteRow(int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | Int32 | De index van de rij die moet worden verwijderd. Deze index begint bij 0 en is relatief ten opzichte van de logische volgorde (niet de documentvolgorde) van alle rijen die zich in de tabel bevinden. Als de index -1 is, wordt de laatste rij in de tabel verwijderd. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Opgetreden als de opgegeven index groter dan of gelijk is aan het aantal rijen of als de index een negatief getal is anders dan -1. @version DOM Level 2 |

### Zie ook

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
