---
title: Interface IDocumentTraversal
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Traversal.IDocumentTraversal интерфейс. DocumentTraversal содержит методы которые создают итераторы и обходчики дерева для обхода узла и его дочерних элементов в порядке документа сначала глубина  обход в предварительном порядке что эквивалентно порядку в котором начальные теги встречаются в текстовом представлении документ. В DOM  которые поддерживают функцию Traversal DocumentTraversal будет реализован теми же объектами которые реализуют интерфейс Document.
type: docs
weight: 2470
url: /ru/net/aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal содержит методы, которые создают итераторы и обходчики дерева для обхода узла и его дочерних элементов в порядке документа (сначала глубина , обход в предварительном порядке, что эквивалентно порядку, в котором начальные теги встречаются в текстовом представлении документ). В DOM , которые поддерживают функцию Traversal, DocumentTraversal будет реализован теми же объектами, которые реализуют интерфейс Document.

См. также[Модель объекта документа (DOM) Уровень 2 Спецификация обхода и диапазона](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @с уровня DOM 2

```csharp
public interface IDocumentTraversal
```

## Методы

| Имя | Описание |
| --- | --- |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Создать новый NodeIterator поверх поддерева с корнем в указанном узле . |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Создать новый NodeIterator поверх поддерева с корнем в указанном узле . |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Создать новый NodeIterator поверх поддерева с корнем в указанном узле . |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Создать новый TreeWalker поверх поддерева с корнем в указанном узле . |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Создать новый TreeWalker поверх поддерева с корнем в указанном узле . |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Создать новый TreeWalker поверх поддерева с корнем в указанном узле . |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* сборка [Aspose.HTML](../../)


