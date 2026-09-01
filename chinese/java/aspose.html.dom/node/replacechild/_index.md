---
title: "Node.ReplaceChild"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。将子节点 oldChild 替换为 newChild 并返回 oldChild 节点。如果 newChild 是 DocumentFragment 对象，则 oldChild 被该 DocumentFragment 的所有子节点替换，且按相同顺序插入。如果 newChild 已经在树中，则先将其移除。"
type: docs

url: /zh/java/com.aspose.html.dom/node/replacechild/
---
## Node.ReplaceChild method

将子节点 oldChild 替换为 newChild 并返回 oldChild 节点。如果 newChild 是 [`DocumentFragment`](../../documentfragment/) 对象，则 oldChild 被该 [`DocumentFragment`](../../documentfragment/) 的所有子节点替换，且按相同顺序插入。如果 newChild 已经在树中，则先将其移除。

```java
public Node ReplaceChild(Node node, Node child)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 节点 | Node | 用于替换 oldChild 的新节点。 |
| 子节点 | Node | 待替换的子节点。 |

### 返回值

被替换的 Node。它与 oldChild 是同一个节点。

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
