---
title: "IMediaList Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.IMediaList интерфейс. Интерфейс MediaList предоставляет абстракцию упорядоченной коллекции носителей без определения или ограничения того, как эта коллекция реализована. Пустой список эквивалентен списку, содержащему все носители."
type: docs

url: /ru/java/com.aspose.html.dom.css/imedialist/
---
## IMediaList interface

Интерфейс MediaList предоставляет абстракцию упорядоченной коллекции медиа, не определяя и не ограничивая способ реализации этой коллекции. Пустой список эквивалентен списку, содержащему средство "all".

Смотрите также [CSS Object Model (CSSOM) # ](https://www.w3.org/TR/cssom-1/#the-medialist-interface)[MediaList](https://www.w3.org/TR/cssom-1/#the-medialist-interface).

```java
public interface IMediaList : IEnumerable<String>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/imedialist/item/) Метод item(index) должен возвращать сериализацию медиазапроса в коллекции медиазапросов по указанному индексу, или null, если индекс больше или равен количеству медиазапросов в коллекции. |
| [getLength](../../com.aspose.html.dom.css/imedialist/length/) Атрибут length должен возвращать количество медиазапросов в коллекции медиазапросов. Диапазон допустимых значений от 0 до length‑1 включительно. |
| [getMediaText](../../com.aspose.html.dom.css/imedialist/mediatext/) Строковый преобразователь, который возвращает DOMString, представляющий MediaList в виде текста, а также позволяет задать новый MediaList. |

## Методы

| Имя | Описание |
| --- | --- |
| [appendMedium](../../com.aspose.html.dom.css/imedialist/appendmedium/)(String) | Добавляет носитель newMedium в конец списка. Если newMedium уже используется, он сначала удаляется. |
| [deleteMedium](../../com.aspose.html.dom.css/imedialist/deletemedium/)(String) | Удаляет из списка носитель, указанный как oldMedium. |

## Примечания

Примечание: MediaList является живым списком; обновление списка с помощью свойств или методов, перечисленных ниже, немедленно изменит поведение документа.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # medialist](https://drafts.csswg.org/cssom/#medialist) – The CSSOM definition.

## Примеры

Следующий код выведет в консоль текстовое представление MediaList первой таблицы стилей, применённой к текущему документу.

```java
var stylesheets = document.StyleSheets;
var stylesheet = stylesheets[0];
Console.Write(stylesheet.Media.MediaText);
```

### См. также

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
