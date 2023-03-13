---
title: HTMLTableSectionElement.InsertRow
second_title: Справочник по Aspose.HTML для .NET API
description: HTMLTableSectionElement метод. Вставьте строку в этот раздел. Новая строка вставляется сразу за перед текущейиндекс й ряд в этом разделе. Если индекс равно 1 или равно количеству строк в этом разделе  добавляется новая строка.
type: docs
weight: 70
url: /ru/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Вставьте строку в этот раздел. Новая строка вставляется сразу за перед текущей`индекс` й ряд в этом разделе. Если `индекс` равно -1 или равно количеству строк в этом разделе , добавляется новая строка.

```csharp
public HTMLElement InsertRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Номер строки, куда вставить новую строку. Этот индекс начинается с 0 и относится только к строкам, содержащимся внутри этого раздела, а не ко всем строкам в таблице. |

### Возвращаемое значение

Недавно созданная строка.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: повышается, если указанный индекс больше количества строк, если индекс представляет собой отрицательное число, отличное от -1. @version DOM Level 2 |

### Смотрите также

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* пространство имен [Aspose.Html](../../htmltablesectionelement/)
* сборка [Aspose.HTML](../../../)


