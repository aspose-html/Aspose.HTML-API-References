---
title: Interface ITreeWalker
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.ITreeWalker 界面. TreeWalker 对象用于使用由其 whatToShow 标志和过滤器如果有定义的文档视图来导航文档树或 子树 使用 TreeWalker 执行导航的任何函数将自动 支持 TreeWalker. 定义的任何视图
type: docs
weight: 2520
url: /zh/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker 对象用于使用由其 whatToShow 标志和过滤器（如果有）定义的文档视图来导航文档树或 子树。 使用 TreeWalker 执行导航的任何函数将自动 支持 TreeWalker. 定义的任何视图

从子树的逻辑视图中省略节点可能导致 结构与 完整、未过滤文档中的同一子树有很大不同。 TreeWalker 视图中的兄弟节点可能是原始视图中不同的、广泛 分隔的节点的子节点。例如，考虑一个 NodeFilter，它跳过除文本节点和 文档根节点之外的所有节点。在结果的逻辑视图中，所有文本 节点都是兄弟节点，并显示为根节点的直接子节点，无论原始文档的结构嵌套多深， 都没有。

另见[文档对象模型 (DOM) 级别 2 遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 级别 2

```csharp
public interface ITreeWalker : ITraversal
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker 当前所在的节点。 对 DOM 树的更改可能导致当前节点不再 被 TreeWalker 的关联过滤器接受。 currentNode 也可以显式设置为任何节点， 无论它是否是在由 the 根节点指定的子树中，或者将被过滤器和 whatToShow 标志接受。进一步遍历相对于 currentNode 即使它不是当前视图的一部分， 通过在请求的方向应用过滤器；如果没有 traversal 是可能的，currentNode 不会改变。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | 将 TreeWalker 移动到 the 当前节点的第一个可见子节点，并返回新节点。如果当前节点有no 个可见子节点，则返回null，并保留current 节点。 |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | 将 TreeWalker 移动到 the 当前节点的最后一个可见子节点，并返回新节点。如果当前节点有no 个可见子节点，则返回null，并保留current 节点。 |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | 将 TreeWalker 移动到相对于当前节点的 document 顺序中的下一个可见节点，并返回新节点。如果 当前节点没有下一个节点，或者搜索nextNode尝试 从TreeWalker的root 节点向上走，返回null，并保留当前节点。 |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | 将 TreeWalker 移动到 current 节点的下一个兄弟节点，并返回新节点。如果当前节点没有visible next sibling，则返回null，并保留当前节点. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | 移动到并返回 current 节点最近的可见祖先节点。如果parentNode的搜索尝试从TreeWalker的根节点向上step ，或者 如果没有找到可见的祖先节点，则该方法保留the 当前位置并返回null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | 将TreeWalker 移动到相对于当前节点的 文档顺序中的上一个可见节点，并返回新的 节点。如果当前节点没有前一个节点，或者搜索 previousNode试图从the TreeWalker的根节点向上一步，返回 null，并保留当前节点. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | 将 TreeWalker 移动到 the 当前节点的前一个兄弟节点，并返回新节点。如果当前节点没有 可见的前一个兄弟节点，则返回null，并保留the 当前节点。 |

### 也可以看看

* interface [ITraversal](../itraversal/)
* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


