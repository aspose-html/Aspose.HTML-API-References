---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML för .NET API Referens
description: SVGListBase metod. Infogar ett nytt objekt i listan på den angivna positionen. Den första artikeln är nummer 0.
type: docs
weight: 90
url: /sv/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Infogar ett nytt objekt i listan på den angivna positionen. Den första artikeln är nummer 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newItem | T | Objektet som ska infogas i listan. |
| index | UInt64 | Indexet för objektet innan det nya objektet ska infogas. Den första posten är nummer 0. Om indexet är lika med 0, så infogas den nya posten längst fram i listan. Om indexet är större än eller lika med numberOfItems, läggs det nya objektet till i slutet av listan. |

### Returvärde

Det infogade objektet.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Koda[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Ökas när listan inte kan ändras. |

### Se även

* class [SVGListBase&lt;T&gt;](../)
* namnutrymme [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* hopsättning [Aspose.HTML](../../../)


