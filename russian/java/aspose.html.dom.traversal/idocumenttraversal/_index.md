---
title: "IDocumentTraversal интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.traversal.IDocumentTraversal интерфейс. DocumentTraversal содержит методы, которые создают итераторы и tree-walkers для обхода узла и его дочерних элементов в порядке документа, глубина‑первый предзаказ (pre-order) обход, который эквивалентен порядку, в котором стартовые теги появляются в текстовом представлении документа. В DOM, поддерживающих функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal содержит методы, создающие итераторы и обходчики дерева для обхода узла и его дочерних элементов в порядке документа (обход в глубину, предварительный порядок, который эквивалентен порядку, в котором стартовые теги появляются в текстовом представлении документа). В DOM, поддерживающих функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document.

Смотрите также [Спецификация Traversal and Range уровня 2 модели объектного документа (DOM)](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Методы

| Имя | Описание |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Создайте новый NodeIterator над поддеревом, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Создайте новый TreeWalker над поддеревом, корнем которого является указанный узел. |

### См. также

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
