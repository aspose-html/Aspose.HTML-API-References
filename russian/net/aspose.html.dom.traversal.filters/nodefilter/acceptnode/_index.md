---
title: AcceptNode
second_title: Справочник по Aspose.HTML для .NET API
description: Проверить виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator обычно он не вызывается непосредственно из пользовательского кода. Хотя вы могли бы сделать это если бы хотели использовать тот же фильтр для управления собственной логикой приложения.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

Проверить, виден ли указанный узел в логическом представлении TreeWalker или NodeIterator. Эта функция будет вызываться реализацией TreeWalker и NodeIterator; обычно он не вызывается непосредственно из пользовательского кода. (Хотя вы могли бы сделать это, если бы хотели использовать тот же фильтр для управления собственной логикой приложения.)

```csharp
public abstract short AcceptNode(Node n)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| n | Node | узел, чтобы проверить, проходит ли он фильтр или нет. |

### Возвращаемое значение

константа для определения того, принят ли узел, отклонен или пропущен, как определено выше.

### Смотрите также

* class [Node](../../../aspose.html.dom/node)
* class [NodeFilter](../../nodefilter)
* пространство имен [Aspose.Html.Dom.Traversal.Filters](../../nodefilter)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
