---
title: "ICSSStyleDeclaration 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSStyleDeclaration 接口。CSSStyleDeclaration 接口表示一个 CSS 声明块对象，并公开样式信息以及各种与样式相关的方法和属性。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssstyledeclaration/
---
## ICSSStyleDeclaration interface

CSSStyleDeclaration 接口表示一个 CSS 声明块对象，并公开样式信息以及各种与样式相关的方法和属性。

CSSStyleDeclaration 对象可以通过三种不同的 API 进行访问：

通过 HTMLElement.style，处理单个元素的内联样式。通过 [`CSSStyleSheet`](../icssstylesheet/) API。例如，document.styleSheets[0].cssRules[0].style 返回文档第一个样式表中第一个 CSS 规则的 `CSSStyleDeclaration` 对象。通过 Window.getComputedStyle()，以只读接口公开 `CSSStyleDeclaration` 对象。

```java
public interface ICSSStyleDeclaration : ICSS2Properties, IEnumerable<String>
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getCSSText]
[setCSSText] The parsable textual representation of the declaration block (excluding the surrounding curly braces). Setting this attribute will result in the parsing of the new value and resetting of all the properties in the declaration block including the removal or addition of properties. |
| [getItem](../../com.aspose.html.dom.css/icssstyledeclaration/item/) 用于检索在此声明块中显式设置的属性。使用此方法检索的属性顺序不必与设置时的顺序相同。此方法可用于遍历此声明块中的所有属性。 |
| [getLength](../../com.aspose.html.dom.css/icssstyledeclaration/length/) 只读属性返回在此 CSS 声明块中显式设置的属性数量的整数。有效索引范围为 0 到 length-1（含）。 |
| [getParentRule](../../com.aspose.html.dom.css/icssstyledeclaration/parentrule/) CSSStyleDeclaration.parentRule 只读属性返回一个 CSSRule，作为此样式块的父级，例如一个表示 CSS 选择器样式的 [`CSSStyleRule`](../icssstylerule/)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [getPropertyCSSValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertycssvalue/)(String) | 用于检索在此声明块中显式设置的 CSS 属性值的对象表示。如果属性是简写属性，则此方法返回 null。简写属性的值只能作为字符串访问和修改，使用 getPropertyValue 和 setProperty 方法。 |
| [getPropertyPriority](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertypriority/)(String) | 用于检索在此声明块中显式设置的 CSS 属性的优先级（例如 “important” 修饰符）。 |
| [getPropertyValue](../../com.aspose.html.dom.css/icssstyledeclaration/getpropertyvalue/)(String) | CSSStyleDeclaration.getPropertyValue() 方法接口返回包含指定 CSS 属性值的字符串。 |
| [removeProperty](../../com.aspose.html.dom.css/icssstyledeclaration/removeproperty/)(String) | CSSStyleDeclaration.removeProperty() 方法接口从 CSS 样式声明对象中移除属性。 |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty)(String, String) | CSSStyleDeclaration.setProperty() 方法接口用于在此声明块中以默认优先级设置属性值。默认优先级不是 “important”，即 String.Empty。 |
| [setProperty](../../com.aspose.html.dom.css/icssstyledeclaration/setproperty/#setproperty_1)(String, String, String) | CSSStyleDeclaration.setProperty() 方法接口用于在此声明块中以默认优先级设置属性值。默认优先级不是 “important”，即 String.Empty。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstyledeclaration](https://drafts.csswg.org/cssom/#cssstyledeclaration) – The CSSOM definition.

### 另请参阅

* interface [ICSS2Properties](../icss2properties/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
