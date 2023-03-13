---
title: Interface IXPathEvaluator
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.XPath.IXPathEvaluator 界面. XPath 表达式的计算由IXPathEvaluator.
type: docs
weight: 2560
url: /zh/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 表达式的计算由`IXPathEvaluator`.

```csharp
public interface IXPathEvaluator
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | 使用已解析的命名空间创建已解析的 XPath 表达式。当表达式将在应用程序中重用时，这很有用 ，因为它可以 将表达式字符串编译为更有效的内部形式，并 预解析表达式中出现的所有名称空间前缀。 |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | 调整任何 DOM 节点以解析名称空间，以便可以相对于它在文档中出现的节点的上下文轻松地评估 XPath 表达式 。这个适配器像 DOM Level 3 方法一样工作 `查找命名空间URI`在调用 time lookupNamespaceURI 时使用节点层次结构中可用的当前信息从给定前缀解析 namespaceURI 的节点上，还正确解析隐式 xml 前缀. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | 计算 XPath 表达式字符串并在可能的情况下返回指定类型的结果。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 部件 [Aspose.HTML](../../)


