---
title: HTMLInputElement.Checked
second_title: Aspose.HTML for .NET API Reference
description: HTMLInputElement Checked property. When the type attribute of the element has the value radio or checkbox this represents the current state of the form control in an interactive user agent. Changes to this attribute change the state of the form control but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value radio or checkbox some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent
type: docs
weight: 50
url: /net/aspose.html/htmlinputelement/checked/
---
## HTMLInputElement.Checked property

When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent.

```csharp
public bool Checked { get; set; }
```

### See Also

* class [HTMLInputElement](../)
* namespace [Aspose.Html](../../../aspose.html/)
* assembly [Aspose.HTML](../../../)
