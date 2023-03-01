---
title: INodeIterator.NextNode
second_title: Справочник по Aspose.HTML для .NET API
description: INodeIterator метод. Возвращает следующий узел в наборе и продвигает позицию итератора в наборе. После создания NodeIterator первый вызов nextNode возвращает первый узел в наборе.
type: docs
weight: 40
url: /ru/net/aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Возвращает следующий узел в наборе и продвигает позицию итератора в наборе. После создания NodeIterator первый вызов nextNode() возвращает первый узел в наборе.

```csharp
public Node NextNode()
```

### Возвращаемое значение

Следующий узел в итерируемом наборе или null, если в этом наборе больше нет членов.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: возникает, если этот метод вызывается после вызова метода detach . |

### Смотрите также

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeIterator](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* сборка [Aspose.HTML](../../../)


