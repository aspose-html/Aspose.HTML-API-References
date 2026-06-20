---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Das Paket com.aspose.html.dom.traversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um zwischen Elementen zu navigieren und einen Knoten sowie dessen Kinder in Dokumentreihenfolge zu durchlaufen."
type: docs

url: /de/java/com.aspose.html.dom.traversal/
---
Das **com.aspose.html.dom.traversal**-Paket enthält Methoden, die Iteratoren und Tree‑Walker erzeugen, um zwischen Elementen zu navigieren und einen Knoten sowie dessen Kinder in Dokumentenreihenfolge zu durchlaufen.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um einen Knoten und dessen Kinder in Dokumentreihenfolge zu durchlaufen (tiefenfirst, Preorder-Durchlauf, der der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung des Dokuments auftreten). In DOMs, die das Traversal-Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document-Interface implementieren. |
| [IElementTraversal](./ielementtraversal/) | Das ElementTraversal-Interface ist ein Satz von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal müssen alle Objekte, die Element implementieren, ebenfalls das ElementTraversal-Interface implementieren. |
| [INodeFilter](./inodefilter/) | Filter sind Objekte, die wissen, wie man Knoten "herausfiltert". Wenn einem NodeIterator oder TreeWalker ein NodeFilter übergeben wird, wendet er den Filter an, bevor er den nächsten Knoten zurückgibt. Wenn der Filter den Knoten akzeptiert, gibt die Traversal-Logik ihn zurück; andernfalls sucht die Traversal-Logik nach dem nächsten Knoten und tut so, als wäre der abgelehnte Knoten nicht vorhanden. |
| [INodeIterator](./inodeiterator/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge‑Durchquerung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator() erstellt. |
| [ITraversal](./itraversal/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, den Dokument-Teilbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotengruppe. Die zu iterierende Knotengruppe wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 spezifiziert eine einzelne NodeIterator-Implementierung für die Dokumentreihenfolge‑Durchquerung eines Dokument-Teilbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator() erstellt. |
| [ITreeWalker](./itreewalker/) | TreeWalker-Objekte werden verwendet, um einen Dokumentbaum oder Teilbaum zu navigieren, wobei die Ansicht des Dokuments verwendet wird, die durch ihre whatToShow-Flags und ggf. Filter definiert ist. Jede Funktion, die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede von einem TreeWalker definierte Ansicht. |
