---
title: Interface ITraversal
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.ITraversal 界面. 迭代器用于遍历一组节点例如 NodeList 中的 节点集由 特定节点管理的文档子树查询结果或任何其他 节点集要迭代的节点集由 NodeIterator 的 实现确定 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator. 创建的
type: docs
weight: 2510
url: /zh/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

迭代器用于遍历一组节点，例如 NodeList 中的 节点集、由 特定节点管理的文档子树、查询结果或任何其他 节点集。要迭代的节点集由 NodeIterator 的 实现确定。 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现。这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator(). 创建的

另见[文档对象模型 (DOM) 级别 2 遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 级别 2

```csharp
public interface ITraversal : IDisposable
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | 用来筛选节点的NodeFilter。 |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | NodeIterator 的根节点，在创建它 时指定。 |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | 此属性确定哪些节点类型通过 迭代器呈现。可用的常量集在 NodeFilter 接口中定义。未被 whatToShow 接受的节点将被跳过，但它们的子节点可能仍 被考虑。请注意，此跳过优先于过滤器 （如果有）。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


