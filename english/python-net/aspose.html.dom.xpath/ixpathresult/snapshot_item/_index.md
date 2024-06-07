---
title: snapshot_item method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.dom.xpath/ixpathresult/snapshot_item/
is_root: false
---

## snapshot_item {#int}

Returns the `index`th item in the snapshot collection. If `index` is greater than 
or equal to the number of nodes in the list, this method returns `null`. Unlike the 
iterator result, the snapshot does not become invalid, but may not correspond to the current 
document if it is mutated.


### Returns 


The node at the `index`th position in the `NodeList`, or `null` if 
that is not a valid index.


```python
def snapshot_item(self, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | int | Index into the snapshot collection. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | TYPE_ERR: raised if `resultType` is not <br/>`UnorderedNodeSnapshot` type or `OrderedNodeSnapshot` type. |





### See Also
* module [`aspose.html.dom.xpath`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`IXPathResult`](/html/python-net/aspose.html.dom.xpath/ixpathresult)
