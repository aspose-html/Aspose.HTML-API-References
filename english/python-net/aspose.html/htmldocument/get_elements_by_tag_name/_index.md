---
title: get_elements_by_tag_name method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 250
url: /python-net/aspose.html/htmldocument/get_elements_by_tag_name/
is_root: false
---

## get_elements_by_tag_name {#str}

This method returns an [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) of elements with the given tag name.


The complete document is searched, including the root node. 
The returned [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) is live,
meaning that it updates itself automatically to stay in sync with the DOM tree without having to call 
this method again.


### Returns 


A live [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection) of found elements in the order they appear in the tree.


```python
def get_elements_by_tag_name(self, tagname):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| tagname | str | A string representing the name of the elements. The special string  represents all elements. |
### Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagname).


### See Also
* module [`aspose.html`](../../)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
