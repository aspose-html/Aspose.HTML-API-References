---
title: "IDocumentTraversal Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.dom.traversal.IDocumentTraversal Schnittstelle. DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erzeugen, um einen Knoten und seine Kinder in Dokumentreihenfolge, tiefenfirst, Vororder-Traversal zu durchlaufen, was der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung des Dokuments vorkommen. In DOMs, die das Traversal-Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document-Interface implementieren."
type: docs

url: /de/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal enthält Methoden, die Iteratoren und Tree-Walker erstellen, um einen Knoten und seine Kinder in Dokumentreihenfolge zu durchlaufen (tiefenfirst, Preorder-Traversierung, die der Reihenfolge entspricht, in der die Start-Tags in der Textdarstellung des Dokuments vorkommen). In DOMs, die das Traversal‑Feature unterstützen, wird DocumentTraversal von denselben Objekten implementiert, die das Document‑Interface implementieren.

Siehe auch die [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Erstellt einen neuen NodeIterator über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Erstellt einen neuen TreeWalker über dem Teilbaum, der am angegebenen Knoten verwurzelt ist. |

### Siehe auch

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
