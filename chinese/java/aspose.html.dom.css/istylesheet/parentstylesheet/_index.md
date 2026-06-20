---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheet 属性。对于支持样式表包含概念的样式表语言，此属性表示包含的样式表（如果存在）。如果样式表是顶层样式表或样式表语言不支持包含，则此属性的值为 null。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

对于支持样式表包含概念的样式表语言，此属性表示包含的样式表（如果存在）。如果样式表是顶层样式表，或样式表语言不支持包含，则此属性的值为 null。

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

parentStyleSheet 属性必须返回父级 [`CSS style sheet`](../../icssstylesheet/)。

## 备注

如果当前样式表是顶层样式表或不支持样式表包含，则此属性返回 null。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### 另请参见

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
