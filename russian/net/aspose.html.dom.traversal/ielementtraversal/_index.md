---
title: Interface IElementTraversal
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Traversal.IElementTraversal интерфейс. Интерфейс ElementTraversal представляет собой набор атрибутов только для чтения которые позволяют автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты реализующие Element должны также реализовывать интерфейс ElementTraversal.
type: docs
weight: 2480
url: /ru/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

Интерфейс ElementTraversal представляет собой набор атрибутов только для чтения, которые позволяют автору легко перемещаться между элементами в документе. В соответствующих реализациях Element Traversal все объекты, реализующие Element, должны также реализовывать интерфейс ElementTraversal.

```csharp
public interface IElementTraversal
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Возвращает текущее количество узлов элемента, которые являются дочерними элементами этого элемента. 0, если у этого элемента нет дочерних узлов с nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Возвращает первый узел дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Возвращает последний узел дочернего элемента этого элемента. null, если у этого элемента нет дочерних элементов. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Возвращает следующий узел одноуровневого элемента этого элемента. null, если у этого элемента нет узлов-сестер, следующих за этим в дереве документа. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Возвращает предыдущий узел родственного элемента этого элемента. null, если этот элемент не имеет родственных узлов, предшествующих ему в дереве документа. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* сборка [Aspose.HTML](../../)


