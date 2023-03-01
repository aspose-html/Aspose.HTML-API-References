---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML for .NET API 参考
description: 的 Aspose.Html.Dom.遍历命名空间包含 创建迭代器和树遍历器以在元素之间导航和 按文档顺序遍历节点及其子节点的方法
type: docs
weight: 170
url: /zh/net/aspose.html.dom.traversal/
---
的 **Aspose.Html.Dom.遍历**命名空间包含 创建迭代器和树遍历器以在元素之间导航和 按文档顺序遍历节点及其子节点的方法。

## 接口

| 界面 | 描述 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal包含创建迭代器和 tree-walkers的方法，以文档顺序遍历节点及其子节点（深度 优先，前序遍历，相当于 开始标记在文本表示中出现的顺序文档）。在支持遍历功能的 DOM 中，DocumentTraversal 将 由实现 Document 接口的相同对象实现。 |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal 接口是一组只读属性，允许作者轻松地在文档中的元素之间导航。在 Element Traversal 的一致性实现中，所有实现 Element 的对象也必须实现 ElementTraversal 接口。 |
| [INodeFilter](./inodefilter/) | 过滤器是知道如何“过滤掉”节点的对象。如果 NodeIterator 或 TreeWalker 被赋予了 NodeFilter，它会在返回下一个 节点之前应用过滤器。如果过滤器说接受节点，遍历逻辑返回 它；否则，遍历寻找下一个节点并假装被拒绝的 节点不存在。 |
| [INodeIterator](./inodeiterator/) | 迭代器用于遍历一组节点，例如 NodeList 中的 节点集、由 特定节点管理的文档子树、查询结果或任何其他 节点集。要迭代的节点集由 NodeIterator 的 实现确定。 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现。这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator(). 创建的 |
| [ITraversal](./itraversal/) | 迭代器用于遍历一组节点，例如 NodeList 中的 节点集、由 特定节点管理的文档子树、查询结果或任何其他 节点集。要迭代的节点集由 NodeIterator 的 实现确定。 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现。这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator(). 创建的 |
| [ITreeWalker](./itreewalker/) | TreeWalker 对象用于使用由其 whatToShow 标志和过滤器（如果有）定义的文档视图来导航文档树或 子树。 使用 TreeWalker 执行导航的任何函数将自动 支持 TreeWalker. 定义的任何视图 |


