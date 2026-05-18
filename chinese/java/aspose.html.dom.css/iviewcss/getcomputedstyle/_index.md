---
title: "IViewCSS.GetComputedStyle"
second_title: "Aspose.HTML for Java API 参考"
description: "IViewCSS 方法。IViewCSS.getComputedStyle 方法返回一个对象，包含元素在应用活动样式表并解析可能的基本计算后所有 CSS 属性的值。"
type: docs

url: /zh/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

IViewCSS.getComputedStyle() 方法返回一个对象，包含元素所有 CSS 属性的值，已应用活动样式表并解析这些值可能包含的基本计算。

单个 CSS 属性值可通过对象提供的 API 访问，或通过使用 CSS 属性名称进行索引。

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | Element | 用于获取计算样式的 [`Element`](../../../com.aspose.html.dom/element/)。此参数不能为空。 |

### 返回值

返回的样式是一个实时的 [`CSSStyleDeclaration`](../../icssstyledeclaration/) 对象，当元素的样式更改时会自动更新。

### 异常

| 异常 | 条件 |
| --- | --- |
| TypeError | 如果传入的对象不是 Element，或者 pseudoElt 不是有效的伪元素选择器。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 另请参阅

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

IViewCSS.getComputedStyle() 方法返回一个对象，包含元素所有 CSS 属性的值，已应用活动样式表并解析这些值可能包含的基本计算。

单个 CSS 属性值可通过对象提供的 API 访问，或通过使用 CSS 属性名称进行索引。

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | Element | 用于获取计算样式的 [`Element`](../../../com.aspose.html.dom/element/)。此参数不能为空。 |
| pseudoElement | String | 一个字符串，指定要匹配的伪元素。对于真实元素可省略（或为 null）。 |

### 返回值

返回的样式是一个实时的 [`CSSStyleDeclaration`](../../icssstyledeclaration/) 对象，当元素的样式更改时会自动更新。

### 异常

| 异常 | 条件 |
| --- | --- |
| TypeError | 如果传入的对象不是 Element，或者 pseudoElt 不是有效的伪元素选择器。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### 另请参阅

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
