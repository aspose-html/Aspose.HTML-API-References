---
title: InsertRow
second_title: Справочник по Aspose.HTML для .NET API
description: Вставьте строку в этот раздел. Новая строка вставляется сразу перед текущей index й строкой в этом разделе. Если  index равно -1 или равно количеству строк в этом разделе  новая строка добавлено.
type: docs
weight: 70
url: /ru/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Вставьте строку в этот раздел. Новая строка вставляется сразу перед текущей` index` й строкой в этом разделе. Если ` index` равно -1 или равно количеству строк в этом разделе , новая строка добавлено.

```csharp
public HTMLElement InsertRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Номер строки, куда вставить новую строку. Этот индекс начинается с 0 и относится только к строкам, содержащимся внутри этого раздела, а не ко всем строкам в таблице. |

### Возвращаемое значение

Вновь созданная строка.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | INDEX_SIZE_ERR:Возникает, если указанный индекс больше количество строк, если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### Смотрите также

* class [HTMLElement](../../htmlelement)
* class [HTMLTableSectionElement](../../htmltablesectionelement)
* пространство имен [Aspose.Html](../../htmltablesectionelement)
* сборка [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
