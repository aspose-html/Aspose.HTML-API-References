---
title: InputElement
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 3060
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
| override [Id](id) { get; set; } | Represents the Id attribute of the input element. |
| [List](list) { get; } | Represents a list of options |
| override [Name](name) { get; set; } | Represent the name attribute of the input element. |
| [Type](type) { get; set; } | Type of the form control. |
| override [Value](value) { get; set; } | Represents the string value of the input element that is directly mapped to the 'value' attribute. |

## Methods

| Name | Description |
| --- | --- |
| [AddFile](addfile)(string) | This method adds files to the [`Files`](../../aspose.html/htmlinputelement/files) collection which will be sent during the next web request. |
| [GetCheckboxValue](getcheckboxvalue)() | Returns the checkedness state for the input element with the Checkbox type . |
| [GetColorValue](getcolorvalue)() | This method is used to get the value as a color. This method is valid if only only type of the input element is "color" |
| [GetDateTimeLocalValue](getdatetimelocalvalue)() | This method is used to get the value as a DateTime object object. This method is valid if only only type of the input element is "datetime-local" |
| [GetDateValue](getdatevalue)() | This method is used to get the value as a DateTime object. This method is valid if only only type of the input element is "date" |
| [GetEmailValue](getemailvalue)() | This method is used to get the value as an email string object. This method is valid if only only type of the input element is "email" |
| [GetMonthValue](getmonthvalue)() | This method is used to get the value as a DateTime object. This method is valid if only only type of the input element is "month" |
| [GetNumberValue](getnumbervalue)() | This method is used to get the value as a number. This method is valid if only only type of the input element is "number" |
| [GetPasswordValue](getpasswordvalue)() | This method is used to get the value as a password string object. This method is valid if only only type of the input element is "password" |
| [GetRadioValue](getradiovalue)() | Returns the checkedness state for the input element with the radio type. |
| [GetTimeValue](gettimevalue)() | This method is used to get the value as a TimeSpan object. This method is valid if only only type of the input element is "time" |
| [GetUrlValue](geturlvalue)() | This method is used to get the value as [`Url`](../../aspose.html/url) object. This method is valid if only only type of the input element is "url" |
| [GetWeekValue](getweekvalue)() | This method is used to get the value as a week string. This method is valid if only only type of the input element is "week" |
| [SetCheckboxValue](setcheckboxvalue)(bool) | Sets the checkedness state for the input elemen with the Checkbox type. |
| [SetColorValue](setcolorvalue)(Color) | This method is used to set color as a value for input element. This method is valid if only the type of the input element is "color" |
| [SetDateTimeLocalValue](setdatetimelocalvalue)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "datetime-local" |
| [SetDateValue](setdatevalue)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "date" |
| [SetEmailValue](setemailvalue)(string) | This method is used to set email string as a value for input element. This method is valid if only the type of the input element is "email" |
| [SetMonthValue](setmonthvalue)(DateTime) | This method is used to set DateTime object as a value for input element. This method is valid if only the type of the input element is "month" |
| [SetNumberValue](setnumbervalue)(float) | This method is used to set number as a value for input element. This method is valid if only the type of the input element is "number" |
| [SetPasswordValue](setpasswordvalue)(string) | This method is used to set password string as a value for input element. This method is valid if only the type of the input element is "password" |
| [SetRadioValue](setradiovalue)(bool) | Sets the checkedness state for the input element with the radio type. |
| [SetTimeValue](settimevalue)(TimeSpan) | This method is used to set TimeSpan object as a value for input element. This method is valid if only the type of the input element is "time" |
| [SetUrlValue](seturlvalue)(Url) | This method is used to set [`Url`](../../aspose.html/url) object as a value for input element. This method is valid if only the type of the input element is "url" |
| [SetWeekValue](setweekvalue)(string) | This method is used to set 'week' string as a value for input element. This method is valid if only the type of the input element is "week" |

### See Also

* class [FormElement&lt;T&gt;](../formelement-1)
* class [HTMLInputElement](../../aspose.html/htmlinputelement)
* namespace [Aspose.Html.Forms](../../aspose.html.forms)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
