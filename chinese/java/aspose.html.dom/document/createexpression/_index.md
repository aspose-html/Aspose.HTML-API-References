---
title: "Document.CreateExpression"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。创建一个已解析包的 XPath 表达式。此功能在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。"
type: docs

url: /zh/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

创建一个已解析包的 XPath 表达式。此功能在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表达式 | String | 待解析的 XPath 表达式 String。 |
| resolver | IXPathNSResolver | `resolver` 允许在 XPath 表达式中将所有前缀（包括 `xml` 包前缀）转换为相应的包 URI。如果将其指定为 `null`，表达式中的任何包前缀将导致抛出 [`DOMException`](../../domexception/) 并带有代码 `NAMESPACE_ERR`。 |

### 返回值

XPath 表达式的编译形式。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR：如果表达式不符合 [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/) 的规则，则会抛出此错误。 |
| [dOMException](../../domexception/) | NAMESPACE_ERR：如果表达式包含指定的 [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) 无法解析的包前缀，则会抛出此错误。 |

### 另请参见

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
