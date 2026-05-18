---
title: "IStyleSheetList.Item"
second_title: "Aspose.HTML for Java API 参考"
description: "IStyleSheetList 属性。itemindex 方法必须返回集合中第 index 个 CSS 样式表。如果集合中不存在第 index 个对象，则方法必须返回 null。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheetlist/item/
---
## IStyleSheetList indexer

item(index) 方法必须返回集合中第 index 个 [`CSS style sheet`](../../icssstylesheet/)。如果集合中不存在第 index 个对象，则方法必须返回 null。

```java
public ICSSStyleSheet this[int index] { get; }
```

### 返回值

一个 [`CSSStyleSheet`](../../icssstylesheet/) 对象，如果该索引不存在则为 null。

### Property Value

一个整数，表示要返回的集合中项目的索引。

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheetlist-item](https://drafts.csswg.org/cssom/#dom-stylesheetlist-item) – The CSSOM definition.

### 另请参阅

* interface [ICSSStyleSheet](../../icssstylesheet/)
* interface [IStyleSheetList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
