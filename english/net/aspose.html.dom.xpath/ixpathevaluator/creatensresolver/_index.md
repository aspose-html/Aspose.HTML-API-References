---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.HTML for .NET API Reference
description: IXPathEvaluator method. Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method lookupNamespaceURI on nodes in resolving the namespaceURI from a given prefix using the current information available in the nodes hierarchy at the time lookupNamespaceURI is called also correctly resolving the implicit xml prefix
type: docs
weight: 20
url: /net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapts any DOM node to resolve namespaces so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the namespaceURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| nodeResolver | Node | The node to be used as a context for namespace resolution. |

### Return Value

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves namespaces with respect to the definitions in scope for a specified node.

### See Also

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Html.Dom.XPath](../../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../../)
