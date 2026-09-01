---
title: "HTMLTableElement.DeleteRow"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLTableElement. Удалить строку таблицы."
type: docs

url: /ru/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Удаляет строку таблицы.

```java
public void DeleteRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс строки, которую нужно удалить. Этот индекс начинается с 0 и относится к логическому порядку (а не к порядку в документе) всех строк, содержащихся в таблице. Если индекс равен -1, удаляется последняя строка таблицы. |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Вызывается, если указанный индекс больше или равен количеству строк или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### См. также

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
