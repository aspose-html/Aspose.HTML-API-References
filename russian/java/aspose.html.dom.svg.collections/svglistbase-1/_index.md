---
title: "Класс SVGListBaseT"
second_title: "Справочник API Aspose.HTML для Java"
description: "Класс com.aspose.html.dom.svg.collections.SVGListBase1T. Этот интерфейс определяет базовый список всех SVG‑списков."
type: docs

url: /ru/java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

Этот интерфейс определяет базовый список всех SVG‑списков.

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| Параметр | Описание |
| --- | --- |
| T | Тип элемента, хранящегося в списке. |

## Свойства

| Имя | Описание |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) Количество элементов в списке. |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) Количество элементов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | Вставляет новый элемент в конец списка. |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | Очищает все текущие элементы из списка, в результате получая пустой список. |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Освобождает неуправляемые и — при необходимости — управляемые ресурсы. |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | Получает перечислитель. |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | Возвращает указанный элемент из списка. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Этот метод используется для получения объекта ECMAScript. |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | Очищает все текущие элементы из списка и переинициализирует список, чтобы содержать единственный элемент, указанный параметром. |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | Вставляет новый элемент в список в указанной позиции. Первый элемент имеет номер 0. |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | Удаляет существующий элемент из списка. |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | Заменяет существующий элемент в списке новым элементом. |

### См. также

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
