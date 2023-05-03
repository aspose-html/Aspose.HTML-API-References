---
title: IXPathNSResolver Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.XPath.IXPathNSResolver interface. The XPathNSResolver interface permit prefix strings in the expression to be properly bound to namespaceURI strings. IXPathEvaluator can construct an implementation of IXPathNSResolver from a node or the interface may be implemented by any application
type: docs
weight: 2590
url: /net/aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

The `XPathNSResolver` interface permit `prefix` strings in the expression to be properly bound to `namespaceURI` strings. [`IXPathEvaluator`](../ixpathevaluator/) can construct an implementation of `IXPathNSResolver` from a node, or the interface may be implemented by any application.

```csharp
public interface IXPathNSResolver
```

## Methods

| Name | Description |
| --- | --- |
| [LookupNamespaceURI](../../aspose.html.dom.xpath/ixpathnsresolver/lookupnamespaceuri/)(string) | Look up the namespace URI associated to the given namespace prefix. The XPath evaluator must never call this with a `null` or empty argument, because the result of doing this is undefined. |

### See Also

* namespace [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../)
