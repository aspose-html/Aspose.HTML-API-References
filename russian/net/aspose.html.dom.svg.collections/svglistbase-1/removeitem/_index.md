---
title: SVGListBase1.RemoveItem
second_title: Справочник по Aspose.HTML для .NET API
description: SVGListBase метод. Удаляет существующий элемент из списка.
type: docs
weight: 100
url: /ru/net/aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Удаляет существующий элемент из списка.

```csharp
public T RemoveItem(ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt64 | Индекс элемента, который необходимо удалить. Первый элемент имеет номер 0. |

### Возвращаемое значение

Удаленный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [DOMException](../../../aspose.html.dom/domexception/) | Код[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### Смотрите также

* class [SVGListBase&lt;T&gt;](../)
* пространство имен [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* сборка [Aspose.HTML](../../../)


