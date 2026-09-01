---
title: "IDocumentTraversal Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.IDocumentTraversal‑Schnittstelle. DocumentTraversal enthält Methoden, die Iteratoren und Tree‑Walker erzeugen, um einen Knoten und seine Kinder in Dokumentreihenfolge, tiefen‑erst‑Pre‑Order‑Durchlauf, zu traversieren, was der Reihenfolge entspricht, in der die Start‑Tags in der Textdarstellung des Dokuments vorkommen. In DOMs, die das Traversal‑Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document‑Interface implementieren."
type: docs

url: /de/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um einen Knoten und dessen Kinder in Dokumentreihenfolge zu durchlaufen (tiefenfirst, Preorder-Durchlauf, der der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung des Dokuments auftreten). In DOMs, die das Traversal-Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document-Interface implementieren.

Siehe auch das [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Erstelle einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Erstelle einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten wurzelt. |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
