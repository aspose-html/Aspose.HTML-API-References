---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML for .NET API Reference
description: IXPathEvaluator Evaluate method. Evaluates an XPath expression string and returns a result of the specified type if possible
type: docs
weight: 30
url: /net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evaluates an XPath expression string and returns a result of the specified type if possible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression string to be parsed and evaluated. |
| contextNode | Node | The `context` is context node for the evaluation of this XPath expression. If the [`IXPathEvaluator`](../) was obtained by casting the [`Document`](../../../aspose.html.dom/document/) then this must be owned by the same document and must be a [`Document`](../../../aspose.html.dom/document/), [`Element`](../../../aspose.html.dom/element/), [`Attr`](../../../aspose.html.dom/attr/), [`Text`](../../../aspose.html.dom/text/), [`CDATASection`](../../../aspose.html.dom/cdatasection/), [`Comment`](../../../aspose.html.dom/comment/), [`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/), or XPathNamespace node. If the context node is a [`Text`](../../../aspose.html.dom/text/) or a [`CDATASection`](../../../aspose.html.dom/cdatasection/), then the context is interpreted as the whole logical text node as seen by XPath, unless the node is empty in which case it may not serve as the XPath context. |
| resolver | IXPathNSResolver | The `resolver` permits translation of all prefixes, including the `xml` namespace prefix, within the XPath expression into appropriate namespace URIs. If this is specified as `null`, any namespace prefix within the expression will result in [`DOMException`](../../../aspose.html.dom/domexception/) being thrown with the code `NAMESPACE_ERR`. |
| type | XPathResultType | If a specific `type` is specified, then the result will be returned as the corresponding type. For XPath 1.0 results, this must be one of the values of the [`XPathResultType`](../../xpathresulttype/) enum. |
| result | Object | The `result` specifies a specific result object which may be reused and returned by this method. If this is specified as `null` or the implementation does not reuse the specified result, a new result object will be constructed and returned. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/). |

### Return Value

The result of the evaluation of the XPath expression. For XPath 1.0 results, this object will be of type [`IXPathResult`](../../ixpathresult/).

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according to the rules of the [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Raised if the result cannot be converted to return the specified type. |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Raised if the expression contains namespace prefixes which cannot be resolved by the specified [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: The Node is from a document that is not supported by this [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: The Node is not a type permitted as an XPath context node or the request type is not permitted by this [`IXPathEvaluator`](../). |

### See Also

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namespace [Aspose.Html.Dom.XPath](../../../aspose.html.dom.xpath/)
* assembly [Aspose.HTML](../../../)
