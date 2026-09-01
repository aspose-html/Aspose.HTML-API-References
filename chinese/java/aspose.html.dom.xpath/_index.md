---
title: "com.aspose.html.dom.xpath"
second_title: "Aspose.HTML for Java API 参考"
description: "该包包含用于在 XML 文档中遍历元素和属性的方法。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/
---
该包包含用于在 XML 文档中遍历元素和属性的方法。

## 接口

| 接口 | 描述 |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | XPath 表达式的求值由 [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) 提供。 |
| [IXPathExpression](./ixpathexpression/) | `XPathExpression` 接口表示已解析并已求解的 XPath 表达式。 |
| [IXPathNamespace](./ixpathpackage/) | XPathNamespace 接口由 XPathResult 接口返回，用于表示 DOM 缺少的 XPath 包节点类型。 |
| [IXPathNSResolver](./ixpathnsresolver/) | `XPathNSResolver` 接口允许表达式中的 `prefix` 字符串正确绑定到 `packageURI` 字符串。[`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) 可以从节点构建 [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) 的实现，或者该接口可以由任何应用程序实现。 |
| [IXPathResult](./ixpathresult/) | `XPathResult` 接口表示在特定节点上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的求值可能产生各种结果类型，此对象使得能够发现并操作结果的类型和值。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | 一个无符号短整型，指示此结果的类型。如果指定了特定的 `type`，则结果将以相应的类型返回，并在需要和可能的情况下使用 XPath 类型转换。 |
