---
title: insert_row method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 280
url: /python-net/aspose.html/htmltableelement/insert_row/
is_root: false
---

## insert_row {#int}

Insert a new empty row in the table. The new row is inserted 
immediately before and in the same section as the current 
`index`th row in the table. If `index` is -1 or 
equal to the number of rows, the new row is appended. In addition, 
when the table is empty the row is inserted into a `TBODY` 
which is created and inserted into the table.A table row cannot be 
empty according to [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].


### Returns 


The newly created row.


```python
def insert_row(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The row number where to insert a new row. This index <br/>starts from 0 and is relative to the logical order (not document <br/>order) of all the rows contained inside the table. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | INDEX_SIZE_ERR: Raised if the specified index is greater than the <br/>number of rows or if the index is a negative number other than -1.<br/>@version DOM Level 2 |





### See Also
* module [`aspose.html`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`HTMLTableElement`](/html/python-net/aspose.html/htmltableelement)
* class [`Node`](/html/python-net/aspose.html.dom/node)
