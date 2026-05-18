---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IXPathResult method. Gibt das Element an der index‑ten Position in der Snapshot‑Sammlung zurück. Wenn index größer oder gleich der Anzahl der Knoten in der Liste ist, liefert diese Methode null. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch nicht mit dem aktuellen Dokument übereinstimmen, wenn es verändert wurde."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Gibt das `index`‑te Element in der Snapshot‑Sammlung zurück. Wenn `index` größer oder gleich der Anzahl der Knoten in der Liste ist, liefert diese Methode `null`. Im Gegensatz zum Iterator‑Ergebnis wird der Snapshot nicht ungültig, kann jedoch bei einer Änderung des Dokuments nicht mehr dem aktuellen Dokument entsprechen.

```java
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index in die Snapshot‑Sammlung. |

### Rückgabewert

Der Knoten an der `index`‑ten Position in der `NodeList` oder `null`, wenn dies kein gültiger Index ist.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: ausgelöst, wenn `resultType` nicht vom Typ `UnorderedNodeSnapshot` oder `OrderedNodeSnapshot` ist. |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
