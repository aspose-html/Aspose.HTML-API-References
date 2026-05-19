---
title: "IStyleSheet интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.IStyleSheet интерфейс. Интерфейс StyleSheet является абстрактным базовым интерфейсом для любого типа таблицы стилей. Он представляет одну таблицу стилей, связанную со структурированным документом. В HTML интерфейс StyleSheet представляет либо внешнюю таблицу стилей, включённую через элемент HTML LINK, либо встроенный элемент STYLE. В XML этот интерфейс представляет внешнюю таблицу стилей, включённую через инструкцию обработки таблицы стилей. Таблицы стилей CSS далее реализуют более специализированный интерфейс CSSStyleSheet."
type: docs

url: /ru/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

Интерфейс StyleSheet является абстрактным базовым интерфейсом для любого типа таблицы стилей. Он представляет одну таблицу стилей, связанную со структурированным документом. В HTML интерфейс StyleSheet представляет либо внешнюю таблицу стилей, включённую через элемент HTML LINK, либо встроенный элемент STYLE. В XML этот интерфейс представляет внешнюю таблицу стилей, включённую через инструкцию обработки таблицы стилей. Таблицы стилей CSS далее реализуют более специализированный интерфейс [`CSSStyleSheet`](../icssstylesheet/).

Смотрите также [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Свойства

| Имя | Описание |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) Свойство href интерфейса `StyleSheet` возвращает расположение таблицы стилей. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) Свойство media интерфейса `StyleSheet` указывает целевую среду назначения для информации о стиле. Это объект только для чтения, похожий на массив, [`MediaList`](../imedialist/), который можно удалить с помощью deleteMedium() и добавить с помощью appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Узел, связывающий эту таблицу стилей с документом. Для HTML это может быть соответствующий элемент LINK или STYLE. Для XML это может быть инструкция связывания. Для таблиц стилей, включаемых другими таблицами стилей, значение этого атрибута равно null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Для языков таблиц стилей, поддерживающих концепцию включения таблиц стилей, этот атрибут представляет включающую таблицу стилей, если она существует. Если таблица стилей является верхнеуровневой или язык таблиц стилей не поддерживает включение, значение этого атрибута равно null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) Свойство title интерфейса `StyleSheet` возвращает рекомендованное название текущей таблицы стилей. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Это указывает язык таблицы стилей для данной таблицы стилей. Язык таблицы стилей задаётся как тип содержимого (например, "text/css"). |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### См. также

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
