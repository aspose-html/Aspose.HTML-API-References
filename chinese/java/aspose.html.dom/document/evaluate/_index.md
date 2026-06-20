---
title: "Document.Evaluate"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。评估 XPath 表达式字符串，并在可能的情况下返回指定类型的结果"
type: docs

url: /zh/java/com.aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

求值一个 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 表达式 | String | 待解析和评估的 XPath 表达式 String。 |
| contextNode | Node | 上下文是用于评估此 XPath 表达式的上下文节点。 |
| resolver | IXPathNSResolver | 解析器允许在 XPath 表达式中将所有前缀（包括 xml 包前缀）转换为相应的包 URI。 |
| 类型 | XPathResultType | 如果指定了特定类型，则结果将以相应的类型返回。 |
| result | 对象 | result 指定一个特定的结果对象，该对象可以被复用并由此方法返回。 |

### 返回值

XPath 表达式评估的结果。

### 另请参见

* interface [IXPathResult](../../../com.aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../com.aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
