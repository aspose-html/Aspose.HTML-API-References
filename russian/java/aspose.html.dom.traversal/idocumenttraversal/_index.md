---
title: "Интерфейс IDocumentTraversal"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.traversal.IDocumentTraversal interface. DocumentTraversal содержит методы, которые создают итераторы и tree-walkers для обхода узла и его дочерних элементов в порядке документа, глубина‑первый предзаказ (pre-order), что эквивалентно порядку, в котором стартовые теги встречаются в текстовом представлении документа. В DOM, поддерживающих функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document."
type: docs

url: /ru/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal содержит методы, которые создают итераторы и обходчики дерева для обхода узла и его дочерних элементов в порядке документа (обход в глубину, предварительный порядок, что эквивалентно порядку, в котором начальные теги появляются в текстовом представлении документа). В DOM, поддерживающих функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document.

Смотрите также [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Методы

| Имя | Описание |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Создайте новый NodeIterator для поддерева, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Создайте новый TreeWalker для поддерева, корнем которого является указанный узел. |

### См. также

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
