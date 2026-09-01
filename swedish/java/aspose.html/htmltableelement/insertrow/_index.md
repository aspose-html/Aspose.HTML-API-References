---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML för Java API-referens"
description: "HTMLTableElement-metod. Infoga en ny tom rad i tabellen. Den nya raden infogas omedelbart före och i samma sektion som den aktuella raden med index i tabellen. Om index är -1 eller lika med antalet rader läggs den nya raden till i slutet. Dessutom, när tabellen är tom, infogas raden i ett TBODY som skapas och infogas i tabellen. En tabellrad kan inte vara tom enligt HTML 4.01"
type: docs

url: /sv/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Infoga en ny tom rad i tabellen. Den nya raden infogas omedelbart före och i samma sektion som den aktuella `index`te raden i tabellen. Om `index` är -1 eller lika med antalet rader, läggs den nya raden till i slutet. Dessutom, när tabellen är tom infogas raden i ett `TBODY` som skapas och infogas i tabellen. En tabellrad får inte vara tom enligt [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```java
public Node InsertRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Radnumret där en ny rad ska infogas. Detta index börjar på 0 och är relativt till den logiska ordningen (inte dokumentordningen) för alla rader som finns i tabellen. |

### Returvärde

Den nyss skapade raden.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Uppstår om det angivna indexet är större än antalet rader eller om indexet är ett negativt tal annat än -1. @version DOM Level 2 |

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
