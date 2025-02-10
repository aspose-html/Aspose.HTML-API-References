---
title: Document.CreateExpression
second_title: Aspose.HTML for Java API Reference
description: Document method. Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression
type: docs
weight: 890
url: /java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression String to be parsed. |
| resolver | IXPathNSResolver | The `resolver` permits translation of all prefixes, including the `xml` package prefix, within the XPath expression into appropriate package URIs. If this is specified as `null`, any package prefix within the expression will result in [`DOMException`](../../domexception/) being thrown with the code `NAMESPACE_ERR`. |

### Return Value

The compiled form of the XPath expression.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according to the rules of the [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Raised if the expression contains package prefixes which cannot be resolved by the specified [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/). |

### See Also

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
