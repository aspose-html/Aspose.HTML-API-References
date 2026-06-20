---
title: "ITreeWalker.NextNode"
second_title: "Aspose.HTML for Java API 参考"
description: "ITreeWalker 方法。将 TreeWalker 移动到相对于当前节点的文档顺序中下一个可见节点，并返回该新节点。如果当前节点没有下一个节点，或者对 nextNode 的搜索尝试从 TreeWalker 的根节点向上移动，则返回 null 并保留当前节点。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/itreewalker/nextnode/
---
## ITreeWalker.NextNode method

将 TreeWalker 按文档顺序移动到相对于当前节点的下一个可见节点，并返回该新节点。如果当前节点没有下一个节点，或在从 TreeWalker 的根节点向上搜索 nextNode 时，返回 null，并保持当前节点不变。

```java
public Node NextNode()
```

### 返回值

新节点，如果在 TreeWalker 的逻辑视图中当前节点没有下一个节点，则为 null。

### 另请参见

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
