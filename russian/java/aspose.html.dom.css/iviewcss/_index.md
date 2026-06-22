---
title: "IViewCSS Интерфейс"
second_title: "Справочник API Aspose.HTML для Java"
description: "com.aspose.html.dom.css.IViewCSS интерфейс. Интерфейс IViewCSS представляет расширение объекта Window, которое предоставляет доступ к значениям всех CSS‑свойств элемента."
type: docs

url: /ru/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

Интерфейс IViewCSS представляет расширение объекта Window, которое предоставляет доступ к значениям всех CSS‑свойств элемента.

CSS‑стиль данного элемента можно получить с помощью метода IViewCSS.GetComputedStyle().

```java
public interface IViewCSS : IAbstractView
```

## Методы

| Имя | Описание |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | Метод IViewCSS.getComputedStyle() возвращает объект, содержащий значения всех CSS‑свойств элемента после применения активных таблиц стилей и разрешения любой базовой вычисляемой информации, содержащейся в этих значениях. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | Метод IViewCSS.getComputedStyle() возвращает объект, содержащий значения всех CSS‑свойств элемента после применения активных таблиц стилей и разрешения любой базовой вычисляемой информации, содержащейся в этих значениях. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### См. также

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
