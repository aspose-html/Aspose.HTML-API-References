---
title: Document.CreateNSResolver
second_title: Aspose.HTML for Java API Reference
description: Document method. Adapts any DOM node to resolve packages so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method lookupNamespaceURI on nodes in resolving the packageURI from a given prefix using the current information available in the nodes hierarchy at the time lookupNamespaceURI is called also correctly resolving the implicit xml prefix
type: docs
weight: 910
url: /net/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Adapts any DOM node to resolve packages so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the packageURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| nodeResolver | Node | The node to be used as a context for package resolution. |

### Return Value

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### See Also

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)
