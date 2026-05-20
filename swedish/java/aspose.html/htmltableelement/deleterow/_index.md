---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableElement-metod. Ta bort en tabellrad"
type: docs

url: /sv/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Ta bort en tabellrad.

```java
public void DeleteRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Indexet för den rad som ska tas bort. Detta index börjar på 0 och är relativt till den logiska ordningen (inte dokumentordningen) för alla rader som finns i tabellen. Om indexet är -1 tas den sista raden i tabellen bort. |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna indexet är större än eller lika med antalet rader eller om indexet är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
