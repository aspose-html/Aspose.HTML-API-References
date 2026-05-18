---
title: "IStyleSheet.Disabled"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheet 属性。StyleSheet 接口的 disabled 属性决定样式表是否被阻止应用于文档。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

[`StyleSheet`](../) 接口的 disabled 属性决定样式表是否被阻止应用于文档。

可以通过手动将此属性设为 true，或当它是非活动的替代样式表时，来禁用样式表。请注意，disabled == false 并不保证样式表已应用（例如，它可能已从文档中移除）。

修改此属性可能导致文档的样式重新解析。只有在存在适当的媒体定义且 disabled 属性为 false 时，样式表才会应用。因此，如果媒体不适用于当前用户代理，则会忽略 disabled 属性。

```java
public bool Disabled { get; set; }
```

### 返回值

获取 disabled 属性时，如果已设置 disabled 标志，则必须返回 true，否则返回 false。设置时，如果新值为 true，则 disabled 属性必须设置 disabled 标志；否则必须取消该标志。

### Property Value

获取 disabled 属性时，如果已设置 disabled 标志，则必须返回 true，否则返回 false。设置时，如果新值为 true，则 disabled 属性必须设置 disabled 标志；否则必须取消该标志。

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### 另请参阅

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
