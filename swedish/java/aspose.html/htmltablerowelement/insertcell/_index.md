---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableRowElement-metod. Infoga en tom TD-cell i den här raden. Om index är -1 eller lika med antalet celler läggs den nya cellen till i slutet"
type: docs

url: /sv/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Infoga en tom `TD`-cell i den här raden. Om `index` är -1 eller lika med antalet celler, läggs den nya cellen till i slutet.

```java
public HTMLElement InsertCell(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Platsen där cellen ska infogas, räknat från 0. |

### Returvärde

Den nyss skapade cellen.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna `index` är större än antalet celler eller om index är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
