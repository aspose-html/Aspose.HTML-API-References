---
title: SVGListBase1.Item
second_title: Справочник по Aspose.HTML для .NET API
description: SVGListBase свойство. Возвращает индексный элемент в списке.
type: docs
weight: 10
url: /ru/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Возвращает индексный элемент в списке.

```csharp
public T this[ulong index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс в списке. |

### Возвращаемое значение

Сохраненный объект в индексной позиции в списке.

### Стоимость имущества

Тип элемента, хранящегося в списке.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### Смотрите также

* class [SVGListBase&lt;T&gt;](../)
* пространство имен [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* сборка [Aspose.HTML](../../../)


