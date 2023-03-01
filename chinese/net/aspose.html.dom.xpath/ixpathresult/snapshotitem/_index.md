---
title: IXPathResult.SnapshotItem
second_title: Aspose.HTML for .NET API 参考
description: IXPathResult 方法. 返回指数快照集合中的第一个项目如果指数大于 或等于列表中的节点数此方法返回无效的.与 迭代器结果不同快照不会失效但如果发生变异则可能与当前 文档不对应
type: docs
weight: 90
url: /zh/net/aspose.html.dom.xpath/ixpathresult/snapshotitem/
---
## IXPathResult.SnapshotItem method

返回`指数`快照集合中的第一个项目。如果`指数`大于 或等于列表中的节点数，此方法返回`无效的`.与 迭代器结果不同，快照不会失效，但如果发生变异，则可能与当前 文档不对应。

```csharp
public Node SnapshotItem(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 快照集合的索引。 |

### 返回值

节点位于`指数`在第th位置`节点列表`， 或者`无效的`如果 不是有效索引。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR：引发如果`结果类型`不是 `无序节点快照`输入或`有序节点快照`类型。 |

### 也可以看看

* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathResult](../)
* 命名空间 [Aspose.Html.Dom.XPath](../../ixpathresult/)
* 部件 [Aspose.HTML](../../../)


