---
title: HTMLTableRowElement.DeleteCell
second_title: Aspose.HTML for .NET API Reference
description: HTMLTableRowElement DeleteCell method. Delete a cell from the current row
type: docs
weight: 90
url: /net/aspose.html/htmltablerowelement/deletecell/
---
## HTMLTableRowElement.DeleteCell method

Delete a cell from the current row.

```csharp
public void DeleteCell(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index of the cell to delete, starting from 0. If the index is -1 the last cell in the row is deleted. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Raised if the specified `index` is greater than or equal to the number of cells or if the index is a negative number other than -1. @version DOM Level 2 |

### See Also

* class [HTMLTableRowElement](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)
