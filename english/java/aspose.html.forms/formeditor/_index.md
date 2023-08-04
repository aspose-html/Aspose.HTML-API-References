---
title: FormEditor Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Forms.FormEditor class. This class represents the editor over the HTMLFormElement that creates a easier way for .net developers to edit the html forms
type: docs
weight: 2940
url: /java/com.aspose.html.forms/formeditor/
---
## FormEditor class

This class represents the editor over the [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) that creates a easier way for .net developers to edit the html forms.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Properties

| Name | Description |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) The number of form controls in the form. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) The original [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) that is associated with current instance of `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Returns the element by specified index. (2 indexers) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selected from the [`Forms`](../../com.aspose.html/htmldocument/forms/) collection by index. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) selected from the document by id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Creates a new [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) and associated it with `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) is created in the detached from the document state; in order to attach it to the document, please select proper location and use [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) method. |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Creates a new [`HTMLElement`](../../com.aspose.html/htmlelement/) and adds it to the end of the form. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Creates a new [`InputElement`](../inputelement/) and adds it to the end of the form. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Creates a new [`InputElement`](../inputelement/) and adds it to the end of the form. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Releases unmanaged and managed resources. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Returns the element by specified index. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Returns the element by specified name. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Gets the enumerator. |

### See Also

* class [FormElement](../formelement/)
* package [com.aspose.html.Forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
