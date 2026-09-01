---
title: "ICSSStyleSheet Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.ICSSStyleSheet интерфейс. Интерфейс CSSStyleSheet представляет один CSS‑стилевой лист и позволяет просматривать и изменять список правил, содержащихся в листе стилей. Он наследует свойства и методы от своего родителя IStyleSheet."
type: docs

url: /ru/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

Интерфейс CSSStyleSheet представляет один CSS‑стилевой лист и позволяет просматривать и изменять список правил, содержащихся в листе стилей. Он наследует свойства и методы от своего родителя, [`IStyleSheet`](../istylesheet/).

Таблица стилей состоит из коллекции объектов [`ICSSRule`](../icssrule/), представляющих каждое правило в таблице стилей. Правила находятся в [`ICSSRuleList`](../icssrulelist/), который можно получить через свойство cssRules таблицы стилей.

Например, одним из правил может быть объект [`ICSSStyleRule`](../icssstylerule/), содержащий стиль, такой как

```java
h1, h2 {   font-size: 16pt; }
```

Другим правилом может быть at‑rule, например @import или @media, и т.д.

```java
public interface ICSSStyleSheet : IStyleSheet
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) Свойство только для чтения cssRules интерфейса CSSStyleSheet возвращает живой [`CSSRuleList`](../icssrulelist/), который предоставляет актуальный в реальном времени список всех CSS‑правил, составляющих таблицу стилей. Каждый элемент списка — это [`CSSRule`](../icssrule/), определяющий отдельное правило. |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) Свойство только для чтения ownerRule интерфейса CSSStyleSheet возвращает [`CSSImportRule`](../icssimportrule/), соответствующее at‑rule @import, который импортировал таблицу стилей в документ. Если таблица стилей не была импортирована в документ с помощью @import, возвращаемое значение равно null. |

## Методы

| Имя | Описание |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | Метод `CSSStyleSheet` deleteRule() удаляет правило из объекта таблицы стилей. |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | Метод CSSStyleSheet.insertRule() вставляет новое CSS‑правило в текущую таблицу стилей с некоторыми ограничениями. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### См. также

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
