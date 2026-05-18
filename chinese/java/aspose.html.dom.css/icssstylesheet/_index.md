---
title: "ICSSStyleSheet 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSStyleSheet 接口。CSSStyleSheet 接口表示单个 CSS 样式表，并允许您检查和修改样式表中包含的规则列表。它继承自其父接口 IStyleSheet 的属性和方法。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssstylesheet/
---
## ICSSStyleSheet interface

CSSStyleSheet 接口表示单个 CSS 样式表，并允许您检查和修改样式表中包含的规则列表。它继承自其父接口 [`IStyleSheet`](../istylesheet/) 的属性和方法。

样式表由一组 [`ICSSRule`](../icssrule/) 对象组成，表示样式表中的每条规则。这些规则包含在一个 [`ICSSRuleList`](../icssrulelist/) 中，可通过样式表的 cssRules 属性获取。

例如，一条规则可能是包含如下样式的 [`ICSSStyleRule`](../icssstylerule/) 对象

```java
h1, h2 {   font-size: 16pt; }
```

另一条规则可能是诸如 @import 或 @media 等 at-rule，依此类推。

```java
public interface ICSSStyleSheet : IStyleSheet
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssstylesheet/cssrules/) 只读的 CSSStyleSheet 属性 cssRules 返回一个实时的 [`CSSRuleList`](../icssrulelist/)，它提供了组成样式表的每个 CSS 规则的实时、最新列表。列表中的每个项都是定义单个规则的 [`CSSRule`](../icssrule/)。 |
| [getOwnerRule](../../com.aspose.html.dom.css/icssstylesheet/ownerrule/) 只读的 CSSStyleSheet 属性 ownerRule 返回对应于将样式表导入文档的 @import at-rule 的 [`CSSImportRule`](../icssimportrule/)。如果样式表不是通过 @import 导入到文档中的，则返回值为 null。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssstylesheet/deleterule/)(int) | `CSSStyleSheet` 的 deleteRule() 方法从样式表对象中移除一条规则。 |
| [insertRule](../../com.aspose.html.dom.css/icssstylesheet/insertrule/)(String, int) | CSSStyleSheet.insertRule() 方法在当前样式表中插入一条新的 CSS 规则，但有一些限制。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # cssstylesheet](https://drafts.csswg.org/cssom/#cssstylesheet) – The CSSOM definition.

### 另请参阅

* interface [IStyleSheet](../istylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
