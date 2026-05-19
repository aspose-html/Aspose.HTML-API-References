---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLTableSectionElement. Вставить строку в этот раздел. Новая строка вставляется непосредственно перед текущей строкой с индексом index в этом разделе. Если index равен -1 или равен количеству строк в этом разделе, новая строка добавляется в конец."
type: docs

url: /ru/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Вставить строку в этот раздел. Новая строка вставляется непосредственно перед текущей `index`‑й строкой в этом разделе. Если `index` равно -1 или равно количеству строк в этом разделе, новая строка добавляется в конец.

```java
public HTMLElement InsertRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Номер строки, в которую нужно вставить новую строку. Этот индекс начинается с 0 и относится только к строкам, находящимся внутри этого раздела, а не ко всем строкам в таблице. |

### Возвращаемое значение

Новосозданная строка.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Возникает, если указанный индекс больше количества строк или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### См. также

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
