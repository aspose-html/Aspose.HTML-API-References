---
title: "IXPathNSResolver 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.xpath.IXPathNSResolver 接口。XPathNSResolver 接口允许表达式中的前缀字符串正确绑定到 packageURI 字符串。IXPathEvaluator 可以从节点构建 IXPathNSResolver 的实现，或者任何应用程序都可以实现该接口。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

`XPathNSResolver` 接口允许表达式中的 `prefix` 字符串正确绑定到 `packageURI` 字符串。[`IXPathEvaluator`](../ixpathevaluator/) 可以从节点构建 `IXPathNSResolver` 的实现，或者任何应用程序都可以实现该接口。

```java
public interface IXPathNSResolver
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | 查找与给定包前缀关联的 package URI。XPath 求值器绝不能使用 `null` 或空参数调用此方法，因为其结果未定义。 |

### 另请参阅

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
