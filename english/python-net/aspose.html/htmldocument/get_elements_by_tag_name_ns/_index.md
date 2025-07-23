---
title: get_elements_by_tag_name_ns method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 260
url: /python-net/aspose.html/htmldocument/get_elements_by_tag_name_ns/
is_root: false
---

## get_elements_by_tag_name_ns {#str-str}

Returns a list of elements with the given tag name belonging to the given namespace.
The complete document is searched, including the root node.


### Returns 


A live [`NodeList`](/html/python-net/aspose.html.collections/nodelist) of found elements in the order they appear in the tree.


```python
def get_elements_by_tag_name_ns(self, namespace_uri, local_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| namespace_uri | str | The namespace URI of elements to look for. |
| local_name | str | Either the local name of elements to look for or the special value *, which matches all elements. |
### Remarks

Refer to official [spec](https://dom.spec.whatwg.org/#dom-document-getelementsbytagnamens).


### See Also
* module [`aspose.html`](../../)
* class [`HTMLCollection`](/html/python-net/aspose.html.collections/htmlcollection)
* class [`HTMLDocument`](/html/python-net/aspose.html/htmldocument)
* class [`NodeList`](/html/python-net/aspose.html.collections/nodelist)
