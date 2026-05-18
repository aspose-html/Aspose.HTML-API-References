---
title: "IXPathEvaluator 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.xpath.IXPathEvaluator 接口。XPath 表达式的求值由 IXPathEvaluator 提供。"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

XPath 表达式的求值由 `IXPathEvaluator` 提供。

```java
public interface IXPathEvaluator
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | 创建一个已解析包的 XPath 表达式。此功能在表达式将在应用程序中重复使用时很有用，因为它可以将表达式字符串编译为更高效的内部形式，并预先解析表达式中出现的所有包前缀。 |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | 适配任意 DOM 节点以解析包，使得 XPath 表达式能够相对于其在文档中出现的节点上下文轻松求值。此适配器的工作方式类似于 DOM Level 3 方法 `lookupNamespaceURI`，在解析给定前缀的 packageURI 时使用节点层次结构中当前可用的信息，并正确解析隐式的 xml 前缀。 |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | 求值 XPath 表达式字符串，并在可能的情况下返回指定类型的结果。 |

### 另请参阅

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
