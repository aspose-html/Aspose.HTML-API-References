---
title: "IXPathResult 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.xpath.IXPathResult 接口。XPathResult 接口表示在特定节点上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的求值可能产生各种结果类型，此对象使得能够发现和操作结果的类型和值"
type: docs

url: /zh/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

`XPathResult` 接口表示在特定节点上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的求值可能产生各种结果类型，此对象使得能够发现并操作结果的类型和值。

```java
public interface IXPathResult
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) 此布尔结果的值。 |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) 表示迭代器已失效。如果 `resultType` 是 `UnorderedNodeIterator` 类型或 `OrderedNodeIterator` 类型且文档在返回此结果后已被修改，则为 true。 |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) 此数字结果的值。 |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) 表示此结果类型的代码，定义于 http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) 枚举。 |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) 此单节点结果的值，可能为 `null`。 |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) 结果快照中的节点数量。snapshotItem 索引的有效取值为 `0` 到 `snapshotLength-1`（含）。 |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) 此字符串结果的值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | 遍历并返回节点集中的下一个节点，如果没有更多节点则返回 `null`。 |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | 返回快照集合中第 `index` 项。如果 `index` 大于或等于列表中的节点数，则此方法返回 `null`。与迭代器结果不同，快照不会失效，但如果文档被修改，快照可能不再对应当前文档。 |

### 另请参阅

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
