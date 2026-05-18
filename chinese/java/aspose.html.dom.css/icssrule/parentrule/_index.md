---
title: "ICSSRule.ParentRule"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSSRule 属性。如果此规则包含在另一个规则中，例如在媒体块中的样式规则，则它是包含规则。如果此规则未嵌套在任何其他规则中，则返回 null。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssrule/parentrule/
---
## ICSSRule.ParentRule property

如果此规则包含在另一个规则中（例如在 @media 块中的样式规则），则它是包含规则。如果此规则未嵌套在任何其他规则中，则返回 null。

```java
public ICSSRule ParentRule { get; }
```

### Property Value

一个 [`CSSRule`](../) ，它是包含规则的类型。如果当前规则位于媒体查询中，则返回 [`CSSMediaRule`](../../icssmediarule/)。否则返回 null。

### 另请参阅

* interface [ICSSRule](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
