---
title: "Интерфейс IHTMLOptionsCollection"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.IHTMLOptionsCollection. HTMLOptionsCollection представляет собой список узлов, соответствующих элементу option в HTML. Отдельный узел можно получить либо по порядковому индексу, либо по имени или атрибуту id узла. Предполагается, что коллекции в HTML‑DOM являются «живыми», то есть они автоматически обновляются при изменении базового документа."
type: docs

url: /ru/java/com.aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

`HTMLOptionsCollection` — это список узлов, представляющих элемент option HTML. Отдельный узел можно получить либо по порядковому индексу, либо по атрибутам `name` или `id` узла. Предполагается, что коллекции в HTML DOM являются «живыми», то есть они автоматически обновляются при изменении базового документа.

См. также [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM Level 2

```java
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html/ihtmloptionscollection/item/) Возвращает элемент с указанным индексом в коллекции. Если индекс больше или равен количеству узлов в списке, возвращается null. (2 индексатора) |
| [getLength](../../com.aspose.html/ihtmloptionscollection/length/) Количество узлов в списке. |

## Методы

| Имя | Описание |
| --- | --- |
| [namedItem](../../com.aspose.html/ihtmloptionscollection/nameditem/)(String) | Метод возвращает элемент с указанным индексом в коллекции. http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### См. также

* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
