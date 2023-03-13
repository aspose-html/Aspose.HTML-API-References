---
title: Class InputElement
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Forms.InputElement klass. InputElementet representerar ett omslag som är associerat med HTMLInputElement.
type: docs
weight: 2980
url: /sv/net/aspose.html.forms/inputelement/
---
## InputElement class

InputElementet representerar ett omslag som är associerat med HTMLInputElement.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Hämtar typen av element. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | Representerar Id-attributet för indataelementet. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | Representerar en lista med alternativ |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | Representerar namnattributet för indataelementet. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | Typ av formulärkontroll. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | Representerar strängvärdet för indataelementet som är direkt mappat till attributet 'value'. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | Denna metod lägger till filer till[`Files`](../../aspose.html/htmlinputelement/files/) samling som kommer att skickas under nästa webbförfrågan. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | Returnerar kontrollstatus för inmatningselementet med kryssrutetypen . |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | Denna metod används för att få värdet som en färg. Denna metod är giltig om endast typen av inmatningselementet är "color" |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | Denna metod används för att få värdet som aDateTime objekt objekt. Denna metod är giltig om endast typen av inmatningselementet är "datetime-local" |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | Denna metod används för att få värdet som aDateTime objekt. Denna metod är giltig om endast typen av inmatningselementet är "date" |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | Denna metod används för att få värdet som ett e-poststrängobjekt. Denna metod är giltig om endast typen av inmatningselementet är "e-post" |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | Denna metod används för att få värdet som aDateTime objekt. Denna metod är giltig om endast typen av inmatningselementet är "month" |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | Denna metod används för att få värdet som ett tal. Denna metod är giltig om endast typen av inmatningselementet är "number" |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | Denna metod används för att få värdet som ett lösenordssträngobjekt. Denna metod är giltig om endast typen av inmatningselementet är "lösenord" |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | Returnerar kontrollstatus för ingångselementet med radiotypen. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | Denna metod används för att få värdet som aTimeSpan objekt. Denna metod är giltig om endast typen av inmatningselementet är "time" |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | Denna metod används för att få värdet som[`Url`](../../aspose.html/url/) objekt. Denna metod är giltig om endast typen av inmatningselementet är "url" |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | Denna metod används för att få värdet som en veckas sträng. Denna metod är giltig om endast typen av inmatningselementet är "vecka" |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Ställer in kontrollstatus för ingångselementet med kryssrutetypen. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | Denna metod används för att ställa in färg som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "color" |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | Denna metod används för att ställa inDateTimeobjekt som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselementet är "datetime-local" |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | Denna metod används för att ställa inDateTime objekt som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "date" |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | Den här metoden används för att ställa in e-poststräng som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "e-post" |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | Denna metod används för att ställa inDateTimeobjekt som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "month" |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | Denna metod används för att ställa in nummer som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "number" |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | Denna metod används för att ställa in lösenordssträng som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "lösenord" |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | Ställer in kontrollstatus för ingångselementet med radiotypen. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | Denna metod används för att ställa inTimeSpan objekt som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "time" |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | Denna metod används för att ställa in[`Url`](../../aspose.html/url/) objekt som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "url" |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | Denna metod används för att ställa in 'vecka'-strängen som ett värde för inmatningselement. Denna metod är giltig om endast typen av inmatningselement är "vecka" |

### Se även

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* namnutrymme [Aspose.Html.Forms](../../aspose.html.forms/)
* hopsättning [Aspose.HTML](../../)


