---
title: INodeFilter.AcceptNode
second_title: Справочник по Aspose.HTML для .NET API
description: INodeFilter метод. Проверить виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator обычно он не вызывается напрямую из пользовательского кода . Хотя вы могли бы сделать это если бы хотели использовать тот же фильтр для управления логикой вашего собственного приложения.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Проверить, виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно он не вызывается напрямую из пользовательского кода . (Хотя вы могли бы сделать это, если бы хотели использовать тот же фильтр для управления логикой вашего собственного приложения.)

```csharp
public short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Node | узел, чтобы проверить, проходит ли он фильтр или нет. |

### Возвращаемое значение

константа для определения того, принят ли узел, отклонен или пропущен, как определено выше.

### Смотрите также

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../)
* пространство имен [Aspose.Html.Dom.Traversal](../../inodefilter/)
* сборка [Aspose.HTML](../../../)


