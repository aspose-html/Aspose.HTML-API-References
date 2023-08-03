---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML for Java API Reference
description: IXPathEvaluator method. Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression
type: docs
weight: 10
url: /net/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Creates a parsed XPath expression with resolved packages. This is useful when an expression will be reused in an application since it makes it possible to compile the expression String into a more efficient internal form and preresolve all package prefixes which occur within the expression.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Type | Description |
| --- | --- | --- |
| expression | String | The XPath expression String to be parsed. |
| resolver | IXPathNSResolver | The `resolver` permits translation of all prefixes, including the `xml` package prefix, within the XPath expression into appropriate package URIs. If this is specified as `null`, any package prefix within the expression will result in [`DOMException`](../../../com.aspose.html.dom/domexception/) being thrown with the code `NAMESPACE_ERR`. |

### Return Value

The compiled form of the XPath expression.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Raised if the expression is not legal according to the rules of the [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Raised if the expression contains package prefixes which cannot be resolved by the specified [`IXPathNSResolver`](../../ixpathnsresolver/). |

### See Also

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.Dom.XPath](../../ixpathevaluator/)
* package [Aspose.HTML](../../../)
