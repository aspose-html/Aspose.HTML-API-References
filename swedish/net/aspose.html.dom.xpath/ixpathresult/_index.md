---
title: Interface IXPathResult
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.XPath.IXPathResult gränssnitt. DenXPathResult gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0uttryck inom ramen för en viss nod. Eftersom utvärdering av ett XPathuttryck kan resultera i olika resultattyper gör detta objekt det möjligt att upptäcka och manipulera typen och värdet av resultatet.
type: docs
weight: 2600
url: /sv/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Den`XPathResult` gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0-uttryck inom ramen för en viss nod. Eftersom utvärdering av ett XPath-uttryck kan resultera i olika resultattyper, gör detta objekt det möjligt att upptäcka och manipulera typen och värdet av resultatet.

```csharp
public interface IXPathResult
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | Värdet för detta booleska resultat. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Betyder att iteratorn har blivit ogiltig. Sant om`resultatTyp` är`UnorderedNodeIterator` typ eller`Beställde NodeIterator` typ och dokumentet har ändrats sedan detta resultat returnerades. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | Värdet för detta talresultat. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | En kod som representerar typen av detta resultat, enligt definitionen av http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Värdet för detta enda nodresultat, vilket kan vara`null` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Antalet noder i resultatets ögonblicksbild. Giltiga värden för snapshotItem index är`0` till`snapshotLength-1` inklusive. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | Värdet för detta strängresultat. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itererar och returnerar nästa nod från noduppsättningen eller`null` om det inte finns fler noder. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Returnerar`index` objektet i ögonblicksbildsamlingen. Om`index`är större än eller lika med antalet noder i listan, returnerar denna metod`null` . Till skillnad från iteratorresultatet blir ögonblicksbilden inte ogiltig, men kanske inte motsvarar det aktuella dokumentet om det är muterat. |

### Se även

* namnutrymme [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* hopsättning [Aspose.HTML](../../)


