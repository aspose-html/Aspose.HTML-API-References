---
title: "Node.ParentNode"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 属性。只读的 parentNode 属性（Node 接口）返回 DOM 树中指定节点的父节点。"
type: docs

url: /zh/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

只读的 parentNode 属性（Node 接口）返回 DOM 树中指定节点的父节点。

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

一个 Node，作为当前节点的父节点。元素的父节点可以是 [`Element`](../../element/) 节点、[`Document`](../../document/) 节点或 [`DocumentFragment`](../../documentfragment/) 节点。

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
