---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Das Paket com.aspose.html.dom.traversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um zwischen Elementen zu navigieren und einen Knoten sowie seine Kinder in Dokumentreihenfolge zu durchlaufen."
type: docs

url: /de/java/com.aspose.html.dom.traversal/
---
Das **com.aspose.html.dom.traversal**-Paket enthält Methoden, die Iteratoren und Tree‑Walker erzeugen, um zwischen Elementen zu navigieren und einen Knoten sowie dessen Kinder in Dokumentenreihenfolge zu durchlaufen.

## Schnittstellen

| Schnittstelle | Beschreibung |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um einen Knoten und seine Kinder in Dokumentreihenfolge zu durchlaufen (tiefenfirst, Preorder-Traversierung, die der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung des Dokuments vorkommen). In DOMs, die das Traversal‑Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document‑Interface implementieren. |
| [IElementTraversal](./ielementtraversal/) | Das ElementTraversal‑Interface ist eine Menge von schreibgeschützten Attributen, die es einem Autor ermöglichen, einfach zwischen Elementen in einem Dokument zu navigieren. In konformen Implementierungen von Element Traversal muss jedes Objekt, das Element implementiert, ebenfalls das ElementTraversal‑Interface implementieren. |
| [INodeFilter](./inodefilter/) | Filter sind Objekte, die wissen, wie man Knoten „herausfiltert“. Wenn einem NodeIterator oder TreeWalker ein NodeFilter übergeben wird, wendet er den Filter an, bevor er den nächsten Knoten zurückgibt. Wenn der Filter den Knoten akzeptiert, gibt die Traversal‑Logik ihn zurück; andernfalls sucht die Traversal‑Logik nach dem nächsten Knoten und tut so, als wäre der abgelehnte Knoten nicht vorhanden. |
| [INodeIterator](./inodeiterator/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotenmengen. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Dokumentreihenfolge‑Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Iteratoren werden verwendet, um durch eine Menge von Knoten zu gehen, z. B. die Menge von Knoten in einer NodeList, das Dokumentunterbaum, der von einem bestimmten Node gesteuert wird, die Ergebnisse einer Abfrage oder jede andere Knotenmengen. Die zu iterierende Knotenmengen wird durch die Implementierung des NodeIterator bestimmt. DOM Level 2 definiert eine einzelne NodeIterator‑Implementierung für die Dokumentreihenfolge‑Traversierung eines Dokumentunterbaums. Instanzen dieser Iteratoren werden durch Aufruf von DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | TreeWalker‑Objekte werden verwendet, um einen Dokumentbaum oder -unterbaum mithilfe der Ansicht des Dokuments zu navigieren, die durch ihre whatToShow‑Flags und Filter (falls vorhanden) definiert ist. Jede Funktion, die Navigation mit einem TreeWalker durchführt, unterstützt automatisch jede von einem TreeWalker definierte Ansicht. |
