---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML for .NET API 参考
description: INodeIterator 财产. 该标志的值决定了 entity 引用节点的子节点是否对迭代器可见如果为假他们和 他们的后代将被拒绝请注意此拒绝优先于 whatToShow 和过滤器还要注意 这是目前唯一的情况其中 NodeIterators 可能会拒绝一个完整的子树而不是 跳过单个节点 要生成具有实体引用 扩展并且不公开实体引用节点本身的文档视图请使用 whatToShow 标志隐藏实体引用 node 并在创建 the 迭代器时将 expandEntityReferences 设置为 true要生成具有实体 reference 节点但没有实体扩展的文档视图请使用 whatToShow flags 显示实体引用节点并将 set expandEntityReferences 设置为 false.
type: docs
weight: 10
url: /zh/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

该标志的值决定了 entity 引用节点的子节点是否对迭代器可见。如果为假，他们和 他们的后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意 ，这是目前唯一的情况，其中 NodeIterators 可能会拒绝一个完整的子树，而不是 跳过单个节点。 要生成具有实体引用 扩展并且不公开实体引用节点本身的文档视图，请使用 whatToShow 标志隐藏实体引用 node 并在创建 the 迭代器时将 expandEntityReferences 设置为 true。要生成具有实体 reference 节点但没有实体扩展的文档视图，请使用 whatToShow flags 显示实体引用节点并将 set expandEntityReferences 设置为 false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### 适当的价值

`真的`如果[展开实体引用]；否则，`错误的`.

### 也可以看看

* interface [INodeIterator](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* 部件 [Aspose.HTML](../../../)


