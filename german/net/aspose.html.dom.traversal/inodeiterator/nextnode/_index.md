---
title: INodeIterator.NextNode
second_title: Aspose.HTML für .NET-API-Referenz
description: INodeIterator methode. Gibt den nächsten Knoten in der Menge zurück und rückt die Position des Iterators in der Menge vor. Nachdem ein NodeIterator erstellt wurde gibt der erste Aufruf von nextNode den ersten Knoten in der Menge zurück.
type: docs
weight: 40
url: /de/net/aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Gibt den nächsten Knoten in der Menge zurück und rückt die Position des Iterators in der Menge vor. Nachdem ein NodeIterator erstellt wurde, gibt der erste Aufruf von nextNode() den ersten Knoten in der Menge zurück.

```csharp
public Node NextNode()
```

### Rückgabewert

Der nächste Knoten in der Menge, über die iteriert wird, oder null, wenn es keine weiteren Mitglieder in dieser Menge gibt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: Wird ausgelöst, wenn diese Methode aufgerufen wird, nachdem die Methode detach aufgerufen wurde. |

### Siehe auch

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeIterator](../)
* namensraum [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* Montage [Aspose.HTML](../../../)


