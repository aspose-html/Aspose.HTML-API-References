---
title: IElementCSSInlineStyle Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Css.IElementCSSInlineStyle interface. Inline style information attached to elements is exposed through the style attribute. This represents the contents of the STYLE attribute for HTML elements or elements in other schemas or DTDs which use the STYLE attribute in the same way. The expectation is that an instance of the ElementCSSInlineStyle interface can be obtained by using binding-specific casting methods on an instance of the Element interface when the element supports inline CSS style informations
type: docs
weight: 570
url: /net/aspose.html.dom.css/ielementcssinlinestyle/
---
## IElementCSSInlineStyle interface

Inline style information attached to elements is exposed through the style attribute. This represents the contents of the STYLE attribute for HTML elements (or elements in other schemas or DTDs which use the STYLE attribute in the same way). The expectation is that an instance of the ElementCSSInlineStyle interface can be obtained by using binding-specific casting methods on an instance of the Element interface when the element supports inline CSS style informations.

See also the [CSS Object Model (CSSOM) # IElementCSSInlineStyle](https://www.w3.org/TR/cssom-1/#the-elementcssinlinestyle-mixin)

```csharp
public interface IElementCSSInlineStyle
```

## Properties

| Name | Description |
| --- | --- |
| [Style](../../aspose.html.dom.css/ielementcssinlinestyle/style/) { get; } | The style attribute must return a CSS declaration block object whose computed flag is unset, whose parent CSS rule is null, and whose owner node is the context object. |

### See Also

* namespace [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* assembly [Aspose.HTML](../../)
