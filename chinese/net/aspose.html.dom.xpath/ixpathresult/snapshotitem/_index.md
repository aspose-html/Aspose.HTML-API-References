---
title: SnapshotItem
second_title: Aspose.HTML for .NET API 参考
description: 返回 索引 快照集合中的第一项 如果 索引 大于 或等于列表中的节点数此方法返回 空 . 与 迭代器结果不同快照不会变得无效但如果它发生突变则可能与当前的 文档不对应
type: docs
weight: 90
url: /zh/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

返回` 索引` 快照集合中的第一项。 如果` 索引` 大于 或等于列表中的节点数，此方法返回` 空` . 与 迭代器结果不同，快照不会变得无效，但如果它发生突变，则可能与当前的 文档不对应。

```csharp
public Node SnapshotItem(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 对快照集合的索引。 |

### 返回值

`处的节点 索引``中的第 th 位 节点列表` , 或` 空` 如果 那不是一个有效的索引。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | TYPE_ERR:如果`则引发 结果类型` 不是 ` UnorderedNodeSnapshot` 键入或` OrderedNodeSnapshot` 类型。 |

### 也可以看看

* class [Node](../../../aspose.html.dom/node)
* interface [IXPathResult](../../ixpathresult)
* 命名空间 [Aspose.Html.Dom.XPath](../../ixpathresult)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->