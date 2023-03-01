---
title: Class FormEditor
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Forms.FormEditor klass. Den här klassen representerar redigeraren överHTMLFormElement som skapar ett enklare sätt för .netutvecklare att redigera htmlformulären.
type: docs
weight: 2930
url: /sv/net/aspose.html.forms/formeditor/
---
## FormEditor class

Den här klassen representerar redigeraren över[`HTMLFormElement`](../../aspose.html/htmlformelement/) som skapar ett enklare sätt för .net-utvecklare att redigera html-formulären.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Formulärhanterare på serversidan. Se definitionen av handlingsattribut i HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Antalet formulärkontroller i formuläret. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Originalet[`HTMLFormElement`](../../aspose.html/htmlformelement/) som är associerad med aktuell instans av`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Returnerar elementet med angivet index. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP-metod [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) används för att skicka in formuläret. Se metodattributdefinitionen i HTML 4.01. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Skapar en ny`FormEditor` baserat på[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Skapar en ny`FormEditor` baserat på[`HTMLFormElement`](../../aspose.html/htmlformelement/) valt från[`Forms`](../../aspose.html/htmldocument/forms/) samling efter index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Skapar en ny`FormEditor` baserat på[`HTMLFormElement`](../../aspose.html/htmlformelement/) valt från dokumentet av id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Skapar en ny[`HTMLFormElement`](../../aspose.html/htmlformelement/) och förknippade det med`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) skapas i tillståndet frikopplat från dokumentet; för att bifoga den till dokumentet, välj lämplig plats och användning[`AppendChild`](../../aspose.html.dom/node/appendchild/) metod. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Skapar en ny[`HTMLElement`](../../aspose.html/htmlelement/) och lägger till det i slutet av formuläret. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Skapar en ny[`InputElement`](../inputelement/) och lägger till det i slutet av formuläret. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Skapar en ny[`InputElement`](../inputelement/) och lägger till det i slutet av formuläret. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Frigör ohanterade och hanterade resurser. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Denna metod fyller hela formuläret med de angivna värdena. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Returnerar elementet med angivet index. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Returnerar elementet med angivet namn. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Hämtar enumeratorn. |

### Se även

* class [FormElement](../formelement/)
* namnutrymme [Aspose.Html.Forms](../../aspose.html.forms/)
* hopsättning [Aspose.HTML](../../)


