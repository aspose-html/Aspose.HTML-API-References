---
title: "ICSSMediaRule 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSMediaRule 接口。CSSMediaRule 接口表示 CSS 样式表中的媒体规则。媒体规则可用于限定特定媒体类型的样式规则。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssmediarule/
---
## ICSSMediaRule interface

CSSMediaRule 接口表示 CSS 样式表中的 @media 规则。@media 规则可用于限定特定媒体类型的样式规则。

```java
public interface ICSSMediaRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icssmediarule/cssrules/) CSSGroupingRule 接口的 cssRules 属性返回一个 [`CSSRuleList`](../icssrulelist/)，其中包含一系列 [`CSSRule`](../icssrule/) 对象。 |
| [getMedia](../../com.aspose.html.dom.css/icssmediarule/media/) `CSSMediaRule` 接口的只读 media 属性（MediaList）表示样式信息的目标介质。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [deleteRule](../../com.aspose.html.dom.css/icssmediarule/deleterule/)(long) | CSSGroupingRule 接口的 deleteRule() 方法从子 CSS 规则列表中移除一个 CSS 规则。 |
| [insertRule](../../com.aspose.html.dom.css/icssmediarule/insertrule/)(String, long) | CSSGroupingRule 接口的 insertRule() 方法向 CSS 规则列表中添加一个新 CSS 规则。 |

### 另请参见

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
