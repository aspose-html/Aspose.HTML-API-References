---
title: delete_row method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/aspose.html/htmltableelement/delete_row/
is_root: false
---

## delete_row {#int}

Delete a table row.



```python
def delete_row(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the row to be deleted. This index starts <br/>from 0 and is relative to the logical order (not document order) of <br/>all the rows contained inside the table. If the index is -1 the <br/>last row in the table is deleted. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified index is greater than or <br/>equal to the number of rows or if the index is a negative number <br/>other than -1.<br/>@version DOM Level 2 |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableElement`](/html/python-net/aspose.html/htmltableelement)
