---
title: Class InputElement
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Forms.InputElement klas. Das InputElement stellt einen Wrapper dar der dem HTMLInputElement zugeordnet ist.
type: docs
weight: 2980
url: /de/net/aspose.html.forms/inputelement/
---
## InputElement class

Das InputElement stellt einen Wrapper dar, der dem HTMLInputElement zugeordnet ist.

```csharp
public class InputElement : FormElement<HTMLInputElement>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ElementType](../../aspose.html.forms/formelement/elementtype/) { get; } | Ruft den Typ des Elements ab. |
| [HtmlElement](../../aspose.html.forms/formelement-1/htmlelement/) { get; } |  |
| override [Id](../../aspose.html.forms/inputelement/id/) { get; set; } | Repräsentiert das ID-Attribut des Eingabeelements. |
| [List](../../aspose.html.forms/inputelement/list/) { get; } | Stellt eine Liste von Optionen dar |
| override [Name](../../aspose.html.forms/inputelement/name/) { get; set; } | Repräsentiert das Namensattribut des Eingabeelements. |
| [Type](../../aspose.html.forms/inputelement/type/) { get; set; } | Typ des Formularsteuerelements. |
| override [Value](../../aspose.html.forms/inputelement/value/) { get; set; } | Stellt den Zeichenfolgenwert des Eingabeelements dar, das direkt dem Attribut „Wert“ zugeordnet ist. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddFile](../../aspose.html.forms/inputelement/addfile/)(string) | Diese Methode fügt Dateien zu der hinzu[`Files`](../../aspose.html/htmlinputelement/files/) Sammlung, die bei der nächsten Webanfrage gesendet wird. |
| [GetCheckboxValue](../../aspose.html.forms/inputelement/getcheckboxvalue/)() | Gibt den Checkedness-Zustand für das Eingabeelement mit dem Checkbox-Typ . zurück |
| [GetColorValue](../../aspose.html.forms/inputelement/getcolorvalue/)() | Diese Methode wird verwendet, um den Wert als Farbe zu erhalten. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "color" ist |
| [GetDateTimeLocalValue](../../aspose.html.forms/inputelement/getdatetimelocalvalue/)() | Diese Methode wird verwendet, um den Wert als a zu erhaltenDateTime Objekt Objekt. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "datetime-local" ist. |
| [GetDateValue](../../aspose.html.forms/inputelement/getdatevalue/)() | Diese Methode wird verwendet, um den Wert als a zu erhaltenDateTime Objekt. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "date" ist |
| [GetEmailValue](../../aspose.html.forms/inputelement/getemailvalue/)() | Diese Methode wird verwendet, um den Wert als E-Mail-String-Objekt abzurufen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "E-Mail" ist. |
| [GetMonthValue](../../aspose.html.forms/inputelement/getmonthvalue/)() | Diese Methode wird verwendet, um den Wert als a zu erhaltenDateTime Objekt. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Monat" ist |
| [GetNumberValue](../../aspose.html.forms/inputelement/getnumbervalue/)() | Diese Methode wird verwendet, um den Wert als Zahl zu erhalten. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Nummer" ist |
| [GetPasswordValue](../../aspose.html.forms/inputelement/getpasswordvalue/)() | Diese Methode wird verwendet, um den Wert als Passwort-String-Objekt zu erhalten. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Passwort" ist |
| [GetRadioValue](../../aspose.html.forms/inputelement/getradiovalue/)() | Gibt den Checkedness-Zustand für das Eingabeelement mit dem Typ radio zurück. |
| [GetTimeValue](../../aspose.html.forms/inputelement/gettimevalue/)() | Diese Methode wird verwendet, um den Wert als a zu erhaltenTimeSpan Objekt. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "time" ist |
| [GetUrlValue](../../aspose.html.forms/inputelement/geturlvalue/)() | Diese Methode wird verwendet, um den Wert als zu erhalten[`Url`](../../aspose.html/url/) Objekt. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "url" ist |
| [GetWeekValue](../../aspose.html.forms/inputelement/getweekvalue/)() | Diese Methode wird verwendet, um den Wert als Wochenstring zu erhalten. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Woche" ist |
| [SetCheckboxValue](../../aspose.html.forms/inputelement/setcheckboxvalue/)(bool) | Legt den Checkedness-Status für das Eingabeelement mit dem Checkbox-Typ fest. |
| [SetColorValue](../../aspose.html.forms/inputelement/setcolorvalue/)(Color) | Diese Methode wird verwendet, um die Farbe als Wert für das Eingabeelement festzulegen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "color" ist |
| [SetDateTimeLocalValue](../../aspose.html.forms/inputelement/setdatetimelocalvalue/)(DateTime) | Diese Methode wird zum Setzen verwendetDateTimeObjekt als Wert für Eingabeelement. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "datetime-local" ist. |
| [SetDateValue](../../aspose.html.forms/inputelement/setdatevalue/)(DateTime) | Diese Methode wird zum Setzen verwendetDateTime Objekt als Wert für Eingabeelement. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "date" ist. |
| [SetEmailValue](../../aspose.html.forms/inputelement/setemailvalue/)(string) | Diese Methode wird verwendet, um die E-Mail-Zeichenfolge als Wert für das Eingabeelement festzulegen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "E-Mail" ist. |
| [SetMonthValue](../../aspose.html.forms/inputelement/setmonthvalue/)(DateTime) | Diese Methode wird zum Setzen verwendetDateTimeObjekt als Wert für Eingabeelement. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Monat" ist |
| [SetNumberValue](../../aspose.html.forms/inputelement/setnumbervalue/)(float) | Diese Methode wird verwendet, um die Zahl als Wert für das Eingabeelement festzulegen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Nummer" ist |
| [SetPasswordValue](../../aspose.html.forms/inputelement/setpasswordvalue/)(string) | Diese Methode wird verwendet, um die Passwortzeichenfolge als Wert für das Eingabeelement festzulegen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Passwort" ist |
| [SetRadioValue](../../aspose.html.forms/inputelement/setradiovalue/)(bool) | Legt den Checkedness-Zustand für das Eingabeelement mit dem Radiotyp fest. |
| [SetTimeValue](../../aspose.html.forms/inputelement/settimevalue/)(TimeSpan) | Diese Methode wird zum Setzen verwendetTimeSpan Objekt als Wert für Eingabeelement. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "time" ist |
| [SetUrlValue](../../aspose.html.forms/inputelement/seturlvalue/)(Url) | Diese Methode wird zum Setzen verwendet[`Url`](../../aspose.html/url/) Objekt als Wert für Eingabeelement. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "url" ist. |
| [SetWeekValue](../../aspose.html.forms/inputelement/setweekvalue/)(string) | Diese Methode wird verwendet, um die Zeichenfolge „Woche“ als Wert für das Eingabeelement festzulegen. Diese Methode ist gültig, wenn nur der Typ des Eingabeelements "Woche" ist |

### Siehe auch

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLInputElement](../../aspose.html/htmlinputelement/)
* namensraum [Aspose.Html.Forms](../../aspose.html.forms/)
* Montage [Aspose.HTML](../../)


