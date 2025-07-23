---
title: create_document_type method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 100
url: /python-net/aspose.html.dom.svg/svgdocument/create_document_type/
is_root: false
---

## create_document_type {#str-str-str-str}

The method returns a [`DocumentType`](/html/python-net/aspose.html.dom/documenttype) object which can either be used 
with [`IDOMImplementation.create_document`](/html/python-net/aspose.html.dom/idomimplementation/create_document) upon document creation or can be put into the document via methods 
like [`Node.insert_before`](/html/python-net/aspose.html.dom/node/insert_before) or [`Node.replace_child`](/html/python-net/aspose.html.dom/node/replace_child).


### Returns 


The [`DocumentType`](/html/python-net/aspose.html.dom/documenttype).


```python
def create_document_type(self, name, public_id, system_id, internal_subset):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| name | str | Is a  containing the qualified name, like . |
| public_id | str | Is a  containing the  identifier. |
| system_id | str | Is a  containing the  identifier. |
| internal_subset | str | The internal subset. |



### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`DocumentType`](/html/python-net/aspose.html.dom/documenttype)
* class [`SVGDocument`](/html/python-net/aspose.html.dom.svg/svgdocument)
