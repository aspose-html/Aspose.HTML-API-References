---
title: HTMLTableElement.DeleteRow
second_title: Aspose.HTML for .NET API 参考
description: HTMLTableElement 方法. 删除表格行
type: docs
weight: 190
url: /zh/net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

删除表格行。

```csharp
public void DeleteRow(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的行的索引。该索引从 从 0 开始，并且是相对于 表中包含的所有行的逻辑顺序（不是文档顺序）。如果索引为 -1，表中的 最后一行将被删除。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于或 等于行数，或者索引是负数 而不是-1. @version DOM Level 2 |

### 也可以看看

* class [HTMLTableElement](../)
* 命名空间 [Aspose.Html](../../htmltableelement/)
* 部件 [Aspose.HTML](../../../)


