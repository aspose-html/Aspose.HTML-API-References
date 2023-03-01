---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML for .NET API 参考
description: IXPathEvaluator 方法. 计算 XPath 表达式字符串并在可能的情况下返回指定类型的结果
type: docs
weight: 30
url: /zh/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

计算 XPath 表达式字符串并在可能的情况下返回指定类型的结果。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 要分析和评估的 XPath 表达式字符串。 |
| contextNode | Node | 这`语境`是用于计算此 XPath 表达式的上下文节点。如果[`IXPathEvaluator`](../)是通过铸造 获得的[`Document`](../../../aspose.html.dom/document/)那么这必须属于同一个文档并且必须是 [`Document`](../../../aspose.html.dom/document/),[`Element`](../../../aspose.html.dom/element/),[`Attr`](../../../aspose.html.dom/attr/),[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/),[`Comment`](../../../aspose.html.dom/comment/),[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , 或XPathNamespace节点。如果上下文节点是[`Text`](../../../aspose.html.dom/text/)或 [`CDATASection`](../../../aspose.html.dom/cdatasection/)然后上下文被解释为 XPath 所见的整个逻辑文本节点 ，除非该节点为空，在这种情况下它可能不会用作 XPath 上下文。 |
| resolver | IXPathNSResolver | 这`解析器`允许翻译所有前缀，包括 `XML`命名空间前缀，在 XPath 表达式中转换为适当的命名空间 URI。 如果指定为`无效的` 表达式中的任何命名空间前缀都将导致 [`DOMException`](../../../aspose.html.dom/domexception/)被代码抛出`命名空间_错误`. |
| type | XPathResultType | 如果一个特定的`类型`被指定，则返回结果为 对应的类型。对于 XPath 1.0 结果，这必须是 的值之一[`XPathResultType`](../../xpathresulttype/)枚举。 |
| result | Object | 这`结果`指定可重复使用 并由此方法返回的特定结果对象。如果指定为`无效的`或者实现不 重用指定的结果，将构造并返回一个新的结果对象。对于 XPath 1.0 结果，此对象将是类型[`IXPathResult`](../../ixpathresult/). |

### 返回值

XPath 表达式的计算结果。对于 XPath 1.0 结果，此对象 的类型[`IXPathResult`](../../ixpathresult/).

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR：如果表达式根据 的规则不合法则引发[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR：如果结果无法转换为返回 指定类型，则引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR：如果表达式包含命名空间前缀 无法由指定的解析[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR：该节点来自一个不受此支持的文档 [`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR：该节点不是允许作为 XPath 上下文 节点的类型，或者该节点不允许请求类型[`IXPathEvaluator`](../). |

### 也可以看看

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* 命名空间 [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* 部件 [Aspose.HTML](../../../)


