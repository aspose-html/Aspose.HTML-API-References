---
title: insert_cell method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 220
url: /python-net/aspose.html/htmltablerowelement/insert_cell/
is_root: false
---

## insert_cell {#int}

Insert an empty `TD` cell into this row. If 
`index` is -1 or equal to the number of cells, the new 
cell is appended.


### Returns 


The newly created cell.


```python
def insert_cell(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The place to insert the cell, starting from 0. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified `index` is greater <br/>than the number of cells or if the index is a negative number other <br/>than -1.<br/>@version DOM Level 2 |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableRowElement`](/html/python-net/aspose.html/htmltablerowelement)
