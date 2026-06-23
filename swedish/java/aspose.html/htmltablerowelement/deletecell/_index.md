---
title: "HTMLTableRowElement.DeleteCell"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableRowElement metod. Ta bort en cell från den aktuella raden"
type: docs

url: /sv/java/com.aspose.html/htmltablerowelement/deletecell/
---
## HTMLTableRowElement.DeleteCell method

Ta bort en cell från den aktuella raden.

```java
public void DeleteCell(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Indexet för den cell som ska tas bort, med start från 0. Om indexet är -1 tas den sista cellen i raden bort. |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna `index` är större än eller lika med antalet celler eller om indexet är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
