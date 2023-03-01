---
title: Interface IHTMLOptionsCollection
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.IHTMLOptionsCollection 界面. 一个HTMLOptions 集合是表示 HTML 选项元素的节点列表单个节点可以通过序号 索引或节点的姓名或者ID属性 HTML DOM 中的集合被假定为实时的这意味着它们在基础文档更改时 自动更新
type: docs
weight: 3680
url: /zh/net/aspose.html/ihtmloptionscollection/
---
## IHTMLOptionsCollection interface

一个`HTMLOptions 集合`是表示 HTML 选项元素的节点列表。单个节点可以通过序号 索引或节点的`姓名`或者`ID`属性。 HTML DOM 中的集合被假定为实时的，这意味着它们在基础文档更改时 自动更新。

另见[文档对象模型 (DOM) 2 级 HTML 规范](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109). @since DOM 级别 2

```csharp
public interface IHTMLOptionsCollection : IEnumerable<Element>
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Item](../../aspose.html/ihtmloptionscollection/item/) { get; } | 返回集合中的第 indexth 个项目。如果索引大于或等于列表中的节点数，则返回 null. (2 indexers) |
| [Length](../../aspose.html/ihtmloptionscollection/length/) { get; } | 列表中的节点数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [NamedItem](../../aspose.html/ihtmloptionscollection/nameditem/)(string) | 方法返回集合中的第 indexth 个项目。 http://www.w3.org/TR/DOM-Level-2-HTML/html.html#HTMLOptionsCollection-namedItem |

### 也可以看看

* class [Element](../../aspose.html.dom/element/)
* 命名空间 [Aspose.Html](../../aspose.html/)
* 部件 [Aspose.HTML](../../)


