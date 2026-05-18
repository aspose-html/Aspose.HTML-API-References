---
title: "Node.RemoveChild"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。Node 接口的 removeChild 方法从 DOM 中移除子节点并返回被移除的节点。"
type: docs

url: /zh/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Node 接口的 removeChild() 方法从 DOM 中移除子节点并返回被移除的节点。

注意：只要对被移除的子节点保持引用，它仍然存在于内存中，但不再是 DOM 的一部分。它仍可在代码中稍后重新使用。如果不保存 removeChild() 的返回值，也没有其他引用，它将在短时间后自动从内存中删除。

```java
public Node RemoveChild(Node child)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| child | Node | 一个 [`Node`](../) ，即将从 DOM 中移除的子节点。 |

### 返回值

不同于 [`Node.cloneNode()`](../clonenode/)，返回值会保留与之关联的 [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) 对象。

### 另请参阅

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
