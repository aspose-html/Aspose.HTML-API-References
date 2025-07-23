---
title: parent_node property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 780
url: /python-net/aspose.html.dom.svg/svgviewelement/parent_node/
is_root: false
---

## parent_node property


Returns the parent of the specified node in the DOM tree.


[`Document`](/html/python-net/aspose.html.dom/document) and [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment) nodes can never have a parent, so  will always return null. It also returns  if the node has just been created and is not yet attached to the tree.

### Remarks 


Reference:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-parentnode).
### Definition:
```python
@property
def parent_node(self):
    ...
```

### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`DocumentFragment`](/html/python-net/aspose.html.dom/documentfragment)
* class [`Node`](/html/python-net/aspose.html.dom/node)
* class [`SVGViewElement`](/html/python-net/aspose.html.dom.svg/svgviewelement)
