---
title: Interface IXPathResult
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Dom.XPath.IXPathResult koppel. DieXPathResult interface stellt das Ergebnis der Auswertung eines XPath 1.0Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPathAusdrucks zu verschiedenen Ergebnistypen führen kann macht es dieses Objekt möglich Typ und Wert des Ergebnisses zu ermitteln und zu manipulieren.
type: docs
weight: 2600
url: /de/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

Die`XPathResult` interface stellt das Ergebnis der Auswertung eines XPath 1.0-Ausdrucks im Kontext eines bestimmten Knotens dar. Da die Auswertung eines XPath-Ausdrucks zu verschiedenen Ergebnistypen führen kann, macht es dieses Objekt möglich, Typ und Wert des Ergebnisses zu ermitteln und zu manipulieren.

```csharp
public interface IXPathResult
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | Der Wert dieses booleschen Ergebnisses. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Gibt an, dass der Iterator ungültig geworden ist. Wahr, wenn`resultType` ist`UnorderedNodeIterator` tippe bzw`OrderedNodeIterator` type und das Dokument wurde geändert, seit dieses Ergebnis zurückgegeben wurde. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | Der Wert dieses Zahlenergebnisses. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | Ein Code, der den Typ dieses Ergebnisses darstellt, wie durch definiert http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) enum. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Der Wert dieses einzelnen Knotenergebnisses, der sein kann`Null` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Die Anzahl der Knoten im Ergebnis-Snapshot. Gültige Werte für die Indizes von snapshotItem sind`0` Zu`Schnappschusslänge-1` inklusive. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | Der Wert dieses Zeichenfolgenergebnisses. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Iteriert und gibt den nächsten Knoten aus dem Knotensatz zurück oder`Null` wenn es keine Knoten mehr gibt. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Gibt die zurück`Index` Artikel in der Schnappschuss-Sammlung. Wenn`Index`größer als oder gleich der Anzahl der Knoten in der Liste ist, gibt diese Methode zurück`Null` . Im Gegensatz zum Ergebnis des -Iterators wird der Schnappschuss nicht ungültig, entspricht aber möglicherweise nicht dem aktuellen -Dokument, wenn es mutiert wird. |

### Siehe auch

* namensraum [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* Montage [Aspose.HTML](../../)


