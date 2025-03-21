---
title: IDocumentCSS Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.IDocumentCSS interface. This interface represents a document with a CSS view
type: docs
weight: 710
url: /net/aspose.html.dom.css/idocumentcss/
---
## IDocumentCSS interface

This interface represents a document with a CSS view.

The getOverrideStyle method provides a mechanism through which a DOM author could effect immediate change to the style of an element without modifying the explicitly linked style sheets of a document or the inline style of elements in the style sheets. This style sheet comes after the author style sheet in the cascade algorithm and is called override style sheet. The override style sheet takes precedence over author style sheets. An "!important" declaration still takes precedence over a normal declaration. Override, author, and user style sheets all may contain "!important" declarations. User "!important" rules take precedence over both override and author "!important" rules, and override "!important" rules take precedence over author "!important" rules.

The expectation is that an instance of the DocumentCSS interface can be obtained by using binding-specific casting methods on an instance of the Document interface.

See also the [Document Object Model (DOM) Level 2 Style Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113).

```csharp
public interface IDocumentCSS : IDocumentStyle
```

## Methods

| Name | Description |
| --- | --- |
| [GetOverrideStyle](../../aspose.html.dom.css/idocumentcss/getoverridestyle/)(*[Element](../../aspose.html.dom/element/), string*) | This method is used to retrieve the override style declaration for a specified element and a specified pseudo-element. |

### See Also

* interface [IDocumentStyle](../idocumentstyle/)
* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
