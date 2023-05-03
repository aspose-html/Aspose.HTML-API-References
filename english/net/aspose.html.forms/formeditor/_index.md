---
title: FormEditor Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Forms.FormEditor class. This class represents the editor over the HTMLFormElement that creates a easier way for .net developers to edit the html forms
type: docs
weight: 2940
url: /net/aspose.html.forms/formeditor/
---
## FormEditor class

This class represents the editor over the [`HTMLFormElement`](../../aspose.html/htmlformelement/) that creates a easier way for .net developers to edit the html forms.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Properties

| Name | Description |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Server-side form handler. See the action attribute definition in HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | The number of form controls in the form. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | The original [`HTMLFormElement`](../../aspose.html/htmlformelement/) that is associated with current instance of `FormEditor`. |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Returns the element by specified index. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../aspose.html/htmlformelement/). |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../aspose.html/htmlformelement/) selected from the [`Forms`](../../aspose.html/htmldocument/forms/) collection by index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Creates a new `FormEditor` based on [`HTMLFormElement`](../../aspose.html/htmlformelement/) selected from the document by id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Creates a new [`HTMLFormElement`](../../aspose.html/htmlformelement/) and associated it with `FormEditor`. [`HTMLFormElement`](../../aspose.html/htmlformelement/) is created in the detached from the document state; in order to attach it to the document, please select proper location and use [`AppendChild`](../../aspose.html.dom/node/appendchild/) method. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Creates a new [`HTMLElement`](../../aspose.html/htmlelement/) and adds it to the end of the form. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Creates a new [`InputElement`](../inputelement/) and adds it to the end of the form. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Creates a new [`InputElement`](../inputelement/) and adds it to the end of the form. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Releases unmanaged and managed resources. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) |  |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Returns the element by specified index. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Returns the element by specified name. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Gets the enumerator. |

### See Also

* class [FormElement](../formelement/)
* namespace [Aspose.Html.Forms](../../aspose.html.forms/)
* assembly [Aspose.HTML](../../)
