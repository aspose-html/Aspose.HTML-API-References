---
title: HTMLTableElement.InsertRow
second_title: Справочник по Aspose.HTML для .NET API
description: HTMLTableElement метод. Вставить в таблицу новую пустую строку. Новая строка вставляется непосредственно перед и в том же разделе что и текущая индекс ая строка в таблице. Еслииндекс равно 1 или количеству строк добавляется новая строка. Кроме того  когда таблица пуста строка вставляется вTBODY  который создается и вставляется в таблицу. Строка таблицы не может быть пустой в соответствии с HTML 4.01 .
type: docs
weight: 220
url: /ru/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

Вставить в таблицу новую пустую строку. Новая строка вставляется непосредственно перед и в том же разделе, что и текущая `индекс` ая строка в таблице. Если`индекс` равно -1 или количеству строк, добавляется новая строка. Кроме того, , когда таблица пуста, строка вставляется в`TBODY` , который создается и вставляется в таблицу. Строка таблицы не может быть пустой в соответствии с [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

```csharp
public Node InsertRow(int index)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Номер строки, куда вставить новую строку. Этот индекс начинается с 0 и относится к логическому порядку (не порядку документа ) всех строк, содержащихся в таблице. |

### Возвращаемое значение

Недавно созданная строка.

### Исключения

| исключение | условие |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: повышается, если указанный индекс больше, чем количество строк, или если индекс является отрицательным числом, отличным от -1. @version DOM Level 2 |

### Смотрите также

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* пространство имен [Aspose.Html](../../htmltableelement/)
* сборка [Aspose.HTML](../../../)


