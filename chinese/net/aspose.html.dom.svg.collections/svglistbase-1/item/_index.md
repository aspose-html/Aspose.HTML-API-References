---
title: SVGListBase1.Item
second_title: Aspose.HTML for .NET API 参考
description: SVGListBase 财产. 返回列表中的第 indexth 项
type: docs
weight: 10
url: /zh/net/aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

返回列表中的第 indexth 项。

```csharp
public T this[ulong index] { get; set; }
```

| 范围 | 描述 |
| --- | --- |
| index | 列表中的索引。 |

### 返回值

列表中第 index 个位置的存储对象。

### 适当的价值

列表中存储的项目类型。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 在无法修改列表时引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). 如果索引号大于或等于 numberOfItems 则引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../)
* 命名空间 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 部件 [Aspose.HTML](../../../)


