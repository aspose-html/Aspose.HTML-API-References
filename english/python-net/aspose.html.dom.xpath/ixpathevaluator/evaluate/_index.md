---
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
| context_node | [`Node`](/html/python-net/aspose.html.dom/node) | The `context` is context node for the evaluation of this <br/>XPath expression. If the [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator) was obtained by casting the <br/>[`Document`](/html/python-net/aspose.html.dom/document) then this must be owned by the same document and must be a <br/>[`Document`](/html/python-net/aspose.html.dom/document), [`Element`](/html/python-net/aspose.html.dom/element), [`Attr`](/html/python-net/aspose.html.dom/attr), [`Text`](/html/python-net/aspose.html.dom/text), <br/>[`CDATASection`](/html/python-net/aspose.html.dom/cdatasection), [`Comment`](/html/python-net/aspose.html.dom/comment), [`ProcessingInstruction`](/html/python-net/aspose.html.dom/processinginstruction), <br/>or XPathNamespace node. If the context node is a [`Text`](/html/python-net/aspose.html.dom/text) or a <br/>[`CDATASection`](/html/python-net/aspose.html.dom/cdatasection), then the context is interpreted as the whole logical text node <br/>as seen by XPath, unless the node is empty in which case it may not serve as the XPath context. |
| resolver | [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver) | The `resolver` permits translation of all prefixes, including <br/>the `xml` namespace prefix, within the XPath expression into appropriate namespace URIs. <br/>If this is specified as `null`, any namespace prefix within the expression will result <br/>in [`DOMException`](/html/python-net/aspose.html.dom/domexception) being thrown with the code `NAMESPACE_ERR`. |
| type | [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype) | If a specific `type` is specified, then the result will be returned as <br/>the corresponding type. For XPath 1.0 results, this must be one of the values of the <br/>[`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype) enum. |
| result | any | The `result` specifies a specific result object which may be reused <br/>and returned by this method. If this is specified as `null` or the implementation does not <br/>reuse the specified result, a new result object will be constructed and returned. For XPath 1.0 <br/>results, this object will be of type [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult). |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according <br/>to the rules of the [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | TYPE_ERR: Raised if the result cannot be converted to return the <br/>specified type. |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NAMESPACE_ERR: Raised if the expression contains namespace prefixes <br/>which cannot be resolved by the specified [`IXPathNSResolver`](/html/python-net/aspose.html.dom.xpath/ixpathnsresolver). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported <br/>by this [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context <br/>node or the request type is not permitted by this [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator). |





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
