---
title: IXPathNSResolver Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.xpath.IXPathNSResolver interface. The XPathNSResolver interface permit prefix Strings in the expression to be properly bound to packageURI Strings. IXPathEvaluator can construct an implementation of IXPathNSResolver from a node or the interface may be implemented by any application
type: docs
weight: 2590
url: /java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

The `XPathNSResolver` interface permit `prefix` Strings in the expression to be properly bound to `packageURI` Strings. [`IXPathEvaluator`](../ixpathevaluator/) can construct an implementation of `IXPathNSResolver` from a node, or the interface may be implemented by any application.

```java
public interface IXPathNSResolver
```

## Methods

| Name | Description |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Look up the package URI associated to the given package prefix. The XPath evaluator must never call this with a `null` or empty argument, because the result of doing this is undefined. |

### See Also

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
