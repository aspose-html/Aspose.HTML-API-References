---
title: Class FormEditor
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Forms.FormEditor klas. Deze klasse vertegenwoordigt de editor over deHTMLFormElement dat creëert een gemakkelijkere manier voor .netontwikkelaars om de htmlformulieren te bewerken.
type: docs
weight: 2930
url: /nl/net/aspose.html.forms/formeditor/
---
## FormEditor class

Deze klasse vertegenwoordigt de editor over de[`HTMLFormElement`](../../aspose.html/htmlformelement/) dat creëert een gemakkelijkere manier voor .net-ontwikkelaars om de html-formulieren te bewerken.

```csharp
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Action](../../aspose.html.forms/formeditor/action/) { get; set; } | Formulierhandler aan de serverzijde. Zie de definitie van het actiekenmerk in HTML 4.01. |
| [Count](../../aspose.html.forms/formeditor/count/) { get; } | Het aantal formulierbesturingselementen in het formulier. |
| [Form](../../aspose.html.forms/formeditor/form/) { get; } | Het origineel[`HTMLFormElement`](../../aspose.html/htmlformelement/) dat is gekoppeld aan het huidige exemplaar van`FormEditor` . |
| [Item](../../aspose.html.forms/formeditor/item/) { get; } | Retourneert het element door gespecificeerde index. (2 indexers) |
| [Method](../../aspose.html.forms/formeditor/method/) { get; set; } | HTTP-methode [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt) gebruikt om formulier in te dienen. Zie de kenmerkdefinitie van de methode in HTML 4.01. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Maakt een nieuw`FormEditor` gebaseerd op[`HTMLFormElement`](../../aspose.html/htmlformelement/) . |
| static [Create](../../aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Maakt een nieuw`FormEditor` gebaseerd op[`HTMLFormElement`](../../aspose.html/htmlformelement/) geselecteerd uit de[`Forms`](../../aspose.html/htmldocument/forms/) collectie door index. |
| static [Create](../../aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, string) | Maakt een nieuw`FormEditor` gebaseerd op[`HTMLFormElement`](../../aspose.html/htmlformelement/) geselecteerd uit het document door id. |
| static [CreateNew](../../aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Maakt een nieuw[`HTMLFormElement`](../../aspose.html/htmlformelement/) en daarmee in verband gebracht`FormEditor` .[`HTMLFormElement`](../../aspose.html/htmlformelement/) wordt gemaakt in de losgekoppelde staat van het document; Selecteer de juiste locatie en gebruik om het aan het document te bevestigen[`AppendChild`](../../aspose.html.dom/node/appendchild/) methode. |
| [Add&lt;T&gt;](../../aspose.html.forms/formeditor/add/)(string) | Maakt een nieuw[`HTMLElement`](../../aspose.html/htmlelement/) en voegt het toe aan het einde van het formulier. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput)(string) | Maakt een nieuw[`InputElement`](../inputelement/) en voegt het toe aan het einde van het formulier. |
| [AddInput](../../aspose.html.forms/formeditor/addinput/#addinput_1)(string, InputElementType) | Maakt een nieuw[`InputElement`](../inputelement/) en voegt het toe aan het einde van het formulier. |
| [Dispose](../../aspose.html.forms/formeditor/dispose/)() | Geeft onbeheerde en beheerde bronnen vrij. |
| [Fill](../../aspose.html.forms/formeditor/fill/)(Dictionary&lt;string, string&gt;) | Deze methode vult het hele formulier met de opgegeven waarden. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement)(int) | Retourneert het element door gespecificeerde index. |
| [GetElement&lt;T&gt;](../../aspose.html.forms/formeditor/getelement/#getelement_1)(string) | Retourneert het element met opgegeven naam. |
| [GetEnumerator](../../aspose.html.forms/formeditor/getenumerator/)() | Haalt de teller op. |

### Zie ook

* class [FormElement](../formelement/)
* naamruimte [Aspose.Html.Forms](../../aspose.html.forms/)
* montage [Aspose.HTML](../../)


