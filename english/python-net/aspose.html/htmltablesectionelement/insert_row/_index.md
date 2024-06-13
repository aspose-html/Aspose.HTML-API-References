﻿---
title: insert_row method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 220
url: /python-net/aspose.html/htmltablesectionelement/insert_row/
is_root: false
---

## insert_row {#int}

Insert a row into this section. The new row is inserted immediately 
before the current `index`th row in this section. If 
`index` is -1 or equal to the number of rows in this 
section, the new row is appended.


### Returns 


The newly created row.


```python
def insert_row(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The row number where to insert a new row. This index 
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified index is greater than the 





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableSectionElement`](/html/python-net/aspose.html/htmltablesectionelement)