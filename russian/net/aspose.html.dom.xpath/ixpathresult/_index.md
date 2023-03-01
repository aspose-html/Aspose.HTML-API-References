---
title: Interface IXPathResult
second_title: Справочник по Aspose.HTML для .NET API
description: Aspose.Html.Dom.XPath.IXPathResult интерфейс. XPathResult Интерфейс представляет собой результат оценки выражения XPath 1.0 в контексте конкретного узла. Поскольку вычисление выражения XPath может привести к различным типам результатов этот объект позволяет обнаруживать и управлять типом и значением результата.
type: docs
weight: 2600
url: /ru/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` Интерфейс представляет собой результат оценки выражения XPath 1.0 в контексте конкретного узла. Поскольку вычисление выражения XPath может привести к различным типам результатов, этот объект позволяет обнаруживать и управлять типом и значением результата.

```csharp
public interface IXPathResult
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | Значение этого логического результата. |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | Означает, что итератор стал недействительным. Верно, если`тип результата` это`UnorderedNodeIterator` тип или`OrderedNodeIterator` type и документ был изменен с момента возврата этого результата. |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | Значение этого числового результата. |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | Код, представляющий тип этого результата, как определено http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult [`XPathResultType`](../xpathresulttype/) перечисление. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | Значение этого единственного результата узла, которое может быть`нулевой` . |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | Количество узлов в снимке результата. Допустимые значения индексов snapshotItem :`0` к`snapshotLength-1` включительно. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | Значение этой строки result. |

## Методы

| Имя | Описание |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Итерирует и возвращает следующий узел из набора узлов или`нулевой` если больше нет узлов. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Возвращает`индекс` элемент в коллекции моментальных снимков. Если`индекс`больше или равно количеству узлов в списке, этот метод возвращает`нулевой` . В отличие от результата итератора , снимок не становится недействительным, но может не соответствовать текущему документу , если он видоизменен. |

### Смотрите также

* пространство имен [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* сборка [Aspose.HTML](../../)


