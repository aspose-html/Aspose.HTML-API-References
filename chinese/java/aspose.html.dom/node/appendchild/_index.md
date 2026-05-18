---
title: "Node.AppendChild"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。Node 接口的 appendChild 方法将在指定父节点的子节点列表末尾添加一个节点。如果给定的子节点是文档中已有节点的引用，appendChild 会将其从当前位置移动到新位置，无需在将其追加到其他节点之前先从其父节点中移除。"
type: docs

url: /zh/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

appendChild() 方法属于 Node 接口，用于将节点添加到指定父节点的子节点列表末尾。如果给定的子节点是文档中已存在的节点，appendChild() 会将其从当前位置移动到新位置（无需在将其追加到其他节点之前先从父节点中移除）。

这意味着一个节点不能同时出现在文档的两个位置。因此，如果节点已经有父节点，首先会将其移除，然后再追加到新位置。可以使用 [`Node.cloneNode()`](../clonenode/) 方法在将节点追加到新父节点之前创建其副本。使用 [`cloneNode`](../clonenode/) 创建的副本不会自动保持同步。

```java
public Node AppendChild(Node node)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | Node | 要追加到给定父节点（通常是元素）的节点。 |

### 返回值

追加的子节点（aChild），除非 aChild 是 [`DocumentFragment`](../../documentfragment/)，在这种情况下返回空的 [`DocumentFragment`](../../documentfragment/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | 当 DOM 树的约束被违反时抛出。 |

### 另请参阅

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
