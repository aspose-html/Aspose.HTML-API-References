---
title: HTMLTableRowElement.InsertCell
second_title: Aspose.HTML for .NET API 参考
description: HTMLTableRowElement 方法. 插入一个空的TD单元格到这一行如果 指数为 1 或等于单元格数则附加新的 单元格
type: docs
weight: 100
url: /zh/net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

插入一个空的`TD`单元格到这一行。如果 `指数`为 -1 或等于单元格数，则附加新的 单元格。

```csharp
public HTMLElement InsertCell(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入单元格的位置，从0开始。 |

### 返回值

新创建的单元格。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定`指数` 大于单元格的数量，或者如果索引是负数 而不是 -1. @version DOM Level 2 |

### 也可以看看

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* 命名空间 [Aspose.Html](../../htmltablerowelement/)
* 部件 [Aspose.HTML](../../../)


