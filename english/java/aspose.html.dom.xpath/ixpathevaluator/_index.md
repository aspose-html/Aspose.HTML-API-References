---
title: IXPathEvaluator Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.XPath.IXPathEvaluator interface. The evaluation of XPath expressions is provided by IXPathEvaluator
type: docs
weight: 2570
url: /net/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

The evaluation of XPath expressions is provided by `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Methods

| Name | Description |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adapts any DOM node to resolve packages so that an XPath expression can be easily evaluated relative to the context of the node where it appeared within the document. This adapter works like the DOM Level 3 method `lookupNamespaceURI` on nodes in resolving the packageURI from a given prefix using the current information available in the node's hierarchy at the time lookupNamespaceURI is called, also correctly resolving the implicit xml prefix. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evaluates an XPath expression String and returns a result of the specified type if possible. |

### See Also

* package [com.aspose.html.Dom.XPath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
