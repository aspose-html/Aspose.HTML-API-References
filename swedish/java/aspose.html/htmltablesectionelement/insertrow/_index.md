---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableSectionElement method. Infoga en rad i detta avsnitt. Den nya raden infogas omedelbart före den aktuella index‑rad i detta avsnitt. Om index är -1 eller lika med antalet rader i detta avsnitt läggs den nya raden till i slutet"
type: docs

url: /sv/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Infoga en rad i detta avsnitt. Den nya raden infogas omedelbart före den aktuella `index`‑te raden i detta avsnitt. Om `index` är -1 eller lika med antalet rader i detta avsnitt, läggs den nya raden till i slutet.

```java
public HTMLElement InsertRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Radnumret där en ny rad ska infogas. Detta index startar från 0 och är endast relativt till raderna som finns i detta avsnitt, inte alla rader i tabellen. |

### Returvärde

Den nyss skapade raden.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna indexet är större än antalet rader eller om indexet är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
