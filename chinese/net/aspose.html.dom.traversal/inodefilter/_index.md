---
title: Interface INodeFilter
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.INodeFilter 界面. 过滤器是知道如何过滤掉节点的对象如果 NodeIterator 或 TreeWalker 被赋予了 NodeFilter它会在返回下一个 节点之前应用过滤器如果过滤器说接受节点遍历逻辑返回 它否则遍历寻找下一个节点并假装被拒绝的 节点不存在
type: docs
weight: 2490
url: /zh/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

过滤器是知道如何“过滤掉”节点的对象。如果 NodeIterator 或 TreeWalker 被赋予了 NodeFilter，它会在返回下一个 节点之前应用过滤器。如果过滤器说接受节点，遍历逻辑返回 它；否则，遍历寻找下一个节点并假装被拒绝的 节点不存在。

DOM 不提供任何过滤器。 NodeFilter 只是一个 接口，用户可以实现它来提供自己的过滤器。

NodeFilters不需要知道如何从节点 遍历到节点，也不需要知道 正在遍历的数据结构。这使得编写过滤器变得非常容易，因为 他们唯一需要知道如何做的就是评估单个节点。一个 过滤器可用于多种不同类型的遍历， 鼓励代码重用。

另见[文档对象模型 (DOM) 级别 2 遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 级别 2

```csharp
public interface INodeFilter
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | 测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。这个函数 将被 TreeWalker 和 NodeIterator 的实现调用；它通常不会直接从 用户代码调用。 （尽管如果您想使用相同的 过滤器来指导您自己的应用程序逻辑，您可以这样做。） |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


