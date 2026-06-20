---
title: "IStyleSheet.Href"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheet 属性。StyleSheet 接口的 href 属性返回样式表的位置。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/href/
---
## IStyleSheet.Href property

The href property of the [`StyleSheet`](../) interface returns the location of the style sheet.

```java
public String Href { get; }
```

### Property Value

uri 是包含样式表 URI 的字符串。

## 备注

如果样式表是链接的样式表，则其属性值为其位置。对于内联样式表，此属性的值为 NULL。

此属性在 Firefox、Opera、Google Chrome 和 Safari 中为只读，在 Internet Explorer 中为读写。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-href](https://drafts.csswg.org/cssom/#dom-stylesheet-href) – The CSSOM definition.

### 另请参见

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
