---
title: IXPathNSResolver class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.dom.xpath/ixpathnsresolver/
is_root: false
---

## IXPathNSResolver class

The `XPathNSResolver` interface permit `prefix` strings in 
the expression to be properly bound to `namespaceURI` strings. 
[`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator) can construct an implementation of 
[`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver) from a node, or the interface may be 
implemented by any application.



The IXPathNSResolver type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [lookup_namespace_uri](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver/lookup_namespace_uri/#str) | Look up the namespace URI associated to the given namespace prefix. <br/>The XPath evaluator must never call this with a `null` or empty <br/>argument, because the result of doing this is undefined. |



### See Also
* module [`aspose.html.dom.xpath`](..)
* class [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator)
* class [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver)
