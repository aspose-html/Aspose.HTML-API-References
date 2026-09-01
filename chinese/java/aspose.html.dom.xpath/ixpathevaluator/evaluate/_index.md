---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML for Java API 参考"
description: "IXPathEvaluator 方法。评估一个 XPath 表达式 String，并在可能的情况下返回指定类型的结果。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

求值一个 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表达式 | String | 待解析和评估的 XPath 表达式 String。 |
| contextNode | Node | `context` 是用于评估此 XPath 表达式的上下文节点。如果通过将 [`Document`](../../../com.aspose.html.dom/document/) 强制转换获得了 [`IXPathEvaluator`](../)，则该节点必须属于同一文档，并且必须是 [`Document`](../../../com.aspose.html.dom/document/)、[`Element`](../../../com.aspose.html.dom/element/)、[`Attr`](../../../com.aspose.html.dom/attr/)、[`Text`](../../../com.aspose.html.dom/text/)、[`CDATASection`](../../../com.aspose.html.dom/cdatasection/)、[`Comment`](../../../com.aspose.html.dom/comment/)、[`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) 或 XPathNamespace 节点。如果上下文节点是 [`Text`](../../../com.aspose.html.dom/text/) 或 [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)，则上下文被解释为 XPath 所看到的整个逻辑文本节点，除非该节点为空，此时它可能无法作为 XPath 上下文。 |
| resolver | IXPathNSResolver | `resolver` 允许在 XPath 表达式中将所有前缀（包括 `xml` 包前缀）翻译为相应的包 URI。如果将其指定为 `null`，表达式中的任何包前缀将导致抛出 [`DOMException`](../../../com.aspose.html.dom/domexception/)，错误代码为 `NAMESPACE_ERR`。 |
| type | XPathResultType | 如果指定了特定的 `type`，则结果将以相应的类型返回。对于 XPath 1.0 的结果，这必须是 [`XPathResultType`](../../xpathresulttype/) 枚举中的某个值。 |
| result | Object | `result` 指定一个特定的结果对象，该对象可以被此方法复用并返回。如果将其指定为 `null`，或实现未复用指定的结果，则会构造并返回一个新的结果对象。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。 |

### 返回值

XPath 表达式求值的结果。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR：如果表达式不符合 [`IXPathEvaluator`](../) 的规则，则会抛出此错误。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR：如果结果无法转换为指定的类型则抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR：如果表达式包含无法由指定的 [`IXPathNSResolver`](../../ixpathnsresolver/) 解析的包前缀，则会抛出此错误。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR：该节点来自一个不被此 [`IXPathEvaluator`](../) 支持的文档。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：该节点不是允许作为 XPath 上下文节点的类型，或请求的类型不被此 [`IXPathEvaluator`](../) 支持。 |

### 另请参见

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
