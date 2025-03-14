---
title: HTMLTableElement.DeleteRow
second_title: Aspose.HTML for .NET API Reference
description: HTMLTableElement DeleteRow method. Delete a table row
type: docs
weight: 190
url: /net/aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

Delete a table row.

```csharp
public void DeleteRow(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index of the row to be deleted. This index starts from 0 and is relative to the logical order (not document order) of all the rows contained inside the table. If the index is -1 the last row in the table is deleted. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Raised if the specified index is greater than or equal to the number of rows or if the index is a negative number other than -1. @version DOM Level 2 |

### See Also

* class [HTMLTableElement](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)
