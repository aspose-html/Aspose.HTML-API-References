---
title: create_element method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.dom/document/create_element/
is_root: false
---

## create_element {#str}

Creates the HTML element specified by , or an  if localName isn't recognized.


### Returns 


The new [`Element`](/html/python-net/aspose.html.dom/element).


```python
def create_element(self, local_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| local_name | str | A string that specifies the type of element to be created. The  of the created element is initialized <br/>with the value of . Don't use qualified names (like "html:a") with this method.<br/>When called on an HTML document,  converts  to lower case before creating the element. |



### See Also
* module [`aspose.html.dom`](../../)
* class [`Document`](/html/python-net/aspose.html.dom/document)
* class [`Element`](/html/python-net/aspose.html.dom/element)
