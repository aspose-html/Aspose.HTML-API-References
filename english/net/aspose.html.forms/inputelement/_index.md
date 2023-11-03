---
title: InputElement Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Forms.InputElement class. The InputElement represents a wrapper that is associated with the HTMLInputElement
type: docs
weight: 3140
url: /net/aspose.html.forms/inputelement/
---
## InputElement class

The InputElement represents a wrapper that is associated with the HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Properties

| Name | Description |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Gets the type of the element. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | Represents the Id attribute of the input element. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | Represents a list of options |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | Represent the name attribute of the input element. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | Type of the form control. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | Represents the string value of the input element that is directly mapped to the 'value' attribute. |

## Methods

| Name | Description |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | This method adds files to the [`Files`](../../aspose.html/htmlinputelement/files/) collection which will be sent during the next web request. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | Returns the checkedness state for the input element with the Checkbox type . |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | This method is used to get the value as a color. This method is valid if only only type of the input element is "color" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | This method is used to get the value as a DateTime object object. This method is valid if only only type of the input element is "datetime-local" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | This method is used to get the value as a DateTime object. This method is valid if only only type of the input element is "date" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | This method is used to get the value as an email string object. This method is valid if only only type of the input element is "email" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | This method is used to get the value as a DateTime object. This method is valid if only only type of the input element is "month" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | This method is used to get the value as a number. This method is valid if only only type of the input element is "number" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | This method is used to get the value as a password string object. This method is valid if only only type of the input element is "password" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | Returns the checkedness state for the input element with the radio type. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | This method is used to get the value as a TimeSpan object. This method is valid if only only type of the input element is "time" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | This method is used to get the value as [`Url`](../../aspose.html/url/) object. This method is valid if only only type of the input element is "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | This method is used to get the value as a week string. This method is valid if only only type of the input element is "week" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Sets the checkedness state for the input elemen with the Checkbox type. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | This method is used to set color as a value for input element. This method is valid if only the type of the input element is "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "date" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | This method is used to set email string as a value for input element. This method is valid if only the type of the input element is "email" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "month" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | This method is used to set number as a value for input element. This method is valid if only the type of the input element is "number" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | This method is used to set password string as a value for input element. This method is valid if only the type of the input element is "password" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | Sets the checkedness state for the input element with the radio type. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | This method is used to set TimeSpan object as a value for input element. This method is valid if only the type of the input element is "time" |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | This method is used to set [`Url`](../../aspose.html/url/) object as a value for input element. This method is valid if only the type of the input element is "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | This method is used to set 'week' string as a value for input element. This method is valid if only the type of the input element is "week" |

### See Also

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* namespace [Aspose.Html.Forms](../../aspose.html.forms/)
* assembly [Aspose.HTML](../../)
