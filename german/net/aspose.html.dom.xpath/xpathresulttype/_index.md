---
title: XPathResultType
second_title: Aspose.HTML für .NET-API-Referenz
description: Ein vorzeichenloser Kurzbefehl der angibt um welche Art von Ergebnis es sich handelt. Wenn ein bestimmter Typangegeben ist wird das Ergebnis als der entsprechende Typ zurückgegeben wobei wo erforderlich und möglich XPathTypkonvertierungen verwendet werden.
type: docs
weight: 2620
url: /de/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Ein vorzeichenloser Kurzbefehl, der angibt, um welche Art von Ergebnis es sich handelt. Wenn ein bestimmter `Typ`angegeben ist, wird das Ergebnis als der entsprechende -Typ zurückgegeben, wobei, wo erforderlich und möglich, XPath-Typkonvertierungen verwendet werden.

```csharp
public enum XPathResultType
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Any | `0` | Dieser Code repräsentiert keinen bestimmten Typ. Eine Auswertung eines XPath-Ausdrucks wird niemals diesen Typ erzeugen. Wenn dieser Typ angefordert wird, gibt die Auswertung zurück, welcher Typ auch immer sich natürlich aus der Auswertung des Ausdrucks ergibt. Wenn das natürliche -Ergebnis ein Knotensatz ist, wenn`Irgendein` Typ wurde dann angefordert`UnorderedNodeIterator` ist immer der resultierende Typ. Jede andere Darstellung eines Knotensatzes muss explizit angefordert werden. |
| Number | `1` | Das Ergebnis ist eine Zahl wie in [XPath 1.0] definiert. Die Änderung des Dokuments macht die Nummer nicht ungültig, kann aber bedeuten, dass eine Neubewertung nicht dieselbe Nummer ergeben würde. |
| String | `2` | Das Ergebnis ist eine Zeichenfolge gemäß der Definition von [XPath 1.0]. Die Änderung des Dokuments macht den String nicht ungültig, kann aber bedeuten, dass der String nicht mehr dem aktuellen Dokument entspricht. |
| Boolean | `3` | Das Ergebnis ist ein boolescher Wert gemäß der Definition von [XPath 1.0]. Die Änderung des Dokuments macht den booleschen Wert nicht ungültig, kann aber bedeuten, dass eine Neubewertung nicht denselben booleschen Wert ergeben würde. |
| UnorderedNodeIterator | `4` | Das Ergebnis ist ein Knotensatz wie in [XPath 1.0] definiert, auf den iterativ zugegriffen wird, der möglicherweise keine Knoten in einer bestimmten Reihenfolge erzeugt. Die Dokumentänderung macht die -Iteration ungültig. Dies ist der Standardtyp, der zurückgegeben wird, wenn das Ergebnis ein Knotensatz und ist`Irgendein` Typ wird angefordert. |
| OrderedNodeIterator | `5` | Das Ergebnis ist ein Knotensatz wie in [XPath 1.0] definiert, auf den iterativ zugegriffen wird, was dokumentengeordnete Knoten erzeugt. Dokumentänderung macht die Iteration ungültig. |
| UnorderedNodeSnapshot | `6` | Das Ergebnis ist ein Knotensatz gemäß der Definition von [XPath 1.0], auf den als Snapshot-Liste von Knoten zugegriffen wird, die sich möglicherweise nicht in einer bestimmten Reihenfolge befinden. Die Änderung des Dokuments macht den Schnappschuss nicht ungültig, kann aber bedeuten, dass eine Neubewertung nicht denselben Schnappschuss ergeben würde und Knoten im Schnappschuss möglicherweise geändert, verschoben oder aus dem Dokument entfernt wurden. |
| OrderedNodeSnapshot | `7` | Das Ergebnis ist ein Knotensatz wie in [XPath 1.0] definiert, auf den als Snapshot-Liste von Knoten zugegriffen wird, die sich in der Reihenfolge des Originaldokuments befinden. Die Änderung des Dokuments macht den Schnappschuss nicht ungültig, kann aber bedeuten, dass eine Neubewertung nicht denselben Schnappschuss ergeben würde und Knoten im Schnappschuss möglicherweise geändert, verschoben oder aus dem Dokument entfernt wurden. |
| AnyUnorderedNode | `8` | Das Ergebnis ist ein Knotensatz wie in [XPath 1.0] definiert und auf den als einzelner Knoten zugegriffen wird, was sein kann`Null`wenn die Knotenmenge leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können aber dazu führen, dass der Ergebnisknoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Annehmlichkeit, die eine Optimierung ermöglicht, da die Implementierung beendet werden kann, sobald irgendein -Knoten in der Ergebnismenge gefunden wurde. Wenn das tatsächliche Ergebnis mehr als einen Knoten enthält, ist der zurückgegebene einzelne Knoten möglicherweise nicht der erste in der Dokumentreihenfolge. |
| FirstOrderedNode | `9` | Das Ergebnis ist ein Knotensatz wie in [XPath 1.0] definiert und auf den als einzelner Knoten zugegriffen wird, was sein kann`Null`wenn die Knotenmenge leer ist. Dokumentänderungen machen den Knoten nicht ungültig, können aber dazu führen, dass der Ergebnisknoten nicht mehr dem aktuellen Dokument entspricht. Dies ist eine Annehmlichkeit, die eine Optimierung erlaubt, da die Implementierung anhalten kann, sobald der erste Knoten in der Dokumentenreihenfolge der resultierenden Menge gefunden wurde. Wenn das tatsächliche Ergebnis mehr als einen -Knoten enthält, ist der zurückgegebene einzelne Knoten der erste in der Dokumentreihenfolge. |

### Siehe auch

* namensraum [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
