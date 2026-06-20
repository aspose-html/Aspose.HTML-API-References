---
title: "IXPathResult.IterateNext"
second_title: "Aspose.HTML für Java API-Referenz"
description: "IXPathResult-Methode. Durchläuft und gibt den nächsten Knoten aus dem Knotensatz zurück oder null, wenn keine weiteren Knoten mehr vorhanden sind."
type: docs

url: /de/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Iteriert und gibt den nächsten Knoten aus dem Knotensatz zurück oder `null`, wenn keine weiteren Knoten vorhanden sind.

```java
public Node IterateNext()
```

### Rückgabewert

Gibt den nächsten Knoten zurück.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: ausgelöst, wenn `resultType` nicht vom Typ `UnorderedNodeIterator` oder `OrderedNodeIterator` ist. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Das Dokument wurde verändert, seit das Ergebnis zurückgegeben wurde. |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
