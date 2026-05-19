---
title: "IXPathResult-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.xpath.IXPathResult interface. De XPathResult-interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een specifiek knooppunt. Aangezien de evaluatie van een XPath-expressie kan leiden tot verschillende resultaatssoorten, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

De `XPathResult`-interface vertegenwoordigt het resultaat van de evaluatie van een XPath 1.0-expressie binnen de context van een specifieke knoop. Aangezien de evaluatie van een XPath-expressie kan resulteren in verschillende resultaatssoorten, maakt dit object het mogelijk om het type en de waarde van het resultaat te ontdekken en te manipuleren.

```java
public interface IXPathResult
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) De waarde van dit booleaanse resultaat. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Geeft aan dat de iterator ongeldig is geworden. Waar als `resultType` is `UnorderedNodeIterator` of `OrderedNodeIterator` type en het document is gewijzigd sinds dit resultaat werd geretourneerd. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) De waarde van dit numerieke resultaat. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Een code die het type van dit resultaat vertegenwoordigt, zoals gedefinieerd door de http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) De waarde van dit enkele knooppuntresultaat, die `null` kan zijn. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Het aantal knooppunten in de resultaat‑snapshot. Geldige waarden voor snapshotItem‑indices zijn `0` tot en met `snapshotLength-1`. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) De waarde van dit String‑resultaat. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itereert en retourneert het volgende knooppunt uit de knooppuntset of `null` als er geen knooppunten meer zijn. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Retourneert het `index`‑de item in de snapshot‑collectie. Als `index` groter dan of gelijk is aan het aantal knooppunten in de lijst, geeft deze methode `null` terug. In tegenstelling tot het iterator‑resultaat wordt de snapshot niet ongeldig, maar kan deze mogelijk niet overeenkomen met het huidige document als dat is gewijzigd. |

### Zie ook

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
