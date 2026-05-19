---
title: "SVGListBase-1.GetItem"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGListBase. Возвращает указанный элемент из списка"
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

Возвращает указанный элемент из списка.

```java
public T GetItem(ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt64 | Индекс элемента из списка, который будет возвращён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Выбранный элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
