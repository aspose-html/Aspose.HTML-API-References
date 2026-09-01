---
title: "HTMLTableRowElement.DeleteCell"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод HTMLTableRowElement. Удалить ячейку из текущей строки"
type: docs

url: /ru/java/com.aspose.html/htmltablerowelement/deletecell/
---
## HTMLTableRowElement.DeleteCell method

Удалить ячейку из текущей строки.

```java
public void DeleteCell(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс ячейки, которую нужно удалить, начиная с 0. Если индекс равен -1, будет удалена последняя ячейка в строке. |

### Исключения

| исключение | условие |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Возникает, если указанный `index` больше или равен количеству ячеек или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### См. также

* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
