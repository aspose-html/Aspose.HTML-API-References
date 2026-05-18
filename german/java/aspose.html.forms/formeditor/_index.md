---
title: "FormEditor-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.forms.FormEditor Klasse. Diese Klasse stellt den Editor für das HTMLFormElement dar, der .net-Entwicklern eine einfachere Möglichkeit bietet, HTML-Formulare zu bearbeiten."
type: docs

url: /de/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Diese Klasse stellt den Editor für das [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) dar, der .net-Entwicklern eine einfachere Möglichkeit bietet, HTML-Formulare zu bearbeiten.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Die Anzahl der Formularelemente im Formular. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Das ursprüngliche [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), das mit der aktuellen Instanz von `FormEditor` verknüpft ist. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Gibt das Element anhand des angegebenen Index zurück. (2 Indexer) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Erstellt einen neuen `FormEditor` basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Erstellt einen neuen `FormEditor` basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), das aus der [`Forms`](../../com.aspose.html/htmldocument/forms/) Sammlung nach Index ausgewählt wurde. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Erstellt einen neuen `FormEditor` basierend auf [`HTMLFormElement`](../../com.aspose.html/htmlformelement/), das im Dokument nach ID ausgewählt wurde. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Erstellt ein neues [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) und verknüpft es mit `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) wird im vom Dokument getrennten Zustand erstellt; um es an das Dokument anzuhängen, wählen Sie bitte die richtige Position und verwenden Sie die [`AppendChild`](../../com.aspose.html.dom/node/appendchild/) Methode. |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Erstellt ein neues [`HTMLElement`](../../com.aspose.html/htmlelement/) und fügt es am Ende des Formulars hinzu. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Erstellt ein neues [`InputElement`](../inputelement/) und fügt es am Ende des Formulars hinzu. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Erstellt ein neues [`InputElement`](../inputelement/) und fügt es am Ende des Formulars hinzu. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Gibt nicht verwaltete und verwaltete Ressourcen frei. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Gibt das Element anhand des angegebenen Index zurück. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Gibt das Element anhand des angegebenen Namens zurück. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Liest den Enumerator. |

### Siehe auch

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
