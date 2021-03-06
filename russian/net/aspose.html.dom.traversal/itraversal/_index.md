---
title: ITraversal
second_title: Справочник по Aspose.HTML для .NET API
description: Итераторы используются для перехода через набор узлов например набор узлов в NodeList поддерево документа управляемое конкретный узел результаты запроса или любой другой набор узлов. Набор итерируемых узлов определяется реализацией NodeIterator. Уровень DOM 2 определяет реализацию одиночного NodeIterator для порядка документов обхода поддерева документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator.
type: docs
weight: 2620
url: /ru/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Итераторы используются для перехода через набор узлов, например, набор узлов в NodeList, поддерево документа, управляемое конкретный узел, результаты запроса или любой другой набор узлов. Набор итерируемых узлов определяется реализацией NodeIterator. Уровень DOM 2 определяет реализацию одиночного NodeIterator для порядка документов обхода поддерева документа. Экземпляры этих итераторов создаются вызовом DocumentTraversal .createNodeIterator().

См. также[Объектная модель документа (DOM) Уровень 2 Обход и спецификация диапазона](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113) . @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter) { get; } | NodeFilter используется для просмотра узлов. |
| [Root](../../aspose.html.dom.traversal/itraversal/root) { get; } | Корневой узел NodeIterator, как указано при его создании . |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow) { get; } | Этот атрибут определяет, какие типы узлов представлены через итератор . Доступный набор констант определяется в интерфейсе NodeFilter. Узлы, не принятые whatToShow, будут пропущены, но их дочерние элементы все равно могут быть рассмотрены . Обратите внимание, что этот пропуск имеет приоритет над фильтром , если он есть. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal)
* сборка [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
