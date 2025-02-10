---
title: HTMLTableSectionElement.DeleteRow
second_title: Aspose.HTML for Java API Reference
description: HTMLTableSectionElement method. Delete a row from this section
type: docs
weight: 60
url: /java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

Delete a row from this section.

```java
public void DeleteRow(int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| index | Int32 | The index of the row to be deleted, or -1 to delete the last row. This index starts from 0 and is relative only to the rows contained inside this section, not all the rows in the table. |

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR: Raised if the specified index is greater than or equal to the number of rows or if the index is a negative number other than -1. @version DOM Level 2 |

### See Also

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
