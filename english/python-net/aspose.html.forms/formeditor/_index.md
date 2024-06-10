---
title: FormEditor class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.html.forms/formeditor/
is_root: false
---

## FormEditor class

This class represents the editor over the [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) that creates a easier way for .net developers to edit the html forms.



The FormEditor type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [form](/html/python-net/aspose.html.forms/formeditor/form) | The original [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) that is associated with current instance of [`FormEditor`](/html/python-net/aspose.html.forms/formeditor). |
| [count](/html/python-net/aspose.html.forms/formeditor/count) | The number of form controls in the form. |
| [method](/html/python-net/aspose.html.forms/formeditor/method) | HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |
| [action](/html/python-net/aspose.html.forms/formeditor/action) | Server-side form handler. See the action attribute definition in HTML 4.01. |



Returns the element by specified index.
### Indexer
| Name | Description |
| :- | :- |
| [index] | The index of the element |


### Methods
| Method | Description |
| :- | :- |
| [create](/html/python-net/aspose.html.forms/formeditor/create/#aspose.html.HTMLFormElement) | Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement). |
| [create](/html/python-net/aspose.html.forms/formeditor/create/#aspose.html.HTMLDocument-int) | Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) selected from the [`HTMLDocument.forms`](/html/python-net/aspose.html/htmldocument#forms) collection by index. |
| [create](/html/python-net/aspose.html.forms/formeditor/create/#aspose.html.HTMLDocument-str) | Creates a new [`FormEditor`](/html/python-net/aspose.html.forms/formeditor) based on [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) selected from the document by id. |
| [add_input](/html/python-net/aspose.html.forms/formeditor/add_input/#str) | Creates a new [`InputElement`](/html/python-net/aspose.html.forms/inputelement) and adds it to the end of the form. |
| [add_input](/html/python-net/aspose.html.forms/formeditor/add_input/#str-aspose.html.forms.InputElementType) | Creates a new [`InputElement`](/html/python-net/aspose.html.forms/inputelement) and adds it to the end of the form. |
| [create_new](/html/python-net/aspose.html.forms/formeditor/create_new/#aspose.html.HTMLDocument) | Creates a new [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) and associated it with [`FormEditor`](/html/python-net/aspose.html.forms/formeditor). [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement) is created in the detached from the document state; in order to attach it to the document, please select proper location and use [`Node.append_child`](/html/python-net/aspose.html.dom/node/append_child) method. |



### See Also
* module [`aspose.html.forms`](..)
* class [`FormEditor`](/html/python-net/aspose.html.forms/formeditor)
* class [`HTMLFormElement`](/html/python-net/aspose.html/htmlformelement)
* class [`InputElement`](/html/python-net/aspose.html.forms/inputelement)
