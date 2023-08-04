---
title: Document.Evaluate
second_title: Aspose.HTML for Java API Reference
description: Document method. Evaluates an XPath expression String and returns a result of the specified type if possible
type: docs
weight: 950
url: /java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Evaluates an XPath expression String and returns a result of the specified type if possible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression String to be parsed and evaluated. |
| contextNode | Node | The context is context node for the evaluation of this XPath expression. |
| resolver | IXPathNSResolver | The resolver permits translation of all prefixes, including the xml package prefix, within the XPath expression into appropriate package URIs. |
| type | XPathResultType | If a specific type is specified, then the result will be returned as the corresponding type. |
| result | Object | The result specifies a specific result object which may be reused and returned by this method. |

### Return Value

The result of the evaluation of the XPath expression.

### See Also

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.Dom](../../document/)
* package [Aspose.HTML](../../../)
