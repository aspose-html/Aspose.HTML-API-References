---
title: "IXPathResult-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.xpath.IXPathResult-gränssnitt. XPathResult-gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0-uttryck inom kontexten för en specifik nod. Eftersom utvärderingen av ett XPath-uttryck kan ge olika resultattyper möjliggör detta objekt att upptäcka och manipulera typ och värde för resultatet"
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult`-gränssnittet representerar resultatet av utvärderingen av ett XPath 1.0-uttryck inom kontexten av en specifik nod. Eftersom utvärderingen av ett XPath-uttryck kan leda till olika resultattyper, möjliggör detta objekt att upptäcka och manipulera typ och värde på resultatet.

```java
public interface IXPathResult
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Värdet av detta booleska resultat. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Anger att iteratorn har blivit ogiltig. Sant om `resultType` är av typen `UnorderedNodeIterator` eller `OrderedNodeIterator` och dokumentet har ändrats sedan detta resultat returnerades. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Värdet av detta numeriska resultat. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) En kod som representerar typen av detta resultat, enligt den http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Värdet för detta enkelnodresultat, vilket kan vara `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Antalet noder i resultatögonblicksbilden. Giltiga värden för snapshotItem-index är `0` till `snapshotLength-1` inklusive. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Värdet för detta Strängresultat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itererar och returnerar nästa nod från nodmängden eller `null` om det inte finns fler noder. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Returnerar det `index`:e elementet i ögonblicksbildsamlingen. Om `index` är större än eller lika med antalet noder i listan returnerar metoden `null`. Till skillnad från iteratorresultatet blir ögonblicksbilden inte ogiltig, men kan avvika från det aktuella dokumentet om det har förändrats. |

### Se även

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
