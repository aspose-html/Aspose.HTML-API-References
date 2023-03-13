---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML for .NET API 参考
description: ITreeWalker 财产. TreeWalker 当前所在的节点 对 DOM 树的更改可能导致当前节点不再 被 TreeWalker 的关联过滤器接受 currentNode 也可以显式设置为任何节点 无论它是否是在由 the 根节点指定的子树中或者将被过滤器和 whatToShow 标志接受进一步遍历相对于 currentNode 即使它不是当前视图的一部分 通过在请求的方向应用过滤器如果没有 traversal 是可能的currentNode 不会改变
type: docs
weight: 10
url: /zh/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker 当前所在的节点。 对 DOM 树的更改可能导致当前节点不再 被 TreeWalker 的关联过滤器接受。 currentNode 也可以显式设置为任何节点， 无论它是否是在由 the 根节点指定的子树中，或者将被过滤器和 whatToShow 标志接受。进一步遍历相对于 currentNode 即使它不是当前视图的一部分， 通过在请求的方向应用过滤器；如果没有 traversal 是可能的，currentNode 不会改变。

```csharp
public Node CurrentNode { get; set; }
```

### 适当的价值

当前节点。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：如果尝试将 set currentNode 设置为空则引发。 |

### 也可以看看

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../itreewalker/)
* 部件 [Aspose.HTML](../../../)


