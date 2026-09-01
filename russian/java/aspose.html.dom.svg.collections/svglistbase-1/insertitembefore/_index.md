---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод SVGListBase. Вставляет новый элемент в список в указанной позиции. Первый элемент имеет номер 0"
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

Вставляет новый элемент в список в указанной позиции. Первый элемент имеет номер 0.

```java
public T InsertItemBefore(T newItem, ulong index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newItem | T | Элемент, который будет вставлен в список. |
| index | UInt64 | Индекс элемента, перед которым будет вставлен новый элемент. Первый элемент имеет номер 0. Если индекс равен 0, новый элемент вставляется в начало списка. Если индекс больше или равен numberOfItems, новый элемент добавляется в конец списка. |

### Возвращаемое значение

Вставляемый элемент.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Код [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/). Возникает, когда список нельзя изменить. |

### См. также

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
