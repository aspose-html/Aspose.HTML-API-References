---
title: "FormEditor‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.forms.FormEditor‑klasse. Deze klasse vertegenwoordigt de editor voor het HTMLFormElement die een eenvoudigere manier biedt voor .net‑ontwikkelaars om HTML‑formulieren te bewerken"
type: docs

url: /nl/java/com.aspose.html.forms/formeditor/
---
## FormEditor class

Deze klasse vertegenwoordigt de editor voor de [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) die een eenvoudigere manier biedt voor .net‑ontwikkelaars om HTML‑formulieren te bewerken.

```java
public class FormEditor : IDisposable, IEnumerable<FormElement>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getAction]
[setAction] Server-side form handler. See the action attribute definition in HTML 4.01. |
| [getCount](../../com.aspose.html.forms/formeditor/count/) Het aantal formulierbesturingselementen in het formulier. |
| [getForm](../../com.aspose.html.forms/formeditor/form/) Het oorspronkelijke [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) dat is gekoppeld aan de huidige instantie van `FormEditor`. |
| [getItem](../../com.aspose.html.forms/formeditor/item/) Retourneert het element op basis van de opgegeven index. (2 indexers) |
[getMethod]
[setMethod] HTTP method [[IETF RFC 2616](http://www.ietf.org/rfc/rfc2616.txt)] used to submit form. See the method attribute definition in HTML 4.01. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_2)(HTMLFormElement) | Maakt een nieuwe `FormEditor` aan op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/). |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create)(HTMLDocument, int) | Maakt een nieuwe `FormEditor` aan op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) geselecteerd uit de [`Forms`](../../com.aspose.html/htmldocument/forms/) collectie op index. |
| static [Create](../../com.aspose.html.forms/formeditor/create/#create_1)(HTMLDocument, String) | Maakt een nieuwe `FormEditor` aan op basis van [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) geselecteerd uit het document op id. |
| static [CreateNew](../../com.aspose.html.forms/formeditor/createnew/)(HTMLDocument) | Maakt een nieuw [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) aan en koppelt het aan `FormEditor`. [`HTMLFormElement`](../../com.aspose.html/htmlformelement/) wordt aangemaakt in een losgekoppelde toestand van het document; om het aan het document toe te voegen, selecteer de juiste locatie en gebruik de [`AppendChild`](../../com.aspose.html.dom/node/appendchild/)‑methode. |
| [Add&lt;T&gt;](../../com.aspose.html.forms/formeditor/add/)(String) | Maakt een nieuw [`HTMLElement`](../../com.aspose.html/htmlelement/) aan en voegt het toe aan het einde van het formulier. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput)(String) | Maakt een nieuw [`InputElement`](../inputelement/) aan en voegt het toe aan het einde van het formulier. |
| [addInput](../../com.aspose.html.forms/formeditor/addinput/#addinput_1)(String, InputElementType) | Maakt een nieuw [`InputElement`](../inputelement/) aan en voegt het toe aan het einde van het formulier. |
| [dispose](../../com.aspose.html.forms/formeditor/dispose/)() | Vrijgeeft onbeheerste en beheerde bronnen. |
| [fill](../../com.aspose.html.forms/formeditor/fill/)(Dictionary&lt;String, String&gt;) |  |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement)(int) | Retourneert het element op basis van de opgegeven index. |
| [GetElement&lt;T&gt;](../../com.aspose.html.forms/formeditor/getelement/#getelement_1)(String) | Retourneert het element op basis van de opgegeven naam. |
| [getEnumerator](../../com.aspose.html.forms/formeditor/getenumerator/)() | Haalt de enumerator op. |

### Zie ook

* class [FormElement](../formelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
