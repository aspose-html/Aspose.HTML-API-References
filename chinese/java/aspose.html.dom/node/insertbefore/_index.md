---
title: "Node.InsertBefore"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。Node 接口的 insertBefore 方法将在指定父节点的子节点中，在参考节点之前插入一个节点。"
type: docs

url: /zh/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

insertBefore() 方法属于 Node 接口，将一个节点插入为指定父节点的子节点，位置在参考节点之前。

如果给定的节点已经存在于文档中，insertBefore() 会将其从当前位置移动到新位置。（即，它会在将其追加到指定的新父节点之前，自动从其现有父节点中移除。）

这意味着一个节点不能同时位于文档的两个位置。

```java
public Node InsertBefore(Node node, Node child)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | Node | 要插入的节点。 |
| 子节点 | Node | newNode 被插入之前的节点。如果此值为 null，则 newNode 将插入到该节点子节点列表的末尾。 |

### 返回值

返回添加的子节点（除非 newNode 是 [`DocumentFragment`](../../documentfragment/)，在这种情况下返回空的 [`DocumentFragment`](../../documentfragment/)）。

### 另请参阅

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
