---
title: "Node.IsEqualNode"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。isEqualNode 方法（属于 Node 接口）用于测试两个节点是否相等。两个节点相等的条件是它们具有相同的类型、定义特征（对于元素而言，这包括它们的 ID、子节点数量等），属性匹配，等等。必须匹配的具体数据点集合取决于节点的类型。"
type: docs

url: /zh/java/com.aspose.html.dom/node/isequalnode/
---
## Node.IsEqualNode method

[`Node`](../) 接口的 isEqualNode() 方法用于测试两个节点是否相等。两个节点相等的条件是它们具有相同的类型、定义特征（对于元素而言，这包括它们的 ID、子节点数量等），属性匹配，等等。必须匹配的具体数据点集合取决于节点的类型。

```java
public bool IsEqualNode(Node otherNode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| otherNode | Node | 用于比较相等性的 [`Node`](../)。 |

### 返回值

如果两个节点相等则为 true，否则为 false 的布尔值。如果 otherNode 为 null，isEqualNode() 总是返回 false。

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
