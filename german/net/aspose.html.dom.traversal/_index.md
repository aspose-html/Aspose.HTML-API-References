---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML für .NET-API-Referenz
description: Die Aspose.Html.Dom.TraversalNamespace enthält Methoden die Iteratoren und Treewalker erstellen um zwischen Elementen zu navigieren und einen Knoten und seine Kinder in der Reihenfolge der Dokumente durchlaufen.
type: docs
weight: 170
url: /de/net/aspose.html.dom.traversal/
---
Die **Aspose.Html.Dom.Traversal**Namespace enthält Methoden, die Iteratoren und Treewalker erstellen, um zwischen Elementen zu navigieren, und einen Knoten und seine Kinder in der Reihenfolge der Dokumente durchlaufen.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um einen Knoten und seine Kinder in der Reihenfolge des Dokuments zu durchlaufen (Tiefe zuerst, Traversierung vorbestellen, was der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung von vorkommen das Dokument). In DOMs , die die Traversal-Funktion unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die die Document-Schnittstelle implementieren. |
| [IElementTraversal](./ielementtraversal/) | Die ElementTraversal-Schnittstelle ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, auch die ElementTraversal-Schnittstelle implementieren. |
| [INodeFilter](./inodefilter/) | Filter sind Objekte, die Knoten "herausfiltern" können. Wenn einem NodeIterator oder TreeWalker ein NodeFilter gegeben wird, wendet er den Filter an, bevor er den nächsten -Knoten zurückgibt. Wenn der Filter sagt, dass der Knoten akzeptiert werden soll, gibt die Traversierungslogik it zurück; Andernfalls sucht Traversal nach dem nächsten Knoten und gibt vor, dass der zurückgewiesene -Knoten nicht vorhanden war. |
| [INodeIterator](./inodeiterator/) | Iteratoren werden verwendet, um schrittweise durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Knoten gesteuert wird, die Ergebnisse einer Abfrage oder irgendeine andere Menge von Knoten. Die Menge der zu iterierenden Knoten wird durch die -Implementierung des NodeIterators bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erstellt durch Aufrufen von DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iteratoren werden verwendet, um schrittweise durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Knoten gesteuert wird, die Ergebnisse einer Abfrage oder irgendeine andere Menge von Knoten. Die Menge der zu iterierenden Knoten wird durch die -Implementierung des NodeIterators bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden erstellt durch Aufrufen von DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker-Objekte werden verwendet, um durch einen Dokumentbaum oder einen -Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und Filter (falls vorhanden) definiert ist. Jede Funktion, die die Navigation mit einem TreeWalker durchführt, wird automatisch jede von einem TreeWalker definierte Ansicht unterstützen. |


