---
title: Evaluate
second_title: Aspose.HTML for .NET API 参考
description: 计算一个 XPath 表达式字符串如果可能返回指定类型的结果
type: docs
weight: 950
url: /zh/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

计算一个 XPath 表达式字符串，如果可能，返回指定类型的结果。

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| expression | String | 要解析和评估的 XPath 表达式字符串。 |
| contextNode | Node | 上下文是评估此 XPath 表达式的上下文节点。 |
| resolver | IXPathNSResolver | 解析器允许将 XPath 表达式中的所有前缀（包括 xml 命名空间前缀）翻译成适当的命名空间 URI。 |
| type | XPathResultType | 如果指定了特定类型，则结果将作为相应类型返回。 |
| result | Object | 结果指定了一个特定的结果对象，该对象可以被此方法重用和返回。 |

### 返回值

XPath 表达式的计算结果。

### 也可以看看

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult)
* class [Node](../../node)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype)
* class [Document](../../document)
* 命名空间 [Aspose.Html.Dom](../../document)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->