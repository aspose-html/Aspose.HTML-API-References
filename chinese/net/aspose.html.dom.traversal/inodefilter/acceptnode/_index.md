---
title: INodeFilter.AcceptNode
second_title: Aspose.HTML for .NET API 参考
description: INodeFilter 方法. 测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见这个函数 将被 TreeWalker 和 NodeIterator 的实现调用它通常不会直接从 用户代码调用 尽管如果您想使用相同的 过滤器来指导您自己的应用程序逻辑您可以这样做
type: docs
weight: 10
url: /zh/net/aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。这个函数 将被 TreeWalker 和 NodeIterator 的实现调用；它通常不会直接从 用户代码调用。 （尽管如果您想使用相同的 过滤器来指导您自己的应用程序逻辑，您可以这样做。）

```csharp
public short AcceptNode(Node n)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| n | Node | 节点检查它是否通过过滤器。 |

### 返回值

一个常量，用于确定节点是否被接受、 拒绝或跳过，如上定义。

### 也可以看看

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../inodefilter/)
* 部件 [Aspose.HTML](../../../)


