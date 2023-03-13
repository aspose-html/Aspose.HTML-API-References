---
title: Interface IXPathResult
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.XPath.IXPathResult 界面. 的XPath结果接口表示在特定节点的上下文中对 XPath 1.0 表达式求值的结果由于 XPath 表达式的计算 可以产生各种结果类型因此该对象使得 可以发现和操作结果的类型和值
type: docs
weight: 2600
url: /zh/net/aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

的`XPath结果`接口表示在特定节点的上下文中对 XPath 1.0 表达式求值的结果。由于 XPath 表达式的计算 可以产生各种结果类型，因此该对象使得 可以发现和操作结果的类型和值。

```csharp
public interface IXPathResult
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [BooleanValue](../../aspose.html.dom.xpath/ixpathresult/booleanvalue/) { get; } | 此布尔结果的值。 |
| [InvalidIteratorState](../../aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) { get; } | 表示迭代器已失效。真如果`结果类型` 是`无序节点迭代器`输入或`有序节点迭代器`类型和 返回此结果后文档已被修改。 |
| [NumberValue](../../aspose.html.dom.xpath/ixpathresult/numbervalue/) { get; } | 这个数字结果的值。 |
| [ResultType](../../aspose.html.dom.xpath/ixpathresult/resulttype/) { get; } | 表示此结果类型的代码，由 http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult 定义[`XPathResultType`](../xpathresulttype/)枚举. |
| [SingleNodeValue](../../aspose.html.dom.xpath/ixpathresult/singlenodevalue/) { get; } | 这个单节点结果的值，可能是`无效的`. |
| [SnapshotLength](../../aspose.html.dom.xpath/ixpathresult/snapshotlength/) { get; } | 结果快照中的节点数。 snapshotItem 索引的有效值为`0`到`快照长度-1`包含. |
| [StringValue](../../aspose.html.dom.xpath/ixpathresult/stringvalue/) { get; } | 这个字符串结果的值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [IterateNext](../../aspose.html.dom.xpath/ixpathresult/iteratenext/)() | 迭代并返回节点集中的下一个节点或`无效的`如果没有更多节点. |
| [SnapshotItem](../../aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | 返回`指数`快照集合中的第一个项目。如果`指数`大于 或等于列表中的节点数，此方法返回`无效的`.与 迭代器结果不同，快照不会失效，但如果发生变异，则可能与当前 文档不对应。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* 部件 [Aspose.HTML](../../)


