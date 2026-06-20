---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML for Java API 参考"
description: "ITreeWalker 属性。TreeWalker 当前所在的节点。对 DOM 树的更改可能导致当前节点不再被 TreeWalker 关联的过滤器接受。currentNode 也可以显式设置为任意节点，无论该节点是否在根节点指定的子树内，或是否会被过滤器和 whatToShow 标志接受。即使当前节点不在当前视图中，进一步的遍历仍相对于 currentNode 进行，通过在请求的方向上应用过滤器；如果无法进行遍历，currentNode 将保持不变。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

TreeWalker 当前所在的节点。对 DOM 树的更改可能导致当前节点不再被 TreeWalker 关联的过滤器接受。currentNode 也可以显式设置为任意节点，无论该节点是否在根节点指定的子树内，或是否会被过滤器和 whatToShow 标志接受。即使当前节点不在当前视图中，进一步的遍历仍相对于 currentNode 进行，通过在请求的方向上应用过滤器；如果无法进行遍历，currentNode 将保持不变。

```java
public Node CurrentNode { get; set; }
```

### Property Value

当前节点。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：如果尝试将 currentNode 设置为 null，则会抛出此错误。 |

### 另请参见

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
