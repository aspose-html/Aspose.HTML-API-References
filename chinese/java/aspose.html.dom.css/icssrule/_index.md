---
title: "ICSSRule 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSRule 接口。CSSRule 接口是任何类型 CSS 语句的抽象基接口。它包括规则集和 at-rule。实现应保留 CSS 样式表中指定的所有规则，即使解析器未识别某些规则。未识别的规则使用该接口表示。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssrule/
---
## ICSSRule interface

CSSRule 接口是任何类型 CSS 语句的抽象基接口。它包括规则集和 at-rule。实现应保留 CSS 样式表中指定的所有规则，即使解析器未识别某些规则。未识别的规则使用该接口表示。

```java
public interface ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getCSSText]
[setCSSText] The cssText property of the `CSSRule` interface returns the actual text of a [`CSSStyleSheet`](../icssstylesheet/) style-rule. |
| [getParentRule](../../com.aspose.html.dom.css/icssrule/parentrule/) 如果此规则包含在另一个规则内部（例如 @media 块中的样式规则），则返回包含它的规则。如果此规则未嵌套在任何其他规则中，则返回 null。 |
| [getParentStyleSheet](../../com.aspose.html.dom.css/icssrule/parentstylesheet/) `CSSRule` 接口的 parentStyleSheet 属性返回定义当前规则的 [`StyleSheet`](../istylesheet/) 对象。 |
| [getType](../../com.aspose.html.dom.css/icssrule/type/) 规则的类型，如 [CSSOM # dom-cssrule-type](https://drafts.csswg.org/cssom/#dom-cssrule-type) 所定义。预期可以使用绑定特定的强制转换方法，将 CSSRule 接口的实例向下转换为由该类型暗示的具体派生接口。 |

### 另请参见

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
