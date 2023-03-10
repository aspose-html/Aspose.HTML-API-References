---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML for .NET API Reference
description: HTMLTableSectionElement method. Insert a row into this section. The new row is inserted immediately before the current indexth row in this section. If index is -1 or equal to the number of rows in this section the new row is appended
type: docs
weight: 70
url: /net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

Insert a row into this section. The new row is inserted immediately before the current `index`th row in this section. If `index` is -1 or equal to the number of rows in this section, the new row is appended.

```csharp
public HTMLElement InsertRow(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The row number where to insert a new row. This index starts from 0 and is relative only to the rows contained inside this section, not all the rows in the table. |

### Return Value

The newly created row.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Raised if the specified index is greater than the number of rows of if the index is a negative number other than -1. @version DOM Level 2 |

### See Also

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* namespace [Aspose.Html](../../htmltablesectionelement/)
* assembly [Aspose.HTML](../../../)
