---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML for Java API 参考"
description: "IXPathExpression 方法。评估此 XPath 表达式并返回结果"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

评估此 XPath 表达式并返回结果。

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| contextNode | Node | `context` 是用于评估此 XPath 表达式的上下文节点。如果通过将 [`IXPathEvaluator`](../../ixpathevaluator/) 强制转换自 [`Document`](../../../com.aspose.html.dom/document/) 获得，则该节点必须属于同一文档，并且必须是 [`Document`](../../../com.aspose.html.dom/document/)、[`Element`](../../../com.aspose.html.dom/element/)、[`Attr`](../../../com.aspose.html.dom/attr/)、[`Text`](../../../com.aspose.html.dom/text/)、[`CDATASection`](../../../com.aspose.html.dom/cdatasection/)、[`Comment`](../../../com.aspose.html.dom/comment/)、[`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) 或 XPathNamespace 节点。如果上下文节点是 [`Text`](../../../com.aspose.html.dom/text/) 或 [`CDATASection`](../../../com.aspose.html.dom/cdatasection/)，则上下文被解释为 XPath 所看到的整个逻辑文本节点，除非该节点为空，此时它不能作为 XPath 上下文。 |
| type | XPathResultType | 如果指定了特定的 `type`，则结果将被强制转换为指定的类型，依赖于 XPath 的转换规则；如果无法进行所需的强制转换则会失败。该值必须是 [`XPathResultType`](../../xpathresulttype/) 的一个取值。 |
| result | Object | `result` 指定一个可被此方法复用并返回的结果对象。如果将其指定为 `null`，或实现未复用指定的结果，则会构造并返回一个新的结果对象。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。 |

### 返回值

XPath 表达式求值的结果。对于 XPath 1.0 的结果，该对象的类型为 [`IXPathResult`](../../ixpathresult/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR：如果结果无法转换为指定的类型则抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR：该节点来自一个不被创建此 [`IXPathExpression`](../) 的 [`IXPathEvaluator`](../../ixpathevaluator/) 支持的文档。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：该节点的类型不被允许作为 XPath 上下文节点，或此请求类型不被此 [`IXPathExpression`](../) 支持。 |

### 另请参阅

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
