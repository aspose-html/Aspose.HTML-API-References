﻿---
title: evaluate method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
is_root: false
---

## evaluate {#str-aspose.html.dom.Node-aspose.html.dom.xpath.IXPathNSResolver-aspose.html.dom.xpath.XPathResultType-any}

Evaluates an XPath expression string and returns a result of the specified type if possible.


### Returns 


The result of the evaluation of the XPath expression. For XPath 1.0 results, this object 
will be of type [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult).


```python
def evaluate(self, expression, context_node, resolver, type, result):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| expression | str | The XPath expression string to be parsed and evaluated. |
| context_node | [`Node`](/html/python-net/aspose.html.dom/node) | The `context` is context node for the evaluation of this 
| resolver | [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver) | The `resolver` permits translation of all prefixes, including 
| type | [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype) | If a specific `type` is specified, then the result will be returned as 
| result | any | The `result` specifies a specific result object which may be reused 
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according 
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | TYPE_ERR: Raised if the result cannot be converted to return the 
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NAMESPACE_ERR: Raised if the expression contains namespace prefixes 
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported 
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context 





### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`Attr`](/html/python-net/aspose.html.dom/attr)
* class [`CDATASection`](/html/python-net/aspose.html.dom/cdatasection)
* class [`Comment`](/html/python-net/aspose.html.dom/comment)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator)
* class [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver)
* class [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult)
* class [`ProcessingInstruction`](/html/python-net/aspose.html.dom/processinginstruction)
* class [`Text`](/html/python-net/aspose.html.dom/text)
* class [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype)