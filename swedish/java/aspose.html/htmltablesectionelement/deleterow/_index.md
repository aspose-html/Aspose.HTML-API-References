---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableSectionElement metod. Ta bort en rad från detta avsnitt"
type: docs

url: /sv/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Ta bort en rad från detta avsnitt.

```java
public void DeleteRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Indexet för raden som ska tas bort, eller -1 för att ta bort den sista raden. Detta index börjar på 0 och är endast relativt till raderna som finns i detta avsnitt, inte alla rader i tabellen. |

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna indexet är större än eller lika med antalet rader eller om indexet är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
