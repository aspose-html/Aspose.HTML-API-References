---
title: "Интерфейс IStyleSheetList"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.dom.css.IStyleSheetList. Интерфейс StyleSheetList представляет список объектов CSSStyleSheet. Экземпляр этого объекта может быть получен через Document.styleSheets."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

Интерфейс StyleSheetList представляет список объектов [`CSSStyleSheet`](../icssstylesheet/). Экземпляр этого объекта может быть получен через [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Поддерживаемые индексы свойств объекта — это числа в диапазоне от нуля до одного меньше количества CSS‑таблиц стилей, представленных в коллекции. Если таких CSS‑таблиц стилей нет, поддерживаемых индексов свойств также нет.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) Метод item(index) должен возвращать объект с указанным индексом [`CSS style sheet`](../icssstylesheet/) из коллекции. Если в коллекции нет объекта с таким индексом, метод должен вернуть null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) Атрибут length должен возвращать количество CSS‑таблиц стилей, представленных в коллекции. Диапазон допустимых индексов дочерних таблиц стилей — от 0 до length‑1 включительно. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### См. также

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
