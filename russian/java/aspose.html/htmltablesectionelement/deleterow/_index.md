---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLTableSectionElement. Удалить строку из этого раздела"
type: docs

url: /ru/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Удалить строку из этого раздела.

```java
public void DeleteRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс строки, которую нужно удалить, или -1 для удаления последней строки. Этот индекс начинается с 0 и относится только к строкам, содержащимся в этом разделе, а не ко всем строкам в таблице. |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Вызывается, если указанный индекс больше или равен количеству строк или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### См. также

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
