---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML für .NET-API-Referenz
description: IXPathResult methode. Gibt die zurückIndex Artikel in der SchnappschussSammlung. WennIndexgrößer als oder gleich der Anzahl der Knoten in der Liste ist gibt diese Methode zurückNull . Im Gegensatz zum Ergebnis des Iterators wird der Schnappschuss nicht ungültig entspricht aber möglicherweise nicht dem aktuellen Dokument wenn es mutiert wird.
type: docs
weight: 90
url: /de/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Gibt die zurück`Index` Artikel in der Schnappschuss-Sammlung. Wenn`Index`größer als oder gleich der Anzahl der Knoten in der Liste ist, gibt diese Methode zurück`Null` . Im Gegensatz zum Ergebnis des -Iterators wird der Schnappschuss nicht ungültig, entspricht aber möglicherweise nicht dem aktuellen -Dokument, wenn es mutiert wird.

```csharp
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index in die Snapshot-Sammlung. |

### Rückgabewert

Der Knoten an der`Index` Platz in der`Knotenliste` , oder`Null` wenn kein gültiger Index ist.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: ausgelöst, wenn`resultType` ist nicht `UnorderedNodeSnapshot` tippe bzw`OrderedNodeSnapshot` Typ. |

### Siehe auch

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* namensraum [Aspose.Html.Dom.XPath](../../ixpathresult/)
* Montage [Aspose.HTML](../../../)


