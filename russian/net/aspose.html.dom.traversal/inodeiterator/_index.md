---
title: Interface INodeIterator
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Traversal.INodeIterator интерфейс. Итераторы используются для перехода через набор узлов например набор узлов в списке узлов поддерево документа управляемое конкретным узлом результаты запроса или любой другой набор узлов . Набор итерируемых узлов определяется реализацией NodeIterator. DOM уровня 2 определяет одиночную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются путем вызова DocumentTraversal .createNodeIterator.
type: docs
weight: 2500
url: /ru/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Итераторы используются для перехода через набор узлов, например, набор узлов в списке узлов, поддерево документа, управляемое конкретным узлом, результаты запроса или любой другой набор узлов . Набор итерируемых узлов определяется реализацией NodeIterator. DOM уровня 2 определяет одиночную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются путем вызова DocumentTraversal .createNodeIterator().

См. также[Модель объекта документа (DOM) Уровень 2 Спецификация обхода и диапазона](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @с уровня DOM 2

```csharp
public interface INodeIterator : ITraversal
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Значение этого флага определяет, видны ли итератору потомки ссылочных узлов entity . Если false, они и их потомки будут отклонены. Обратите внимание, что это отклонение имеет приоритет над whatToShow и фильтром. Также обратите внимание на то, что в настоящее время это единственная ситуация, когда NodeIterators может отклонить полное поддерево, а не пропустить отдельные узлы. скройте ссылку на сущность node и установите для параметра expandEntityReferences значение true при создании итератора . Чтобы создать представление документа с узлами ссылки на сущность , но без расширения сущности, используйте флаги whatToShow для отображения узла ссылки на сущность и установите для свойства expandEntityReferences значение false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Текущий опорный узел. |

## Методы

| Имя | Описание |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Отсоединяет NodeIterator от набора, по которому он выполнял итерацию , освобождая все вычислительные ресурсы и переводя итератор в состояние INVALID. После вызова detach вызовы nextNode или previousNode будут вызывать исключение INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Возвращает следующий узел в наборе и продвигает позицию итератора в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Возвращает предыдущий узел в наборе и перемещает позицию NodeIterator назад в наборе. |

### Смотрите также

* interface [ITraversal](../itraversal/)
* пространство имен [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* сборка [Aspose.HTML](../../)


