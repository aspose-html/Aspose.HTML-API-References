---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "INodeIterator-Methode. Gibt den nächsten Knoten im Satz zurück und bewegt die Position des Iterators im Satz vorwärts. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode den ersten Knoten im Satz."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Gibt den nächsten Knoten im Satz zurück und verschiebt die Position des Iterators im Satz nach vorne. Nach dem Erzeugen eines NodeIterator gibt der erste Aufruf von nextNode() den ersten Knoten im Satz zurück.

```java
public Node NextNode()
```

### Rückgabewert

Der nächste Node im iterierten Satz, oder null, wenn es keine weiteren Elemente in diesem Satz gibt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Wird ausgelöst, wenn diese Methode aufgerufen wird, nachdem die detach‑Methode aufgerufen wurde. |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
