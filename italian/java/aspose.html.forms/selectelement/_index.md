---
title: "Classe SelectElement"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Classe com.aspose.html.forms.SelectElement. SelectElement rappresenta un wrapper associato a HTMLSelectElement."
type: docs

url: /it/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

Il SelectElement rappresenta un wrapper associato all'HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Ottiene il tipo dell'elemento. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Rappresenta l'attributo Id dell'elemento input. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Rappresenta l'attributo name dell'elemento input. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Restituisce un elenco di opzioni |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Restituisce un elenco di opzioni selezionate |
| [getType](../../com.aspose.html.forms/selectelement/type/) Il tipo di questo controllo del modulo. È la stringa "select-multiple" quando l'attributo multiple è `true` e la stringa "select-one" quando è `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Durante il recupero, deve restituire il valore del primo elemento option nell'elenco delle opzioni in ordine gerarchico che ha la proprietà selected impostata su true, se presente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Questo metodo consente di selezionare più opzioni tramite i loro indici. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Questo metodo consente di selezionare più opzioni tramite i loro valori. |

### Vedi anche

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
