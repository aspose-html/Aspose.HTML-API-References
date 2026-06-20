---
title: "IViewCSS.GetComputedStyle"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IViewCSS. La méthode IViewCSS.getComputedStyle renvoie un objet contenant les valeurs de toutes les propriétés CSS d'un élément après l'application des feuilles de style actives et la résolution de toute computation de base que ces valeurs peuvent contenir."
type: docs

url: /fr/java/com.aspose.html.dom.css/iviewcss/getcomputedstyle/
---
## GetComputedStyle(Element) {#getcomputedstyle}

La méthode IViewCSS.getComputedStyle() renvoie un objet contenant les valeurs de toutes les propriétés CSS d'un élément, après l'application des feuilles de style actives et la résolution de toute computation de base que ces valeurs peuvent contenir.

Les valeurs individuelles des propriétés CSS sont accessibles via les API fournies par l'objet, ou par indexation avec les noms de propriétés CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| element | Element | L'[`Element`](../../../com.aspose.html.dom/element/) pour lequel obtenir le style calculé. Ce paramètre ne peut pas être null. |

### Valeur de retour

Le style retourné est un objet [`CSSStyleDeclaration`](../../icssstyledeclaration/) en direct, qui se met à jour automatiquement lorsque les styles de l'élément sont modifiés.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | Si l'objet passé n'est pas un Element ou que pseudoElt n'est pas un sélecteur de pseudo-élément valide. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Voir aussi

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)

---

## GetComputedStyle(Element, String) {#getcomputedstyle_1}

La méthode IViewCSS.getComputedStyle() renvoie un objet contenant les valeurs de toutes les propriétés CSS d'un élément, après l'application des feuilles de style actives et la résolution de toute computation de base que ces valeurs peuvent contenir.

Les valeurs individuelles des propriétés CSS sont accessibles via les API fournies par l'objet, ou par indexation avec les noms de propriétés CSS.

```java
public ICSSStyleDeclaration GetComputedStyle(Element element, String pseudoElement)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| element | Element | L'[`Element`](../../../com.aspose.html.dom/element/) pour lequel obtenir le style calculé. Ce paramètre ne peut pas être null. |
| pseudoElement | String | Une chaîne spécifiant le pseudo-élément à faire correspondre. Omis (ou null) pour les éléments réels. |

### Valeur de retour

Le style retourné est un objet [`CSSStyleDeclaration`](../../icssstyledeclaration/) en direct, qui se met à jour automatiquement lorsque les styles de l'élément sont modifiés.

### Exceptions

| exception | condition |
| --- | --- |
| TypeError | Si l'objet passé n'est pas un Element ou que pseudoElt n'est pas un sélecteur de pseudo-élément valide. |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-window-getcomputedstyle](https://drafts.csswg.org/cssom/#dom-window-getcomputedstyle) – The CSSOM definition.

### Voir aussi

* interface [ICSSStyleDeclaration](../../icssstyledeclaration/)
* class [Element](../../../com.aspose.html.dom/element/)
* interface [IViewCSS](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
