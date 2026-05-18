---
title: "IStyleSheetList 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.IStyleSheetList 接口。StyleSheetList 接口表示 CSSStyleSheet 对象的列表。可以通过 Document.styleSheets 获取该对象的实例。"
type: docs

url: /zh/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

StyleSheetList 接口表示一个由 [`CSSStyleSheet`](../icssstylesheet/) 对象组成的列表。可以通过 [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/) 获取该对象的实例。

对象支持的属性索引是从零到集合中 CSS 样式表数量减一的范围内的数字。如果没有此类 CSS 样式表，则不存在支持的属性索引。

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) item(index) 方法必须返回集合中第 index 个 [`CSS style sheet`](../icssstylesheet/)。如果集合中不存在第 index 个对象，则该方法必须返回 null。 |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) length 属性必须返回集合中 CSS 样式表的数量。有效的子样式表索引范围为 0 到 length-1（含）。 |

## 备注

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

参考

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### 另请参阅

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
