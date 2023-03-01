---
title: INodeIterator.NextNode
second_title: Aspose.HTML for .NET API 参考
description: INodeIterator 方法. 返回集合中的下一个节点并将 迭代器在集合中的位置向前推进创建 NodeIterator 后 第一次调用 nextNode 返回第一个节点 in set.
type: docs
weight: 40
url: /zh/net/aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

返回集合中的下一个节点，并将 迭代器在集合中的位置向前推进。创建 NodeIterator 后， 第一次调用 nextNode() 返回第一个节点 in set.

```csharp
public Node NextNode()
```

### 返回值

正在迭代的集合中的下一个节点，如果该集合中没有更多成员，则 null.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR：如果在调用 the detach 方法之后调用此方法，则引发。 |

### 也可以看看

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeIterator](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* 部件 [Aspose.HTML](../../../)


