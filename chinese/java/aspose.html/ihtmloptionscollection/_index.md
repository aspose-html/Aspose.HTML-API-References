---
title: "IHTMLOptionsCollection 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.IHTMLOptionsCollection 接口。HTMLOptionsCollection 是表示 HTML option 元素的节点列表。可以通过序号索引或节点的 name 或 id 属性访问单个节点。HTML DOM 中的集合被视为实时的，这意味着当底层文档更改时，它们会自动更新。"
type: docs

url: /zh/java/com.aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

`HTMLOptionsCollection` 是表示 HTML option 元素的节点列表。可以通过序数索引或节点的 `name` 或 `id` 属性访问单个节点。HTML DOM 中的集合被视为实时的，这意味着当底层文档更改时，它们会自动更新。

另请参阅 [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109)。@since DOM Level 2

```java
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html/ihtmloptionscollection/item/) 返回集合中第 index 项。如果 index 大于或等于列表中节点的数量，则返回 null。（2 个索引器） |
| [getLength](../../com.aspose.html/ihtmloptionscollection/length/) 列表中节点的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [namedItem](../../com.aspose.html/ihtmloptionscollection/nameditem/)(String) | 该方法返回集合中第 index 项。http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### 另请参见

* class [Element](../../com.aspose.html.dom/element/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
