---
title: HTMLInputElement.Checked
second_title: Aspose.HTML for Java API Reference
description: HTMLInputElement property. When the type attribute of the element has the value radio or checkbox this represents the current state of the form control in an interactive user agent. Changes to this attribute change the state of the form control but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value radio or checkbox some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent
type: docs

url: /java/com.aspose.html/htmlinputelement/checked/
---
## HTMLInputElement.Checked property

When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent.

```java
public bool Checked { get; set; }
```

### See Also

* class [HTMLInputElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
