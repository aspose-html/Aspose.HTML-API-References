---
title: RemoveItem
second_title: Aspose.HTML for .NET API 参考
description: 从列表中删除现有项目
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

被移除的项。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err)。 无法修改列表时引发。 |
| [DOMException](../../../aspose.html.dom/domexception) | 代码INDEX_SIZE_ERR。 如果索引号大于或等于 numberOfItems，则引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../../svglistbase-1)
* 命名空间 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1)
* 部件 [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->