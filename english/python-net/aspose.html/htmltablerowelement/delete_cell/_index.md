---
title: delete_cell method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.html/htmltablerowelement/delete_cell/
is_root: false
---

## delete_cell {#int}

Delete a cell from the current row.



```python
def delete_cell(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the cell to delete, starting from 0. If the <br/>index is -1 the last cell in the row is deleted. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified `index` is greater <br/>than or equal to the number of cells or if the index is a negative <br/>number other than -1.<br/>@version DOM Level 2 |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableRowElement`](/html/python-net/aspose.html/htmltablerowelement)
