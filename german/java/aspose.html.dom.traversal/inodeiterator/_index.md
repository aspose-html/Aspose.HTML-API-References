---
title: "INodeIterator Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.INodeIterator Schnittstelle. Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge der Knoten in einer NodeList, den Dokumententeilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Traversierung von Dokumenten in Dokumentreihenfolge eines Teilbaums. Instanzen dieser Iteratoren werden erzeugt, indem DocumentTraversal.createNodeIterator aufgerufen wird."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotenmengen. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Dokumentreihenfolge‑Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator().

Siehe auch die [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Der Wert dieses Flags bestimmt, ob die Kinder von Entity-Reference-Knoten für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen abgelehnt. Beachten Sie, dass diese Ablehnung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen kompletten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, in der Entity-References erweitert sind und der Entity-Reference-Knoten selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den Entity-Reference-Knoten zu verbergen, und setzen Sie expandEntityReferences beim Erzeugen des Iterators auf true. Um eine Ansicht zu erzeugen, die Entity-Reference‑Knoten enthält, aber keine Entity‑Erweiterung, verwenden Sie die whatToShow‑Flags, um den Entity-Reference-Knoten anzuzeigen, und setzen Sie expandEntityReferences auf false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Der aktuelle Referenzknoten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Löst die Bindung des NodeIterator vom Satz, über den er iteriert hat, löst alle Rechenressourcen und versetzt den Iterator in den INVALID‑Zustand. Nachdem detach aufgerufen wurde, führen Aufrufe von nextNode oder previousNode zu der Ausnahme INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Gibt den nächsten Knoten im Satz zurück und verschiebt die Position des Iterators im Satz nach vorne. Nach dem Erzeugen eines NodeIterator gibt der erste Aufruf von nextNode() den ersten Knoten im Satz zurück. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Gibt den vorherigen Knoten im Satz zurück und verschiebt die Position des NodeIterator rückwärts im Satz. |

### Siehe auch

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
