---
title: "Node.ChildNodes"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 属性。只读的 childNodes 属性（Node 接口）返回给定元素的子节点的实时 NodeList，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。"
type: docs

url: /zh/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

只读的 childNodes 属性（Node 接口）返回给定元素的子节点的实时 [`NodeList`](../../../com.aspose.html.collections/nodelist/)，其中第一个子节点的索引为 0。子节点包括元素、文本和注释。

注意：[`NodeList`](../../../com.aspose.html.collections/nodelist/) 为实时的，意味着每次添加或删除子节点时其内容都会改变。

```java
public NodeList ChildNodes { get; }
```

### Property Value

一个实时的 [`NodeList`](../../../com.aspose.html.collections/nodelist/)，包含该节点的子节点。

注意：多次调用 childNodes 会返回相同的 [`NodeList`](../../../com.aspose.html.collections/nodelist/)。

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
