---
title: "IXPathResult.SnapshotItem"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathResult-metod. Returnerar det indexte elementet i snapshot-samlingen. Om index är större än eller lika med antalet noder i listan returnerar denna metod null. Till skillnad från iteratorresultatet blir snapshotet inte ogiltigt men kan eventuellt inte motsvara det aktuella dokumentet om det har förändrats."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

Returnerar det `index`‑te elementet i snapshot‑samlingen. Om `index` är större än eller lika med antalet noder i listan returnerar metoden `null`. Till skillnad från iteratorresultatet blir snapshotet inte ogiltigt, men kan avvika från det aktuella dokumentet om det har förändrats.

```java
public Node SnapshotItem(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index i snapshot-samlingen. |

### Returvärde

Noden på `index`-positionen i `NodeList`, eller `null` om det inte är ett giltigt index.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: kastas om `resultType` inte är `UnorderedNodeSnapshot`-typ eller `OrderedNodeSnapshot`-typ. |

### Se även

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
