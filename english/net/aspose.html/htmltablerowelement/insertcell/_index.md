---
title: HTMLTableRowElement.InsertCell
second_title: Aspose.HTML for .NET API Reference
description: HTMLTableRowElement method. Insert an empty TD cell into this row. If index is -1 or equal to the number of cells the new cell is appended
type: docs
weight: 100
url: /net/aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

Insert an empty `TD` cell into this row. If `index` is -1 or equal to the number of cells, the new cell is appended.

```csharp
public HTMLElement InsertCell(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The place to insert the cell, starting from 0. |

### Return Value

The newly created cell.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Raised if the specified `index` is greater than the number of cells or if the index is a negative number other than -1. @version DOM Level 2 |

### See Also

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* namespace [Aspose.Html](../../htmltablerowelement/)
* assembly [Aspose.HTML](../../../)
