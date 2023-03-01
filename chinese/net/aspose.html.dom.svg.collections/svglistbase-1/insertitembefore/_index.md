---
title: SVGListBase1.InsertItemBefore
second_title: Aspose.HTML for .NET API 参考
description: SVGListBase 方法. 在列表的指定位置插入一个新项目第一项是数字 0.
type: docs
weight: 90
url: /zh/net/aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

在列表的指定位置插入一个新项目。第一项是数字 0.

```csharp
public T InsertItemBefore(T newItem, ulong index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入到列表中的项目。 |
| index | UInt64 | 要在其前插入新项的项的索引。第一项的编号为 0。如果索引等于 0，则将新项插入到列表的前面。如果索引大于或等于 numberOfItems，则新项目将附加到列表的末尾。 |

### 返回值

插入的项目。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | 代码[`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err/). 无法修改列表时引发。 |

### 也可以看看

* class [SVGListBase&lt;T&gt;](../)
* 命名空间 [Aspose.Html.Dom.Svg.Collections](../../svglistbase-1/)
* 部件 [Aspose.HTML](../../../)


