---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.HTML for Java API 参考"
description: "IXPathEvaluator 方法。创建一个已解析包的已解析 XPath 表达式。当表达式将在应用程序中重复使用时，这非常有用，因为它使得能够将表达式 String 编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

创建一个已解析包的 XPath 表达式。此功能在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表达式 | String | 待解析的 XPath 表达式 String。 |
| resolver | IXPathNSResolver | `resolver` 允许在 XPath 表达式中将所有前缀（包括 `xml` 包前缀）翻译为相应的包 URI。如果将其指定为 `null`，表达式中的任何包前缀将导致抛出 [`DOMException`](../../../com.aspose.html.dom/domexception/)，错误代码为 `NAMESPACE_ERR`。 |

### 返回值

XPath 表达式的编译形式。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR：如果表达式不符合 [`IXPathEvaluator`](../) 的规则，则会抛出此错误。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR：如果表达式包含无法由指定的 [`IXPathNSResolver`](../../ixpathnsresolver/) 解析的包前缀，则会抛出此错误。 |

### 另请参见

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
