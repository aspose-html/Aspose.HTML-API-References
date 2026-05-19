---
title: "IStyleSheetList.Item"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство IStyleSheetList. Метод itemindex должен возвращать CSS‑таблицу стилей с указанным индексом в коллекции. Если объект с таким индексом в коллекции отсутствует, метод должен вернуть null."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheetlist/item/
---
## IStyleSheetList indexer

Метод item(index) должен возвращать index‑ую [`CSS style sheet`](../../icssstylesheet/) в коллекции. Если объект с таким индексом в коллекции отсутствует, метод должен вернуть null.

```java
public ICSSStyleSheet this[int index] { get; }
```

### Возвращаемое значение

Объект [`CSSStyleSheet`](../../icssstylesheet/), или null, если для этого индекса такой объект не существует.

### Property Value

Целое число, представляющее индекс элемента в коллекции, который должен быть возвращён.

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheetlist-item](https://drafts.csswg.org/cssom/#dom-stylesheetlist-item) – The CSSOM definition.

### См. также

* interface [ICSSStyleSheet](../../icssstylesheet/)
* interface [IStyleSheetList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
