---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML for Java API 参考"
description: "INodeIterator 属性。此标志的值决定实体引用节点的子节点是否对迭代器可见。如果为 false，它们及其后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意，这目前是 NodeIterators 只能拒绝完整子树而不是跳过单个节点的唯一情况。要生成一个文档视图，使实体引用被展开且不暴露实体引用节点本身，请使用 whatToShow 标志隐藏实体引用节点，并在创建迭代器时将 expandEntityReferences 设置为 true。要生成一个文档视图，包含实体引用节点但不进行实体展开，请使用 whatToShow 标志显示实体引用节点，并将 expandEntityReferences 设置为 false。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

此标志的值决定实体引用节点的子节点是否对迭代器可见。如果为 false，它们及其后代将被拒绝。请注意，此拒绝优先于 whatToShow 和过滤器。还要注意，这目前是 NodeIterators 只能拒绝完整子树而不是跳过单个节点的唯一情况。要生成一个文档视图，使实体引用被展开且不暴露实体引用节点本身，请使用 whatToShow 标志隐藏实体引用节点，并在创建迭代器时将 expandEntityReferences 设置为 true。要生成一个文档视图，包含实体引用节点但不进行实体展开，请使用 whatToShow 标志显示实体引用节点，并将 expandEntityReferences 设置为 false。

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` 如果 [expand entity references]；否则为 `false`。

### 另请参见

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
