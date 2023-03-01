---
title: SVGListBase1.RemoveItem
second_title: Aspose.HTML for .NET API 参考
description: SVGListBase 方法. 从列表中删除现有项目
type: docs
weight: 100
url: /zh/net/aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

从列表中删除现有项目。

```csharp
public T RemoveItem(ulong index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | UInt64 | 要删除的项目的索引。第一项是数字 0。 |

### 返回值

删除的项目。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 无法修改列表时引发。 |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`INDEX_SIZE_ERR`](../../../aspose.html.dom/domexception/index_size_err/). 如果索引号大于或等于 numberOfItems 则引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../)
* 命名空间 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 部件 [Aspose.HTML](../../../)


