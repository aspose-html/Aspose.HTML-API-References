---
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
| resolver | [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver) | The `resolver` permits translation of all prefixes, <br/>including the `xml` namespace prefix, within the XPath expression into <br/>appropriate namespace URIs. If this is specified as `null`, any namespace <br/>prefix within the expression will result in [`DOMException`](/html/python-net/aspose.html.dom/domexception) being <br/>thrown with the code `NAMESPACE_ERR`. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INVALID_EXPRESSION_ERR: Raised if the expression is not <br/>legal according to the rules of the [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NAMESPACE_ERR: Raised if the expression contains namespace <br/>prefixes which cannot be resolved by the specified [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver). |





### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator)
* class [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver)
