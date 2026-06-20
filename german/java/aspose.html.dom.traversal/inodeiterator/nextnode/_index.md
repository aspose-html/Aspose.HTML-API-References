---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "INodeIterator-Methode. Gibt den nächsten Knoten im Satz zurück und bewegt die Position des Iterators im Satz vorwärts. Nachdem ein NodeIterator erstellt wurde, gibt der erste Aufruf von nextNode den ersten Knoten im Satz zurück."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Gibt den nächsten Knoten in der Menge zurück und verschiebt die Position des Iterators in der Menge nach vorne. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode() den ersten Knoten in der Menge.

```java
public Node NextNode()
```

### Rückgabewert

Der nächste Knoten im iterierten Satz oder null, wenn keine weiteren Elemente in diesem Satz vorhanden sind.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Wird ausgelöst, wenn diese Methode nach dem Aufruf von detach aufgerufen wird. |

### Siehe auch

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
