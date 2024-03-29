---
title: Class FormEditor
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Forms.FormEditor klas. Diese Klasse repräsentiert den Editor über dieHTMLFormElement Das schafft eine einfachere Möglichkeit für .netEntwickler die HTMLFormulare zu bearbeiten.
type: docs
weight: 2930
url: /de/net/aspose.html.forms/formeditor/
---
## FormEditor class

Diese Klasse repräsentiert den Editor über die[`HTMLFormElement`](../../aspose.html/htmlformelement/) Das schafft eine einfachere Möglichkeit für .net-Entwickler, die HTML-Formulare zu bearbeiten.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Serverseitiger Formularhandler. Siehe Aktionsattributdefinition in HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Die Anzahl der Formularsteuerelemente im Formular. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Das Original[`HTMLFormElement`](../../aspose.html/htmlformelement/) die der aktuellen Instanz von zugeordnet ist`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Gibt das Element nach dem angegebenen Index zurück. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP-Methode [[IETF-RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) zum Absenden des Formulars verwendet. Siehe Methodenattributdefinition in HTML 4.01. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Erstellt eine neue`FormEditor` bezogen auf[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Erstellt eine neue`FormEditor` bezogen auf[`HTMLFormElement`](../../aspose.html/htmlformelement/) ausgewählt aus der[`Forms`](../../aspose.html/htmldocument/forms/) Sammlung nach Index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Erstellt eine neue`FormEditor` bezogen auf[`HTMLFormElement`](../../aspose.html/htmlformelement/) ausgewählt aus dem Dokument nach id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Erstellt eine neue[`HTMLFormElement`](../../aspose.html/htmlformelement/) und damit verbunden`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) im vom Dokument losgelösten Zustand erstellt wird; Um es an das Dokument anzuhängen, wählen Sie bitte den richtigen Ort und verwenden Sie es[`AppendChild`](../../aspose.html.dom/node/appendchild/) Methode. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Erstellt eine neue[`HTMLElement`](../../aspose.html/htmlelement/) und fügt es am Ende des Formulars hinzu. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Erstellt eine neue[`InputElement`](../inputelement/) und fügt es am Ende des Formulars hinzu. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Erstellt eine neue[`InputElement`](../inputelement/) und fügt es am Ende des Formulars hinzu. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Gibt nicht verwaltete und verwaltete Ressourcen frei. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Diese Methode füllt das gesamte Formular mit den angegebenen Werten. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Gibt das Element nach dem angegebenen Index zurück. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Gibt das Element mit dem angegebenen Namen zurück. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Ruft den Enumerator ab. |

### Siehe auch

* class [FormElement](../formelement/)
* namensraum [Aspose.Html.Forms](../../aspose.html.forms/)
* Montage [Aspose.HTML](../../)


