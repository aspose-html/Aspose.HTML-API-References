---
title: anchors property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 610
url: /python-net/aspose.html/htmldocument/anchors/
is_root: false
---

## anchors property


A collection of all the anchor (`A`) elements in a document 
with a value for the `name` attribute. For reasons of 
backward compatibility, the returned set of anchors only contains 
those anchors created with the `name` attribute, not those 
created with the `id` attribute. Note that in [[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)], the 
`name` attribute (see section 4.10) has no semantics and 
is only present for legacy user agents: the `id` attribute 
is used instead. Users should prefer the iterator mechanisms provided 
by [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] instead.
### Definition:
```python
@property
def anchors(self):
    ...
```

### See Also
* module [`aspose.html`](../../)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
