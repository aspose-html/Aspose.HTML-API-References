---
title: "SVGListBase-1.RemoveItem"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGListBase. Удаляет существующий элемент из списка"
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

Удаляет существующий элемент из списка.

```java
public T RemoveItem(ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | UInt64 | Индекс элемента, который будет удалён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Удалённый элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
