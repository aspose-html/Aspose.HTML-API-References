---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML for Java API Reference
description: IXPathEvaluator method. Evaluates an XPath expression String and returns a result of the specified type if possible
type: docs
weight: 30
url: /java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evaluates an XPath expression String and returns a result of the specified type if possible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression String to be parsed and evaluated. |
| contextNode | Node | The `context` is context node for the evaluation of this XPath expression. If the [`IXPathEvaluator`](../) was obtained by casting the [`Document`](../../../com.aspose.html.dom/document/) then this must be owned by the same document and must be a [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), or XPathNamespace node. If the context node is a [`Text`](../../../com.aspose.html.dom/text/) or a [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), then the context is interpreted as the whole logical text node as seen by XPath, unless the node is empty in which case it may not serve as the XPath context. |
| resolver | IXPathNSResolver | The `resolver` permits translation of all prefixes, including the `xml` package prefix, within the XPath expression into appropriate package URIs. If this is specified as `null`, any package prefix within the expression will result in [`DOMException`](../../../com.aspose.html.dom/domexception/) being thrown with the code `NAMESPACE_ERR`. |
| type | XPathResultType | If a specific `type` is specified, then the result will be returned as the corresponding type. For XPath 1.0 results, this must be one of the values of the [`XPathResultType`](../../xpathresulttype/) enum. |
| result | Object | The `result` specifies a specific result object which may be reused and returned by this method. If this is specified as `null` or the implementation does not reuse the specified result, a new result object will be constructed and returned. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/). |

### Return Value

The result of the evaluation of the XPath expression. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according to the rules of the [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Raised if the result cannot be converted to return the specified type. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Raised if the expression contains package prefixes which cannot be resolved by the specified [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported by this [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context node or the request type is not permitted by this [`IXPathEvaluator`](../). |

### See Also

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
