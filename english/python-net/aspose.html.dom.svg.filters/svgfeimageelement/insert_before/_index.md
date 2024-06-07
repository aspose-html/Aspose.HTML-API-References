---
title: insert_before method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 200
url: /aspose.html.dom.svg.filters/svgfeimageelement/insert_before/
is_root: false
---

## insert_before {#aspose.html.dom.Node-aspose.html.dom.Node}

Inserts the node before the existing child node child. If child is null, insert node at the end of the list of children.
If child is a DocumentFragment object, all of its children are inserted, in the same order, before child. If the child is already in the tree, it is first removed.


### Returns 


Returns inserted node


```python
def insert_before(self, node, child):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| node | [`Node`](/html/python-net/aspose.html.dom/node) | The new child. |
| child | [`Node`](/html/python-net/aspose.html.dom/node) | The ref child. |



### See Also
* module [`aspose.html.dom.svg.filters`](../../)
* class [`SVGFEImageElement`](/html/python-net/aspose.html.dom.svg.filters/svgfeimageelement)
