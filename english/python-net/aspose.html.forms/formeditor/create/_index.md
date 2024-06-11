---
title: create method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.html.forms/formeditor/create/
is_root: false
---

## create {#aspose.html.HTMLFormElement}

Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement).


### Returns 


Return a new instance of the [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) class


```python
def create(self, form):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| form | [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) | The html form element |


## create {#aspose.html.HTMLDocument-int}

Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) selected from the [`HTMLDocument.forms`](/html/python-net/aspose.html/htmldocument#forms) collection by index.


### Returns 


Return a new instance of the [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) class


```python
def create(self, document, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | [`HTMLDocument`](/html/python-net/aspose.html/htmldocument) | The document. |
| index | int | The index inside the forms collection. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | The exception is occured if index out of the range. |




## create {#aspose.html.HTMLDocument-str}

Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) selected from the document by id.


### Returns 


Return a new instance of the [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) class


```python
def create(self, document, id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| document | [`HTMLDocument`](/html/python-net/aspose.html/htmldocument) | The document. |
| id | str | The identifier. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | The exception is occured if there is no element by specified Id or element is not a form type. |





### See Also
* module [`aspose.html.forms`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`FormEditor`](/html/python-net/aspose.html.forms/formeditor)
* class [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement)
