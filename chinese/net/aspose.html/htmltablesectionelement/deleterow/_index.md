---
title: HTMLTableSectionElement.DeleteRow
second_title: Aspose.HTML for .NET API 参考
description: HTMLTableSectionElement 方法. 从此部分删除一行
type: docs
weight: 60
url: /zh/net/aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

从此部分删除一行。

```csharp
public void DeleteRow(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的行的索引，或 -1 以删除 最后一行。该索引从 0 开始，仅与该部分中包含的行 相关，而不是表中的所有行。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于或 等于行数，或者索引是负数 而不是-1. @version DOM Level 2 |

### 也可以看看

* class [HTMLTableSectionElement](../)
* 命名空间 [Aspose.Html](../../htmltablesectionelement/)
* 部件 [Aspose.HTML](../../../)


