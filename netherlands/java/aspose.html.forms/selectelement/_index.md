---
title: "SelectElement‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.forms.SelectElement‑klasse. De SelectElement vertegenwoordigt een wrapper die is gekoppeld aan de HTMLSelectElement."
type: docs

url: /nl/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

De SelectElement vertegenwoordigt een wrapper die geassocieerd is met de HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Haalt het type van het element op. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Stelt het Id-attribuut van het invoerelement voor. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Stelt het name-attribuut van het invoerelement voor. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Retourneert een lijst met opties |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Retourneert een lijst met geselecteerde opties |
| [getType](../../com.aspose.html.forms/selectelement/type/) Het type van deze formulierelement. Dit is de string "select-multiple" wanneer het multiple-attribuut `true` is en de string "select-one" wanneer `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Bij ophalen moet de waarde van het eerste optie‑element in de lijst met opties in boomvolgorde worden geretourneerd waarvan de geselecteerd‑status op true staat, indien aanwezig. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Deze methode maakt het mogelijk om meerdere opties te selecteren op basis van hun indexen. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Deze methode maakt het mogelijk om meerdere opties te selecteren op basis van hun waarden. |

### Zie ook

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
