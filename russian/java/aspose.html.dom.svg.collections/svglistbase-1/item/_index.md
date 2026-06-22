---
title: "SVGListBase-1.Item"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство SVGListBase. Возвращает элемент с индексом в списке"
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

Возвращает элемент с индексом в списке.

```java
public T this[ulong index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Индекс в списке. |

### Возвращаемое значение

Сохранённый объект на позиции с индексом в списке.

### Property Value

Тип элемента, хранящегося в списке.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
