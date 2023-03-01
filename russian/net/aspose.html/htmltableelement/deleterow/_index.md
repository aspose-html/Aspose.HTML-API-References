---
title: HTMLTableElement.DeleteRow
second_title: Справочник по Aspose.HTML для .NET API
description: HTMLTableElement метод. Удалить строку таблицы.
type: docs
weight: 190
url: /ru/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Удалить строку таблицы.

```csharp
public void DeleteRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Индекс удаляемой строки. Этот индекс начинается с 0 и относится к логическому порядку (не порядку документа) всех строк, содержащихся в таблице. Если индекс равен -1, последняя строка таблицы удаляется. |

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: повышается, если указанный индекс больше или равен количеству строк или если индекс представляет собой отрицательное число , отличное от -1. @version DOM Level 2 |

### Смотрите также

* class [HTMLTableElement](../)
* пространство имен [Aspose.Html](../../htmltableelement/)
* сборка [Aspose.HTML](../../../)


