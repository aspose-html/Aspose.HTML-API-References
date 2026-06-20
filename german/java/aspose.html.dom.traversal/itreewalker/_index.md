---
title: "ITreeWalker‑Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.ITreeWalker‑Schnittstelle. TreeWalker‑Objekte werden verwendet, um einen Dokumentbaum oder Teilbaum anhand der Ansicht des Dokuments zu navigieren, die durch ihre whatToShow‑Flags und ggf. einen Filter definiert ist. Jede Funktion, die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede durch einen TreeWalker definierte Ansicht."
type: docs

url: /de/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker-Objekte werden verwendet, um einen Dokumentbaum oder Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und ggf. Filter definiert ist. Jede Funktion, die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede von einem TreeWalker definierte Ansicht.

Das Auslassen von Knoten aus der logischen Ansicht eines Teilbaums kann zu einer Struktur führen, die sich wesentlich von demselben Teilbaum im vollständigen, ungefilterten Dokument unterscheidet. Knoten, die in der TreeWalker‑Ansicht Geschwister sind, können im ursprünglichen Dokument Kinder verschiedener, weit auseinander liegender Knoten sein. Beispielsweise ein NodeFilter, der alle Knoten außer Textknoten und dem Wurzelknoten eines Dokuments überspringt. In der daraus resultierenden logischen Ansicht werden alle Textknoten Geschwister sein und als direkte Kinder des Wurzelknotens erscheinen, unabhängig davon, wie tief die Struktur des ursprünglichen Dokuments verschachtelt ist.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Bewegt den TreeWalker zum ersten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Hat der aktuelle Knoten keine sichtbaren Kinder, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Bewegt den TreeWalker zum letzten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Hat der aktuelle Knoten keine sichtbaren Kinder, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Bewegt den TreeWalker zum nächsten sichtbaren Knoten in Dokumentreihenfolge relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Hat der aktuelle Knoten keinen nächsten Knoten oder versucht die Suche nach nextNode, vom Wurzelknoten des TreeWalkers aus nach oben zu gehen, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Bewegt den TreeWalker zum nächsten sichtbaren Geschwisterknoten des aktuellen Knotens und gibt den neuen Knoten zurück. Hat der aktuelle Knoten kein sichtbares nächstes Geschwister, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Bewegt sich zum nächsten sichtbaren Vorfahrenknoten des aktuellen Knotens und gibt ihn zurück. Versucht die Suche nach parentNode, vom Wurzelknoten des TreeWalkers aus nach oben zu gehen, oder findet keinen sichtbaren Vorfahren, behält diese Methode die aktuelle Position bei und gibt null zurück. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Verschiebt den TreeWalker zum vorherigen sichtbaren Knoten in Dokumentreihenfolge relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keinen vorherigen Knoten hat oder wenn die Suche nach previousNode versucht, vom Wurzelknoten des TreeWalkers nach oben zu gehen, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Verschiebt den TreeWalker zum vorherigen Geschwisterknoten des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten kein sichtbares vorheriges Geschwister hat, wird null zurückgegeben und der aktuelle Knoten bleibt erhalten. |

### Siehe auch

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
