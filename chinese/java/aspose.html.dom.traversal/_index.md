---
title: "com.aspose.html.dom.traversal"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal 包含用于创建迭代器和树遍历器的方法，以在元素之间导航并按文档顺序遍历节点及其子节点。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/
---
该 **com.aspose.html.dom.traversal** 包包含创建迭代器和树遍历器的方法，用于在元素之间导航并按文档顺序遍历节点及其子节点。

## 接口

| 接口 | 描述 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal 包含用于创建迭代器和树遍历器的方法，以按文档顺序（深度优先、先序遍历，这等同于文档文本表示中起始标签出现的顺序）遍历节点及其子节点。在支持 Traversal 功能的 DOM 中，DocumentTraversal 将由实现 Document 接口的同一对象实现。 |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal 接口是一组只读属性，允许作者在文档中轻松地在元素之间导航。在符合 Element Traversal 的实现中，所有实现 Element 的对象也必须实现 ElementTraversal 接口。 |
| [INodeFilter](./inodefilter/) | 过滤器是能够“过滤”节点的对象。如果为 NodeIterator 或 TreeWalker 提供了 NodeFilter，则在返回下一个节点之前会应用该过滤器。如果过滤器接受该节点，遍历逻辑会返回它；否则，遍历会寻找下一个节点，并假装被拒绝的节点不存在。 |
| [INodeIterator](./inodeiterator/) | 迭代器用于遍历一组节点，例如 NodeList 中的节点集合、由特定节点管理的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档顺序遍历文档子树指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator() 创建。 |
| [ITraversal](./itraversal/) | 迭代器用于遍历一组节点，例如 NodeList 中的节点集合、由特定节点管理的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档顺序遍历文档子树指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator() 创建。 |
| [ITreeWalker](./itreewalker/) | TreeWalker 对象用于使用其 whatToShow 标志和过滤器（如果有）定义的文档视图来导航文档树或子树。任何使用 TreeWalker 执行导航的函数都会自动支持 TreeWalker 定义的任何视图。 |
