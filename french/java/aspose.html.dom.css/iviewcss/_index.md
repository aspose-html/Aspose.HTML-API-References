---
title: "Interface IViewCSS"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.IViewCSS. L'interface IViewCSS représente une extension de l'objet Window qui donne accès aux valeurs de toutes les propriétés CSS d'un élément."
type: docs

url: /fr/java/com.aspose.html.dom.css/iviewcss/
---
## IViewCSS interface

L'interface IViewCSS représente une extension de l'objet Window qui donne accès aux valeurs de toutes les propriétés CSS d'un élément.

Le style CSS d'un élément donné peut être obtenu en utilisant la méthode IViewCSS.GetComputedStyle().

```java
public interface IViewCSS : IAbstractView
```

## Méthodes

| Nom | Description |
| --- | --- |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle)(Element) | La méthode IViewCSS.getComputedStyle() renvoie un objet contenant les valeurs de toutes les propriétés CSS d'un élément, après l'application des feuilles de style actives et la résolution de toute computation de base que ces valeurs peuvent contenir. |
| [getComputedStyle](../../com.aspose.html.dom.css/iviewcss/getcomputedstyle/#getcomputedstyle_1)(Element, String) | La méthode IViewCSS.getComputedStyle() renvoie un objet contenant les valeurs de toutes les propriétés CSS d'un élément, après l'application des feuilles de style actives et la résolution de toute computation de base que ces valeurs peuvent contenir. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

### Voir aussi

* interface [IAbstractView](../../com.aspose.html.dom.views/iabstractview/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
