---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Справочник API Aspose.HTML для Java"
description: "Свойство IStyleSheet. Для языков таблиц стилей, поддерживающих концепцию включения таблиц стилей, этот атрибут представляет включающую таблицу стилей, если она существует. Если таблица стилей является таблицей верхнего уровня или язык таблиц стилей не поддерживает включение, значение этого атрибута равно null."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Для языков таблиц стилей, поддерживающих концепцию включения таблиц стилей, этот атрибут представляет включающую таблицу стилей, если она существует. Если таблица стилей является таблицей верхнего уровня или язык таблиц стилей не поддерживает включение, значение этого атрибута равно null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

Атрибут parentStyleSheet должен возвращать родительскую [`CSS style sheet`](../../icssstylesheet/).

## Примечания

Это свойство возвращает null, если текущая таблица стилей является таблицей верхнего уровня или если включение таблиц стилей не поддерживается.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### См. также

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
