---
title: images property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 800
url: /aspose.html/htmldocument/images/
is_root: false
---

## images property


A collection of all the `IMG` elements in a document. The 
behavior is limited to `IMG` elements for backwards 
compatibility. As suggested by [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)], to include images, authors may use 
the `OBJECT` element or the `IMG` element. 
Therefore, it is recommended not to use this attribute to find the 
images in the document but `getElementsByTagName` with 
HTML 4.01 or `getElementsByTagNameNS` with XHTML 1.0.
### Definition:
```python
@property
def images(self):
    ...
```

### See Also
* module [`aspose.html`](../../)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
