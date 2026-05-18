---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "INodeIterator property. Der Wert dieses Flags bestimmt, ob die Kinder von entity reference nodes für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen verworfen. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen kompletten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, in der entity references expandiert sind und der entity reference node selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den entity reference node zu verbergen, und setzen Sie expandEntityReferences beim Erstellen des Iterators auf true. Um eine Ansicht des Dokuments zu erzeugen, in der entity reference nodes vorhanden sind, aber keine Expansion erfolgt, verwenden Sie die whatToShow‑Flags, um den entity reference node anzuzeigen, und setzen Sie expandEntityReferences auf false."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Der Wert dieses Flags bestimmt, ob die Kinder von entity reference nodes für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen verworfen. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen kompletten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, in der entity references expandiert sind und der entity reference node selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den entity reference node zu verbergen, und setzen Sie expandEntityReferences beim Erstellen des Iterators auf true. Um eine Ansicht des Dokuments zu erzeugen, in der entity reference nodes vorhanden sind, aber keine Expansion erfolgt, verwenden Sie die whatToShow‑Flags, um den entity reference node anzuzeigen, und setzen Sie expandEntityReferences auf false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` wenn [expand entity references]; andernfalls `false`.

### Siehe auch

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
