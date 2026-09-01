---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML for Java API 参考"
description: "INodeIterator 方法。返回集合中的下一个节点，并将迭代器在集合中的位置前移。创建 NodeIterator 后，第一次调用 nextNode 将返回集合中的第一个节点。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

返回集合中的下一个节点并将迭代器在集合中的位置前移。创建 NodeIterator 后，第一次调用 nextNode() 将返回集合中的第一个节点。

```java
public Node NextNode()
```

### 返回值

正在迭代的集合中的下一个节点，如果该集合中没有更多成员，则为 null。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR：如果在调用 detach 方法后调用此方法，则会抛出此错误。 |

### 另请参见

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
