---
title: "ICSSKeyframesRule 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSKeyframesRule 接口。CSSKeyframeRule 接口的 name 属性获取和设置动画名称，该名称用于 animation-name 属性。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icsskeyframesrule/
---
## ICSSKeyframesRule interface

CSSKeyframeRule 接口的 name 属性获取和设置动画名称，该名称用于 animation-name 属性。

```java
public interface ICSSKeyframesRule : ICSSRule
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getCSSRules](../../com.aspose.html.dom.css/icsskeyframesrule/cssrules/) 只读的 cssRules 属性（来自 [`CSSKeyframeRule`](../icsskeyframerule/) 接口）返回一个包含关键帧 at-rule 中规则的 [`CSSRuleList`](../icssrulelist/)。 |
| [getName](../../com.aspose.html.dom.css/icsskeyframesrule/name/) [`CSSKeyframeRule`](../icsskeyframerule/) 接口的 name 属性获取和设置动画名称，该名称用于 animation-name 属性。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [appendRule](../../com.aspose.html.dom.css/icsskeyframesrule/appendrule/)(String) | appendRule 方法将在关键帧规则集合的末尾追加传入的 [`CSSKeyframeRule`](../icsskeyframerule/)。 |
| [deleteRule](../../com.aspose.html.dom.css/icsskeyframesrule/deleterule/)(String) | deleteRule 方法会删除具有给定键的 [`CSSKeyframeRule`](../icsskeyframerule/)。如果不存在具有该键的规则，方法不执行任何操作。 |
| [findRule](../../com.aspose.html.dom.css/icsskeyframesrule/findrule/)(String) | findRule 方法返回键与给定键匹配的规则。如果不存在此类规则，则返回 null 值。 |

### 另请参阅

* interface [ICSSRule](../icssrule/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
