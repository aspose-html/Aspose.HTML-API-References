---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML for Java API Reference
description: IXPathExpression method. Evaluates this XPath expression and returns a result
type: docs
weight: 10
url: /java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evaluates this XPath expression and returns a result.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| contextNode | Node | The `context` is context node for the evaluation of this XPath expression. If the [`IXPathEvaluator`](../../ixpathevaluator/) was obtained by casting the [`Document`](../../../com.aspose.html.dom/document/) then this must be owned by the same document and must be a [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), or XPathNamespace node. If the context node is a [`Text`](../../../com.aspose.html.dom/text/) or a [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), then the context is interpreted as the whole logical text node as seen by XPath, unless the node is empty in which case it may not serve as the XPath context. |
| type | XPathResultType | If a specific `type` is specified, then the result will be coerced to return the specified type relying on XPath conversions and fail if the desired coercion is not possible. This must be one of the values of [`XPathResultType`](../../xpathresulttype/). |
| result | Object | The `result` specifies a specific result object which may be reused and returned by this method. If this is specified as `null` or the implementation does not reuse the specified result, a new result object will be constructed and returned. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/). |

### Return Value

The result of the evaluation of the XPath expression. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Raised if the result cannot be converted to return the specified type. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported by the [`IXPathEvaluator`](../../ixpathevaluator/) that created this [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context node or the request type is not permitted by this [`IXPathExpression`](../). |

### See Also

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.Dom.XPath](../../ixpathexpression/)
* package [Aspose.HTML](../../../)
