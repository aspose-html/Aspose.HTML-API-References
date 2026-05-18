---
title: "IStyleSheet.OwnerNode"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheet 属性。将此样式表与文档关联的节点。对于 HTML，可能是相应的 LINK 或 STYLE 元素。对于 XML，可能是链接的处理指令。对于被其他样式表包含的样式表，此属性的值为 null。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

将此样式表与文档关联的节点。对于 HTML，可能是相应的 LINK 或 STYLE 元素。对于 XML，可能是链接的处理指令。对于被其他样式表包含的样式表，此属性的值为 null。

```java
public Node OwnerNode { get; }
```

### Property Value

ownerNode 属性必须返回所有者节点。

## 备注

对于被其他样式表包含的样式表，例如使用 @import， 此属性的值为 null。

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### 另请参阅

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
