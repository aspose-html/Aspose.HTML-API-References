---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML för .NET API Referens
description: IXPathResult metod. Returnerarindex objektet i ögonblicksbildsamlingen. Omindexär större än eller lika med antalet noder i listan returnerar denna metodnull . Till skillnad från iteratorresultatet blir ögonblicksbilden inte ogiltig men kanske inte motsvarar det aktuella dokumentet om det är muterat.
type: docs
weight: 90
url: /sv/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Returnerar`index` objektet i ögonblicksbildsamlingen. Om`index`är större än eller lika med antalet noder i listan, returnerar denna metod`null` . Till skillnad från iteratorresultatet blir ögonblicksbilden inte ogiltig, men kanske inte motsvarar det aktuella dokumentet om det är muterat.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Indexera till ögonblicksbildsamlingen. |

### Returvärde

Noden vid`index` plats i`NodeList` , eller`null` om är det inte ett giltigt index.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: höjt om`resultatTyp` är inte `UnorderedNodeSnapshot` typ eller`Beställde NodeSnapshot` typ. |

### Se även

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* namnutrymme [Aspose.Html.Dom.XPath](../../ixpathresult/)
* hopsättning [Aspose.HTML](../../../)


