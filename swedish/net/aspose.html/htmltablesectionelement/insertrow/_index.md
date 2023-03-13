---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML för .NET API Referens
description: HTMLTableSectionElement metod. Infoga en rad i det här avsnittet. Den nya raden infogas omedelbart före den nuvarandeindex raden i detta avsnitt. Om index är 1 eller lika med antalet rader i denna sektion läggs den nya raden till.
type: docs
weight: 70
url: /sv/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Infoga en rad i det här avsnittet. Den nya raden infogas omedelbart före den nuvarande`index` raden i detta avsnitt. Om `index` är -1 eller lika med antalet rader i denna -sektion, läggs den nya raden till.

```csharp
public HTMLElement InsertRow(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Radnumret där en ny rad ska infogas. Detta index börjar från 0 och är endast relativt till raderna som finns i detta avsnitt, inte alla rader i tabellen. |

### Returvärde

Den nyskapade raden.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Ökas om det angivna indexet är större än antalet rader för om indexet är ett negativt tal annat än -1. @version DOM Nivå 2 |

### Se även

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* namnutrymme [Aspose.Html](../../htmltablesectionelement/)
* hopsättning [Aspose.HTML](../../../)


