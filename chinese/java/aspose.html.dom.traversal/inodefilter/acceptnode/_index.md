---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.HTML for Java API 参考"
description: "INodeFilter 方法。测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用，通常不会直接从用户代码调用。若需要，也可以自行调用以在应用逻辑中使用相同的过滤器。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用；通常不会直接从用户代码中调用。（如果您想使用相同的过滤器来指导自己的应用逻辑，也可以这样做。）

```java
public short AcceptNode(Node n)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| n | Node | 要检查的节点，以确定它是否通过过滤器。 |

### 返回值

一个常量，用于确定节点是被接受、被拒绝还是被跳过，如上所定义。

### 另请参阅

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
