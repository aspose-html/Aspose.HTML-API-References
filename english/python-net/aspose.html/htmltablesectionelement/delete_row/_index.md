---
title: delete_row method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/aspose.html/htmltablesectionelement/delete_row/
is_root: false
---

## delete_row {#int}

Delete a row from this section.



```python
def delete_row(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the row to be deleted, or -1 to delete the <br/>last row. This index starts from 0 and is relative only to the rows <br/>contained inside this section, not all the rows in the table. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified index is greater than or <br/>equal to the number of rows or if the index is a negative number <br/>other than -1.<br/>@version DOM Level 2 |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableSectionElement`](/html/python-net/aspose.html/htmltablesectionelement)
