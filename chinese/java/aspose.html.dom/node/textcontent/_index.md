---
title: "Node.TextContent"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 属性。Node 接口的 textContent 属性表示节点及其后代的文本内容"
type: docs

url: /zh/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

[`Node`](../) 接口的 textContent 属性表示节点及其后代的文本内容。

```java
public String TextContent { get; set; }
```

### Property Value

一个字符串，或 null。其值取决于具体情况：

如果节点是文档或文档类型，textContent 返回 null。注意：要获取整个文档的所有文本和 CDATA 数据，请使用 document.documentElement.textContent。如果节点是 CDATA 区段、注释、处理指令或文本节点，textContent 返回或设置节点内部的文本，即 [`Node.nodeValue`](../nodevalue/)。对于其他节点类型，textContent 返回所有子节点的 textContent 的连接，排除注释和处理指令。

## 备注

参考：

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
