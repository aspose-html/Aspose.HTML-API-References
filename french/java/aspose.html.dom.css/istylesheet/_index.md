---
title: "Interface IStyleSheet"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.IStyleSheet. L'interface `StyleSheet` est l'interface de base abstraite pour tout type de feuille de style. Elle représente une seule feuille de style associée à un document structuré. En HTML, l'interface `StyleSheet` représente soit une feuille de style externe incluse via l'élément HTML LINK, soit un élément STYLE en ligne. En XML, cette interface représente une feuille de style externe incluse via une instruction de traitement de feuille de style. Les feuilles de style CSS implémenteront ensuite l'interface plus spécialisée `CSSStyleSheet`."
type: docs

url: /fr/java/com.aspose.html.dom.css/istylesheet/
---
## IStyleSheet interface

L'interface `StyleSheet` est l'interface de base abstraite pour tout type de feuille de style. Elle représente une seule feuille de style associée à un document structuré. En HTML, l'interface `StyleSheet` représente soit une feuille de style externe, incluse via l'élément HTML LINK, soit un élément STYLE en ligne. En XML, cette interface représente une feuille de style externe, incluse via une instruction de traitement de feuille de style. Les feuilles de style CSS implémenteront ensuite l'interface plus spécialisée [`CSSStyleSheet`](../icssstylesheet/).

Voir également la [CSS Object Model (CSSOM) # StyleSheet Interface Specification](https://drafts.csswg.org/cssom/#the-stylesheet-interface).

```java
public interface IStyleSheet
```

## Propriétés

| Nom | Description |
| --- | --- |
[getDisabled]
[setDisabled] The disabled property of the `StyleSheet` interface determines whether the style sheet is prevented from applying to the document. |
| [getHref](../../com.aspose.html.dom.css/istylesheet/href/) La propriété href de l'interface `StyleSheet` renvoie l'emplacement de la feuille de style. |
| [getMedia](../../com.aspose.html.dom.css/istylesheet/media/) La propriété media de l'interface `StyleSheet` spécifie le média de destination prévu pour les informations de style. C'est un objet en lecture seule, de type tableau, [`MediaList`](../imedialist/), qui peut être supprimé avec deleteMedium() et ajouté avec appendMedium(). |
| [getOwnerNode](../../com.aspose.html.dom.css/istylesheet/ownernode/) Le nœud qui associe cette feuille de style au document. Pour HTML, il peut s'agir de l'élément LINK ou STYLE correspondant. Pour XML, il peut s'agir de l'instruction de traitement de liaison. Pour les feuilles de style incluses par d'autres feuilles de style, la valeur de cet attribut est null. |
| [getParentStyleSheet](../../com.aspose.html.dom.css/istylesheet/parentstylesheet/) Pour les langages de feuilles de style qui supportent le concept d'inclusion de feuille de style, cet attribut représente la feuille de style incluante, si elle existe. Si la feuille de style est une feuille de niveau supérieur, ou si le langage de feuilles de style ne supporte pas l'inclusion, la valeur de cet attribut est null. |
| [getTitle](../../com.aspose.html.dom.css/istylesheet/title/) La propriété title de l'interface `StyleSheet` renvoie le titre consultatif de la feuille de style actuelle. |
| [getType](../../com.aspose.html.dom.css/istylesheet/type/) Cela spécifie le langage de la feuille de style pour cette feuille de style. Le langage de la feuille de style est indiqué comme type de contenu (par ex. "text/css"). |

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[The StyleSheet Interface](https://drafts.csswg.org/cssom/#the-stylesheet-interface) – The official CSSOM definition.

### Voir aussi

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
