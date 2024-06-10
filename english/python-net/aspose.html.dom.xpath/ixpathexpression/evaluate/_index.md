---
title: evaluate method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /python-net/aspose.html.dom.xpath/ixpathexpression/evaluate/
is_root: false
---

## evaluate {#aspose.html.dom.Node-aspose.html.dom.xpath.XPathResultType-any}

Evaluates this XPath expression and returns a result.


### Returns 


The result of the evaluation of the XPath expression. For XPath 1.0 results, this object will be 
of type [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult).


```python
def evaluate(self, context_node, type, result):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| context_node | [`Node`](/html/python-net/aspose.html.dom/node) | The `context` is context node for the evaluation of this XPath expression. <br/>If the [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator) was obtained by casting the [`Document`](/html/python-net/aspose.html.dom/document) then this must be <br/>owned by the same document and must be a [`Document`](/html/python-net/aspose.html.dom/document), [`Element`](/html/python-net/aspose.html.dom/element), [`Attr`](/html/python-net/aspose.html.dom/attr), <br/>[`Text`](/html/python-net/aspose.html.dom/text), [`CDATASection`](/html/python-net/aspose.html.dom/cdatasection), [`Comment`](/html/python-net/aspose.html.dom/comment), [`ProcessingInstruction`](/html/python-net/aspose.html.dom/processinginstruction), <br/>or XPathNamespace node. If the context node is a [`Text`](/html/python-net/aspose.html.dom/text) or a [`CDATASection`](/html/python-net/aspose.html.dom/cdatasection), <br/>then the context is interpreted as the whole logical text node as seen by XPath, unless the node is empty <br/>in which case it may not serve as the XPath context. |
| type | [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype) | If a specific `type` is specified, then the result will be coerced to return the <br/>specified type relying on XPath conversions and fail if the desired coercion is not possible. This must <br/>be one of the values of [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype). |
| result | any | The `result` specifies a specific result object which may be reused and returned <br/>by this method. If this is specified as `null` or the implementation does not reuse the specified <br/>result, a new result object will be constructed and returned. For XPath 1.0 results, this object will be <br/>of type [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult). |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | TYPE_ERR: Raised if the result cannot be converted to return the specified type. |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported by <br/>the [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator) that created this [`IXPathExpression`](/html/python-net/aspose.html.dom.xpath/ixpathexpression). |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context node <br/>or the request type is not permitted by this [`IXPathExpression`](/html/python-net/aspose.html.dom.xpath/ixpathexpression). |





### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`Attr`](/html/python-net/aspose.html.dom/attr)
* class [`CDATASection`](/html/python-net/aspose.html.dom/cdatasection)
* class [`Comment`](/html/python-net/aspose.html.dom/comment)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`Element`](/html/python-net/aspose.html.dom/element)
* class [`IXPathEvaluator`](/html/python-net/aspose.html.dom.xpath/ixpathevaluator)
* class [`IXPathExpression`](/html/python-net/aspose.html.dom.xpath/ixpathexpression)
* class [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult)
* class [`ProcessingInstruction`](/html/python-net/aspose.html.dom/processinginstruction)
* class [`Text`](/html/python-net/aspose.html.dom/text)
* class [`XPathResultType`](/html/python-net/aspose.html.dom.xpath/xpathresulttype)
