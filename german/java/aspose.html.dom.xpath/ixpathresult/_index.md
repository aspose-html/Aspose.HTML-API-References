---
title: "IXPathResult-Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.xpath.IXPathResult-Schnittstelle. Die XPathResult-Schnittstelle stellt das Ergebnis der Auswertung eines XPath‑1.0‑Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPath‑Ausdrucks zu verschiedenen Ergebnis­typen führen kann, ermöglicht dieses Objekt das Erkennen und Manipulieren des Typs und des Werts des Ergebnisses."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Das Interface `XPathResult` stellt das Ergebnis der Auswertung eines XPath‑1.0‑Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPath‑Ausdrucks zu verschiedenen Ergebnis‑Typen führen kann, ermöglicht dieses Objekt das Erkennen und Manipulieren des Typs und des Werts des Ergebnisses.

```java
public interface IXPathResult
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) Der Wert dieses booleschen Ergebnisses. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Zeigt an, dass der Iterator ungültig geworden ist. Wahr, wenn `resultType` vom Typ `UnorderedNodeIterator` oder `OrderedNodeIterator` ist und das Dokument seit der Rückgabe dieses Ergebnisses geändert wurde. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) Der Wert dieses numerischen Ergebnisses. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Ein Code, der den Typ dieses Ergebnisses darstellt, wie im http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/)‑Enum definiert. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) Der Wert dieses einzelnen Knotenergebnisses, der `null` sein kann. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) Die Anzahl der Knoten im Ergebnis‑Snapshot. Gültige Werte für snapshotItem‑Indizes sind `0` bis `snapshotLength-1` inklusive. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) Der Wert dieses String‑Ergebnisses. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Iteriert und gibt den nächsten Knoten aus dem Knotensatz zurück oder `null`, wenn keine weiteren Knoten vorhanden sind. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Gibt das `index`‑te Element in der Snapshot‑Sammlung zurück. Wenn `index` größer oder gleich der Anzahl der Knoten in der Liste ist, liefert diese Methode `null`. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch bei einer Veränderung des Dokuments nicht mehr dem aktuellen Dokument entsprechen. |

### Siehe auch

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
