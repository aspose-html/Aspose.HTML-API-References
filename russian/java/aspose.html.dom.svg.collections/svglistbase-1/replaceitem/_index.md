---
title: "SVGListBase-1.ReplaceItem"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGListBase. Заменяет существующий элемент в списке новым элементом"
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

Заменяет существующий элемент в списке новым элементом.

```java
public T ReplaceItem(T newItem, ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newItem | T | Элемент, который будет вставлен в список. |
| index | UInt64 | Индекс элемента, который будет заменён. Первый элемент имеет номер 0. |

### Возвращаемое значение

Вставляемый элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/). Возникает, если номер индекса больше или равен numberOfItems. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
