---
title: evaluate method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 220
url: /python-net/aspose.html.dom/document/evaluate/
is_root: false
---

## evaluate {#str-aspose.html.dom.Node-aspose.html.dom.xpath.IXPathNSResolver-aspose.html.dom.xpath.XPathResultType-any}

Evaluates an XPath expression string and returns a result of the specified type if possible.


### Returns 


The result of the evaluation of the XPath expression.


```python
def evaluate(self, expression, context_node, resolver, type, result):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| expression | str | The XPath expression string to be parsed and evaluated. |
| context_node | [`Node`](/html/python-net/aspose.html.dom/node) | The context is context node for the evaluation of this XPath expression. |
| resolver | aspose.html.dom.xpath.IXPathNSResolver | The resolver permits translation of all prefixes, including the xml<br/>namespace prefix, within the XPath expression into appropriate namespace URIs. |
| type | aspose.html.dom.xpath.XPathResultType | If a specific type is specified, then the result will be returned as the corresponding type. |
| result | any | The result specifies a specific result object which may be reused and returned by this method. |



### See Also
* module [`aspose.html.dom`](../../)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult)
