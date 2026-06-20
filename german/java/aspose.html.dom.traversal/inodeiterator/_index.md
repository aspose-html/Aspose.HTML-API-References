---
title: "INodeIterator Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.INodeIterator‑Schnittstelle. Iteratoren werden verwendet, um durch eine Menge von Knoten zu schritteln, z. B. die Menge von Knoten in einer NodeList, den Dokument‑Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Traversierung eines Dokument‑Teilbaums in Dokumentreihenfolge. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator erstellt."
type: docs

url: /de/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge‑Durchquerung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator() erstellt.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Der Wert dieses Flags bestimmt, ob die Kinder von Entity‑Reference‑Knoten für den Iterator sichtbar sind. Wenn false, werden sie und ihre Nachkommen verworfen. Beachten Sie, dass diese Verwerfung Vorrang vor whatToShow und dem Filter hat. Außerdem ist dies derzeit die einzige Situation, in der NodeIterators einen gesamten Teilbaum ablehnen können, anstatt einzelne Knoten zu überspringen. Um eine Ansicht des Dokuments zu erzeugen, bei der Entity‑References expandiert sind und der Entity‑Reference‑Knoten selbst nicht sichtbar ist, verwenden Sie die whatToShow‑Flags, um den Entity‑Reference‑Knoten zu verbergen, und setzen Sie expandEntityReferences beim Erstellen des Iterators auf true. Um eine Ansicht zu erzeugen, bei der Entity‑Reference‑Knoten vorhanden, aber nicht expandiert sind, verwenden Sie die whatToShow‑Flags, um den Entity‑Reference‑Knoten anzuzeigen, und setzen Sie expandEntityReferences auf false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Der aktuelle Referenzknoten. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Löst den NodeIterator von der Menge, über die er iteriert hat, gibt alle Rechenressourcen frei und versetzt den Iterator in den INVALID‑Zustand. Nachdem detach aufgerufen wurde, führen Aufrufe von nextNode oder previousNode zu der Ausnahme INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Gibt den nächsten Knoten in der Menge zurück und verschiebt die Position des Iterators in der Menge nach vorne. Nachdem ein NodeIterator erstellt wurde, liefert der erste Aufruf von nextNode() den ersten Knoten in der Menge. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Gibt den vorherigen Knoten in der Menge zurück und verschiebt die Position des NodeIterator rückwärts in der Menge. |

### Siehe auch

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
