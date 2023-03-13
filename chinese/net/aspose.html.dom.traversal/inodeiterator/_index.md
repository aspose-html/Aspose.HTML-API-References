---
title: Interface INodeIterator
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.INodeIterator 界面. 迭代器用于遍历一组节点例如 NodeList 中的 节点集由 特定节点管理的文档子树查询结果或任何其他 节点集要迭代的节点集由 NodeIterator 的 实现确定 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator. 创建的
type: docs
weight: 2500
url: /zh/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

迭代器用于遍历一组节点，例如 NodeList 中的 节点集、由 特定节点管理的文档子树、查询结果或任何其他 节点集。要迭代的节点集由 NodeIterator 的 实现确定。 DOM 级别 2 为文档子树的文档顺序 遍历指定了 单个 NodeIterator 实现。这些迭代器的实例是通过调用 DocumentTraversal .createNodeIterator(). 创建的

另见[文档对象模型 (DOM) 级别 2 遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 级别 2

```csharp
public interface INodeIterator : ITraversal
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | 该标志的值决定了 entity 引用节点的子节点是否对迭代器可见。如果为假，他们和 他们的后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意 ，这是目前唯一的情况，其中 NodeIterators 可能会拒绝一个完整的子树，而不是 跳过单个节点。 要生成具有实体引用 扩展并且不公开实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用 node 并在创建 the 迭代器时将 expandEntityReferences 设置为 true。要生成具有实体 reference 节点但没有实体扩展的文档视图，请使用 whatToShow flags 显示实体引用节点并将 set expandEntityReferences 设置为 false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | 当前参考节点。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | 将 NodeIterator 从它迭代 的集合中分离出来，释放所有计算资源并将 iterator 置于无效状态。调用分离后， 调用 nextNode 或 previousNode 将 引发异常 INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | 返回集合中的下一个节点，并将 迭代器在集合中的位置向前推进。创建 NodeIterator 后， 第一次调用 nextNode() 返回第一个节点 in set. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | 返回集合中的前一个节点并将 NodeIterator在集合中的位置向后移动。 |

### 也可以看看

* interface [ITraversal](../itraversal/)
* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


