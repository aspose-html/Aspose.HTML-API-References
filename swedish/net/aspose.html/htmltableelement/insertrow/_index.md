---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML för .NET API Referens
description: HTMLTableElement metod. Infoga en ny tom rad i tabellen. Den nya raden infogas omedelbart före och i samma avsnitt som den nuvarande index raden i tabellen. Omindex är 1 eller lika med antalet rader läggs den nya raden till. Dessutom när tabellen är tom infogas raden i enTBODY som skapas och infogas i tabellen. En tabellrad kan inte vara tom enligt HTML 4.01 .
type: docs
weight: 220
url: /sv/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Infoga en ny tom rad i tabellen. Den nya raden infogas omedelbart före och i samma avsnitt som den nuvarande `index` raden i tabellen. Om`index` är -1 eller lika med antalet rader, läggs den nya raden till. Dessutom, när tabellen är tom infogas raden i en`TBODY` som skapas och infogas i tabellen. En tabellrad kan inte vara tom enligt [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Radnumret där en ny rad ska infogas. Detta index börjar från 0 och är relativt till den logiska ordningen (inte dokument order) för alla rader som finns i tabellen. |

### Returvärde

Den nyskapade raden.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Ökas om det angivna indexet är större än antalet rader eller om indexet är ett negativt tal annat än -1. @version DOM nivå 2 |

### Se även

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* namnutrymme [Aspose.Html](../../htmltableelement/)
* hopsättning [Aspose.HTML](../../../)


