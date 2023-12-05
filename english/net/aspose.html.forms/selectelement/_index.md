---
title: SelectElement Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Forms.SelectElement class. The SelectElement represents a wrapper that is associated with the HTMLSelectElement
type: docs
weight: 3190
url: /net/aspose.html.forms/selectelement/
---
## SelectElement class

The SelectElement represents a wrapper that is associated with the HTMLSelectElement

```csharp
public class SelectElement : FormElement<HTMLSelectElement>
```

## Properties

| Name | Description |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Gets the type of the element. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/selectelement/id/) { get; set; } | Represents the Id attribute of the input element. |
| [Multiple](../../aspose.html.forms/selectelement/multiple/) { get; set; } | If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| override [Name](../../aspose.html.forms/selectelement/name/) { get; set; } | Represent the name attribute of the input element. |
| [Options](../../aspose.html.forms/selectelement/options/) { get; } | Returns a list of options |
| [SelectedOptions](../../aspose.html.forms/selectelement/selectedoptions/) { get; } | Returns a list of selected options |
| [Type](../../aspose.html.forms/selectelement/type/) { get; } | The type of this form control. This is the string "select-multiple" when the multiple attribute is `true` and the string "select-one" when `false`. |
| override [Value](../../aspose.html.forms/selectelement/value/) { get; set; } | On getting, must return the value of the first option element in the list of options in tree order that has its selectedness set to true, if any. |

## Methods

| Name | Description |
| --- | --- |
| [SelectItems](../../aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | This methods allows to select multiple options by their indexes. |
| [SelectItems](../../aspose.html.forms/selectelement/selectitems/#selectitems_1)(params string[]) | This methods allows to select multiple options by their values. |

### See Also

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../aspose.html/htmlselectelement/)
* namespace [Aspose.Html.Forms](../../aspose.html.forms/)
* assembly [Aspose.HTML](../../)
