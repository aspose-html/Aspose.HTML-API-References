---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。将任意 DOM 节点适配为解析包，以便能够相对于该节点在文档中出现的上下文轻松评估 XPath 表达式。此适配器的工作方式类似于 DOM Level 3 中的 lookupNamespaceURI 方法，在节点上解析给定前缀的 packageURI，使用 lookupNamespaceURI 调用时节点层次结构中可用的当前信息，并且还能正确解析隐式的 xml 前缀"
type: docs

url: /zh/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

适配任意 DOM 节点以解析包，使得 XPath 表达式能够相对于其在文档中出现的节点上下文轻松求值。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在解析给定前缀的 packageURI 时使用节点层次结构中当前可用的信息，并正确解析隐式的 xml 前缀。

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| nodeResolver | Node | 用于包解析的上下文节点。 |

### 返回值

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### 另请参阅

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
