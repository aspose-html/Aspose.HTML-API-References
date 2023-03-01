---
title: Interface ITraversal
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.Traversal.ITraversal интерфейс. Итераторы используются для перехода через набор узлов например набор узлов в списке узлов поддерево документа управляемое конкретным узлом результаты запроса или любой другой набор узлов . Набор итерируемых узлов определяется реализацией NodeIterator. DOM уровня 2 определяет одиночную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются путем вызова DocumentTraversal .createNodeIterator.
type: docs
weight: 2510
url: /ru/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Итераторы используются для перехода через набор узлов, например, набор узлов в списке узлов, поддерево документа, управляемое конкретным узлом, результаты запроса или любой другой набор узлов . Набор итерируемых узлов определяется реализацией NodeIterator. DOM уровня 2 определяет одиночную реализацию NodeIterator для обхода поддерева документа в порядке документа. Экземпляры этих итераторов создаются путем вызова DocumentTraversal .createNodeIterator().

См. также[Модель объекта документа (DOM) Уровень 2 Спецификация обхода и диапазона](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @с уровня DOM 2

```csharp
public interface ITraversal : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | NodeFilter, используемый для просмотра узлов. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | Корневой узел NodeIterator, указанный при создании it . |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Этот атрибут определяет, какие типы узлов представлены через итератор . Доступный набор констант определяется в интерфейсе NodeFilter. Узлы, не принятые whatToShow, будут пропущены, но их дочерние узлы все еще могут рассматриваться. Обратите внимание, что этот пропуск имеет приоритет над фильтром, , если он есть. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* сборка [Aspose.HTML](../../)


