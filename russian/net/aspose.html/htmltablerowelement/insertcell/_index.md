---
title: HTMLTableRowElement.InsertCell
second_title: Справочник по Aspose.HTML для .NET API
description: HTMLTableRowElement метод. Вставить пустойТД ячейку в эту строку. Если индекс равно 1 или равно количеству ячеек добавляется новая ячейка .
type: docs
weight: 100
url: /ru/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Вставить пустой`ТД` ячейку в эту строку. Если `индекс` равно -1 или равно количеству ячеек, добавляется новая ячейка .

```csharp
public HTMLElement InsertCell(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Место для вставки ячейки, начиная с 0. |

### Возвращаемое значение

Только что созданная ячейка.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: возникает, если указано`индекс` больше количества ячеек или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### Смотрите также

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* пространство имен [Aspose.Html](../../htmltablerowelement/)
* сборка [Aspose.HTML](../../../)


