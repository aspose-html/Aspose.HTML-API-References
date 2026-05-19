---
title: "IViewCSS.GetComputedStyle"
second_title: "Справочник API Aspose.HTML для Java"
description: "Метод IViewCSS. Метод IViewCSS.getComputedStyle возвращает объект, содержащий значения всех CSS‑свойств элемента после применения активных таблиц стилей и разрешения любой базовой вычисляемости этих значений."
type: docs

url: /ru/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

Метод IViewCSS.getComputedStyle() возвращает объект, содержащий значения всех CSS‑свойств элемента после применения активных таблиц стилей и разрешения любой базовой вычисляемой информации, содержащейся в этих значениях.

Отдельные значения CSS‑свойств доступны через API, предоставляемый объектом, или через индексацию по именам CSS‑свойств.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | Element | [`Element`](../../../com.aspose.html.dom/element/), для которого необходимо получить вычисленный стиль. Этот параметр не может быть null. |

### Возвращаемое значение

Возвращаемый стиль — это живой объект [`CSSStyleDeclaration`](../../icssstyledeclaration/), который автоматически обновляется при изменении стилей элемента.

### Исключения

| исключение | условие |
| --- | --- |
| TypeError | Если переданный объект не является Element или pseudoElt не является допустимым селектором псевдо‑элемента. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### См. также

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

Метод IViewCSS.getComputedStyle() возвращает объект, содержащий значения всех CSS‑свойств элемента после применения активных таблиц стилей и разрешения любой базовой вычисляемой информации, содержащейся в этих значениях.

Отдельные значения CSS‑свойств доступны через API, предоставляемый объектом, или через индексацию по именам CSS‑свойств.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | Element | [`Element`](../../../com.aspose.html.dom/element/), для которого необходимо получить вычисленный стиль. Этот параметр не может быть null. |
| pseudoElement | String | Строка, указывающая псевдо‑элемент для сопоставления. Опускается (или null) для реальных элементов. |

### Возвращаемое значение

Возвращаемый стиль — это живой объект [`CSSStyleDeclaration`](../../icssstyledeclaration/), который автоматически обновляется при изменении стилей элемента.

### Исключения

| исключение | условие |
| --- | --- |
| TypeError | Если переданный объект не является Element или pseudoElt не является допустимым селектором псевдо‑элемента. |

## Примечания

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Ссылка

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### См. также

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
