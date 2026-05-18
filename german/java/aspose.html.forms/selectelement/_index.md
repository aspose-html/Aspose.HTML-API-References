---
title: "SelectElement-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.forms.SelectElement‑Klasse. Das SelectElement stellt einen Wrapper dar, der mit dem HTMLSelectElement verknüpft ist."
type: docs

url: /de/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

Das SelectElement stellt einen Wrapper dar, der mit dem HTMLSelectElement verknüpft ist.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Gibt den Typ des Elements zurück. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Stellt das Id-Attribut des Eingabeelements dar. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Stellt das name-Attribut des Eingabeelements dar. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Gibt eine Liste von Optionen zurück |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Gibt eine Liste der ausgewählten Optionen zurück |
| [getType](../../com.aspose.html.forms/selectelement/type/) Der Typ dieses Formularelements. Dies ist die Zeichenkette "select-multiple", wenn das Attribut multiple `true` ist und die Zeichenkette "select-one", wenn `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Beim Abrufen muss der Wert des ersten Options-Elements in der Optionsliste in Baumreihenfolge zurückgegeben werden, das auf `true` gesetzt ist, falls vorhanden. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Diese Methode ermöglicht das Auswählen mehrerer Optionen anhand ihrer Indizes. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Diese Methode ermöglicht das Auswählen mehrerer Optionen anhand ihrer Werte. |

### Siehe auch

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
