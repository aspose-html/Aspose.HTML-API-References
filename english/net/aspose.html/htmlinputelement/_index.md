---
title: HTMLInputElement
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 3400
url: /net/aspose.html/htmlinputelement/
---
## HTMLInputElement class

Form control.Depending upon the environment in which the page is being viewed, the value property may be read-only for the file upload input type. For the "password" input type, the actual value returned may be masked to prevent unauthorized use. See the INPUT element definition in [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

See also the [Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLInputElement : HTMLElement
```

## Properties

| Name | Description |
| --- | --- |
| [Accept](accept) { get; set; } | A comma-separated list of content types that a server processing this form will handle correctly. See the accept attribute definition in HTML 4.01. |
| [AccessKey](accesskey) { get; set; } | A single character access key to give access to the form control. See the accesskey attribute definition in HTML 4.01. |
| [Align](align) { get; set; } | Aligns this object (vertically or horizontally) with respect to its surrounding text. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
| [Alt](alt) { get; set; } | Alternate text for user agents not rendering the normal content of this element. See the alt attribute definition in HTML 4.01. |
| [Checked](checked) { get; set; } | When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent. |
| [DefaultChecked](defaultchecked) { get; set; } | When `type` has the value "radio" or "checkbox", this represents the HTML checked attribute of the element. The value of this attribute does not change if the state of the corresponding form control, in an interactive user agent, changes. See the checked attribute definition in HTML 4.01. |
| [DefaultValue](defaultvalue) { get; set; } | When the `type` attribute of the element has the value "text", "file" or "password", this represents the HTML value attribute of the element. The value of this attribute does not change if the contents of the corresponding form control, in an interactive user agent, changes. See the value attribute definition in HTML 4.01. |
| [Disabled](disabled) { get; set; } | The control is unavailable in this context. See the disabled attribute definition in HTML 4.01. |
| [Files](files) { get; } | The files IDL attribute allows scripts to access the element’s selected files. On getting, if the IDL attribute applies, it must return a FileList object that represents the current selected files. The same object must be returned until the list of selected files changes. If the IDL attribute does not apply, then it must instead return null. [FILEAPI] |
| [Form](form) { get; set; } | Returns the `FORM` element containing this control. Returns `null` if this control is not within the context of a form. |
| [List](list) { get; set; } | The list attribute is used to identify an element that lists predefined options suggested to the user. If present, its value must be the ID of a datalist element in the same document. |
| [MaxLength](maxlength) { get; set; } | Maximum number of characters for text fields, when `type` has the value "text" or "password". See the maxlength attribute definition in HTML 4.01. |
| [Name](name) { get; set; } | Form control or object name when submitted with a form. See the name attribute definition in HTML 4.01. |
| [ReadOnly](readonly) { get; set; } | This control is read-only. Relevant only when `type` has the value "text" or "password". See the readonly attribute definition in HTML 4.01. |
| [Size](size) { get; set; } | Size information. The precise meaning is specific to each type of field. See the size attribute definition in HTML 4.01. @version DOM Level 2 |
| [Src](src) { get; set; } | When the `type` attribute has the value "image", this attribute specifies the location of the image to be used to decorate the graphical submit button. See the src attribute definition in HTML 4.01. |
| [TabIndex](tabindex) { get; set; } | Index that represents the element's position in the tabbing order. See the tabindex attribute definition in HTML 4.01. |
| [Type](type) { get; set; } | The type of control created (all lower case). See the type attribute definition in HTML 4.01. @version DOM Level 2 |
| [UseMap](usemap) { get; set; } | Use client-side image map. See the usemap attribute definition in HTML 4.01. |
| [Value](value) { get; set; } | When the `type` attribute of the element has the value "text", "file" or "password", this represents the current contents of the corresponding form control, in an interactive user agent. Changing this attribute changes the contents of the form control, but does not change the value of the HTML value attribute of the element. When the `type` attribute of the element has the value "button", "hidden", "submit", "reset", "image", "checkbox" or "radio", this represents the HTML value attribute of the element. See the value attribute definition in HTML 4.01. |

### See Also

* class [HTMLElement](../htmlelement)
* namespace [Aspose.Html](../../aspose.html)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
