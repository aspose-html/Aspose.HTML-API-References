---
title: "HTMLTableRowElement.InsertCell"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLTableRowElement. Вставляет пустую ячейку TD в эту строку. Если index равен -1 или равен количеству ячеек, новая ячейка добавляется в конец"
type: docs

url: /ru/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Вставить пустую ячейку `TD` в эту строку. Если `index` равен -1 или количеству ячеек, новая ячейка добавляется в конец.

```java
public HTMLElement InsertCell(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки ячейки, начиная с 0. |

### Возвращаемое значение

Новосозданная ячейка.

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Возникает, если указанный `index` больше количества ячеек или если index является отрицательным числом, отличным от -1. @version DOM Level 2 |

### См. также

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
