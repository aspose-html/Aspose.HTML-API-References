---
title: ITreeWalker
second_title: Aspose.HTML für .NET-API-Referenz
description: TreeWalkerObjekte werden verwendet um durch einen Dokumentbaum oder einen Teilbaum zu navigieren wobei die Ansicht des Dokuments verwendet wird die durch ihre whatToShowFlags und Filter falls vorhanden definiert ist. Jede Funktion die die Navigation mit einem TreeWalker durchführt wird automatisch jede von einem TreeWalker definierte Ansicht unterstützen.
type: docs
weight: 2530
url: /de/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker-Objekte werden verwendet, um durch einen Dokumentbaum oder einen -Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und Filter (falls vorhanden) definiert ist. Jede Funktion, die die Navigation mit einem TreeWalker durchführt, wird automatisch jede von einem TreeWalker definierte Ansicht unterstützen.

Das Auslassen von Knoten aus der logischen Ansicht eines Teilbaums kann zu einer -Struktur führen, die sich wesentlich von demselben Teilbaum in dem vollständigen, ungefilterten Dokument unterscheidet. Knoten, die in der -TreeWalker-Ansicht Geschwister sind, können in der ursprünglichen Ansicht Kinder verschiedener, weit -getrennter Knoten sein. Stellen Sie sich beispielsweise einen NodeFilter vor, der alle Knoten außer Textknoten und den Stammknoten eines Dokuments überspringt. In der daraus resultierenden logischen Ansicht sind alle -Textknoten Geschwister und erscheinen als direkte Kinder des Wurzelknotens, egal wie tief die Struktur des Originaldokuments verschachtelt ist.

Siehe auch die[Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @seit DOM Level 2

```csharp
public interface ITreeWalker : ITraversal
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode) { get; set; } | Der Knoten, an dem sich der TreeWalker derzeit befindet. Änderungen am DOM-Baum können dazu führen, dass der aktuelle Knoten nicht mehr vom zugehörigen Filter des TreeWalkers akzeptiert wird. currentNode kann auch explizit auf einen beliebigen Knoten gesetzt werden, unabhängig davon, ob dies der Fall ist oder nicht innerhalb des Unterbaums, der durch den -Stammknoten angegeben ist, oder würde von den Flags filter and whatToShow akzeptiert werden. Eine weitere Traversierung erfolgt relativ zu aktuellem Knoten, selbst wenn er nicht Teil der aktuellen Ansicht ist, durch Anwenden der Filter in der angeforderten Richtung; wenn kein Traversal möglich ist, wird currentNode nicht geändert. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild)() | Verschiebt den TreeWalker zum ersten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keine sichtbaren untergeordneten Elemente hat, wird null zurückgegeben und der aktuelle -Knoten beibehalten. |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild)() | Verschiebt den TreeWalker zum letzten sichtbaren Kind des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keine sichtbaren untergeordneten Elemente hat, wird null zurückgegeben und der aktuelle -Knoten beibehalten. |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode)() | Verschiebt den TreeWalker zum nächsten sichtbaren Knoten in der Reihenfolge document relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keinen nächsten Knoten hat oder wenn die Suche nach nextNode versucht , vom Wurzelknoten des TreeWalkers nach oben zu gehen, wird null zurückgegeben und der aktuelle Knoten beibehalten. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling)() | Verschiebt den TreeWalker zum nächsten gleichgeordneten Knoten des aktuellen -Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten kein sichtbares nächstes Geschwister hat, wird null zurückgegeben und der aktuelle Knoten beibehalten. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode)() | Verschiebt sich zum nächstgelegenen sichtbaren Vorgängerknoten des aktuellen -Knotens und gibt diesen zurück. Wenn die Suche nach parentNode versucht, vom Stammknoten des TreeWalkers schrittweise nach oben zu gehen, oder keinen sichtbaren Vorgängerknoten findet, behält diese Methode die aktuelle Position bei und gibt null zurück. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode)() | Bewegt den TreeWalker zum vorherigen sichtbaren Knoten in Dokumentenreihenfolge relativ zum aktuellen Knoten und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keinen vorherigen Knoten hat oder wenn die Suche nach previousNode versucht, vom Stammknoten des TreeWalkers nach oben zu gehen, gibt null zurück und behält den aktuellen Knoten bei. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling)() | Verschiebt den TreeWalker zum vorherigen Geschwister des aktuellen Knotens und gibt den neuen Knoten zurück. Wenn der aktuelle Knoten keine sichtbaren vorherigen Geschwister hat, wird null zurückgegeben und der aktuelle Knoten beibehalten. |

### Siehe auch

* interface [ITraversal](../itraversal)
* namensraum [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal)
* Montage [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
