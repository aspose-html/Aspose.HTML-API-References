---
title: "Classe SelectElement"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.forms.SelectElement. Le SelectElement représente un wrapper associé à l'HTMLSelectElement."
type: docs

url: /fr/java/com.aspose.html.forms/selectelement/
---
## SelectElement class

Le SelectElement représente un wrapper associé à l’HTMLSelectElement.

```java
public class SelectElement : FormElement<HTMLSelectElement>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getElementType](../../com.aspose.html.forms/formelement/elementtype/) Obtient le type de l'élément. |
| [getHtmlElement](../../com.aspose.html.forms/formelement-1/htmlelement/) |
| [id](../../com.aspose.html.forms/selectelement/id/) { get; set; } | Représente l'attribut Id de l'élément d'entrée. |
[getMultiple]
[setMultiple] If true, multiple `OPTION` elements may be selected in this `SELECT`. See the multiple attribute definition in HTML 4.01. |
| [name](../../com.aspose.html.forms/selectelement/name/) { get; set; } | Représente l'attribut name de l'élément d'entrée. |
| [getOptions](../../com.aspose.html.forms/selectelement/options/) Renvoie une liste d'options |
| [getSelectedOptions](../../com.aspose.html.forms/selectelement/selectedoptions/) Renvoie une liste d'options sélectionnées |
| [getType](../../com.aspose.html.forms/selectelement/type/) Le type de ce contrôle de formulaire. C'est la chaîne "select-multiple" lorsque l'attribut multiple est `true` et la chaîne "select-one" lorsque `false`. |
| [value](../../com.aspose.html.forms/selectelement/value/) { get; set; } | Lors de l'obtention, doit renvoyer la valeur du premier élément option dans la liste d'options selon l'ordre de l'arbre qui a sa sélection définie sur true, le cas échéant. |

## Méthodes

| Nom | Description |
| --- | --- |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems)(params int[]) | Cette méthode permet de sélectionner plusieurs options par leurs index. |
| [selectItems](../../com.aspose.html.forms/selectelement/selectitems/#selectitems_1)(params String[]) | Cette méthode permet de sélectionner plusieurs options par leurs valeurs. |

### Voir aussi

* class [FormElement&lt;T&gt;](../formelement-1/)
* class [HTMLSelectElement](../../com.aspose.html/htmlselectelement/)
* package [com.aspose.html.forms](../../com.aspose.html.forms/)
* package [Aspose.HTML](../../)
