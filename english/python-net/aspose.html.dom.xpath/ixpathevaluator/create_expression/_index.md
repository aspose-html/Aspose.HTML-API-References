﻿---
title: create_expression method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.dom.xpath/ixpathevaluator/create_expression/
is_root: false
---

## create_expression {#str-aspose.html.dom.xpath.IXPathNSResolver}

Creates a parsed XPath expression with resolved namespaces. This is useful 
when an expression will be reused in an application since it makes it possible 
to compile the expression string into a more efficient internal form and 
preresolve all namespace prefixes which occur within the expression.


### Returns 


The compiled form of the XPath expression.


```python
def create_expression(self, expression, resolver):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| expression | str | The XPath expression string to be parsed. |
| resolver | [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver) | The `resolver` permits translation of all prefixes, 
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INVALID_EXPRESSION_ERR: Raised if the expression is not 
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NAMESPACE_ERR: Raised if the expression contains namespace 





### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator)
* class [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver)