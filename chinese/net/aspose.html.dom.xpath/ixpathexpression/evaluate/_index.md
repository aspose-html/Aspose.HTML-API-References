---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML for .NET API 参考
description: IXPathExpression 方法. 计算此 XPath 表达式并返回结果
type: docs
weight: 10
url: /zh/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

计算此 XPath 表达式并返回结果。

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| contextNode | Node | 这`语境`是用于计算此 XPath 表达式的上下文节点。 如果[`IXPathEvaluator`](../../ixpathevaluator/)是通过铸造获得的[`Document`](../../../aspose.html.dom/document/)那么这必须是同一文档所拥有的 并且必须是[`Document`](../../../aspose.html.dom/document/),[`Element`](../../../aspose.html.dom/element/),[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/),[`CDATASection`](../../../aspose.html.dom/cdatasection/),[`Comment`](../../../aspose.html.dom/comment/),[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , 或XPathNamespace节点。如果上下文节点是[`Text`](../../../aspose.html.dom/text/)或[`CDATASection`](../../../aspose.html.dom/cdatasection/) 然后上下文被解释为 XPath 所见的整个逻辑文本节点，除非节点为空 在这种情况下它可能不作为 XPath 上下文。 |
| type | XPathResultType | 如果一个特定的`类型`被指定，则结果将被强制返回依赖于 XPath 转换的 指定类型，如果无法进行所需的强制转换，则结果将失败。这必须是 的值之一[`XPathResultType`](../../xpathresulttype/). |
| result | Object | 这`结果`指定一个特定的结果对象，该对象可以被此方法重用并返回 。如果指定为`无效的`或者实现不重用指定的 结果，将构造并返回一个新的结果对象。对于 XPath 1.0 结果，此对象将是 类型[`IXPathResult`](../../ixpathresult/). |

### 返回值

XPath 表达式的计算结果。对于 XPath 1.0 结果，此对象将是 类型[`IXPathResult`](../../ixpathresult/).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR：如果无法将结果转换为返回指定类型，则引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR：节点来自 不支持的文档[`IXPathEvaluator`](../../ixpathevaluator/)创造了这个[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：该节点不是允许作为 XPath 上下文节点 的类型，或者该节点不允许请求类型[`IXPathExpression`](../). |

### 也可以看看

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* 命名空间 [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* 部件 [Aspose.HTML](../../../)


