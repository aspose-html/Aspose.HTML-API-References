---
title: Evaluate
second_title: Aspose.HTML for .NET API 参考
description: 计算此 XPath 表达式并返回结果
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
| contextNode | Node | ` context` 是用于评估的上下文节点这个 XPath 表达式。 如果[`IXPathEvaluator`](../../ixpathevaluator)是通过转换[`Document`](../../../aspose.html.dom/document)获得的那么这必须是 由同一文档拥有，并且必须是[`Document`](../../../aspose.html.dom/document),[`Element`](../../../aspose.html.dom/element),[`Attr`](../../../aspose.html.dom/attr), [`Text`](../../../aspose.html.dom/text),[`CDATASection`](../../../aspose.html.dom/cdatasection),[`Comment`](../../../aspose.html.dom/comment),[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction), 或XPathNamespace节点。如果上下文节点是[`Text`](../../../aspose.html.dom/text)或[`CDATASection`](../../../aspose.html.dom/cdatasection), 然后上下文被解释为 XPath 所看到的整个逻辑文本节点，除非该节点为空 在这种情况下它可能不能用作 XPath 上下文。 |
| type | XPathResultType | 如果指定了特定的` 类型` ，则结果将被强制返回 指定类型依赖于 XPath 转换，如果无法实现所需的强制转换，则会失败。这必须 是[`XPathResultType`](../../xpathresulttype)的值之一。 |
| result | Object | ` 结果` 指定一个特定的结果对象，它可以被重用和返回 通过这种方法。如果这被指定为` null` 或实现不重用指定的 结果，将构造并返回一个新的结果对象。对于 XPath 1.0 结果，该对象将是 类型的[`IXPathResult`](../../ixpathresult)。 |

### 返回值

XPath 表达式的计算结果。对于 XPath 1.0 结果，该对象将是 类型的[`IXPathResult`](../../ixpathresult)。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | TYPE_ERR:如果结果无法转换为返回指定类型则引发。 |
| [DOMException](../../../aspose.html.dom/domexception) | WRONG_DOCUMENT_ERR:节点来自 :::不支持的文档R5:T:Aspose.Html.Dom.XPath.IXPathEvaluator:::创建了这个[`IXPathExpression`](../../ixpathexpression)。 |
| [DOMException](../../../aspose.html.dom/domexception) | NOT_SUPPORTED_ERR:该节点不是允许作为 XPath 上下文节点 或请求的类型此[`IXPathExpression`](../../ixpathexpression)不允许类型。 |

### 也可以看看

* interface [IXPathResult](../../ixpathresult)
* class [Node](../../../aspose.html.dom/node)
* enum [XPathResultType](../../xpathresulttype)
* interface [IXPathExpression](../../ixpathexpression)
* 命名空间 [Aspose.Html.Dom.XPath](../../ixpathexpression)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->