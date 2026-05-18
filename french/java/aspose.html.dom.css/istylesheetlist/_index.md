---
title: "Interface IStyleSheetList"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.IStyleSheetList. L'interface StyleSheetList représente une liste d'objets CSSStyleSheet. Une instance de cet objet peut être renvoyée par Document.styleSheets."
type: docs

url: /fr/java/com.aspose.html.dom.css/istylesheetlist/
---
## IStyleSheetList interface

L'interface StyleSheetList représente une liste d'objets [`CSSStyleSheet`](../icssstylesheet/). Une instance de cet objet peut être renvoyée par [`Document.styleSheets`](../../com.aspose.html.dom/document/stylesheets/).

Les indices de propriétés pris en charge par l'objet sont les nombres compris entre zéro et un de moins que le nombre de feuilles de style CSS représentées par la collection. S'il n'existe aucune feuille de style CSS de ce type, il n'y a aucun indice de propriété pris en charge.

```java
public interface IStyleSheetList : IEnumerable<ICSSStyleSheet>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/istylesheetlist/item/) La méthode item(index) doit renvoyer le [`CSS style sheet`](../icssstylesheet/) d'indice index dans la collection. S'il n'existe aucun objet d'indice index dans la collection, la méthode doit renvoyer null. |
| [getLength](../../com.aspose.html.dom.css/istylesheetlist/length/) L'attribut length doit renvoyer le nombre de feuilles de style CSS représentées par la collection. L'intervalle des indices valides des feuilles de style enfants est de 0 à length-1 inclus. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # stylesheetlist](https://drafts.csswg.org/cssom/#stylesheetlist) – The CSSOM definition.

### Voir aussi

* interface [ICSSStyleSheet](../icssstylesheet/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
