---
title: "IStyleSheet.ParentStyleSheet"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété IStyleSheet. Pour les langages de feuilles de style qui prennent en charge le concept d’inclusion de feuilles de style, cet attribut représente la feuille de style incluante si elle existe. Si la feuille de style est une feuille de style de niveau supérieur ou si le langage de feuilles de style ne prend pas en charge l’inclusion, la valeur de cet attribut est null."
type: docs

url: /fr/java/com.aspose.html.dom.css/istylesheet/parentstylesheet/
---
## IStyleSheet.ParentStyleSheet property

Pour les langages de feuilles de style qui prennent en charge le concept d’inclusion de feuilles de style, cet attribut représente la feuille de style incluante, si elle existe. Si la feuille de style est une feuille de style de niveau supérieur, ou si le langage de feuilles de style ne prend pas en charge l’inclusion, la valeur de cet attribut est null.

```java
public IStyleSheet ParentStyleSheet { get; }
```

### Property Value

L'attribut parentStyleSheet doit renvoyer le [`CSS style sheet`](../../icssstylesheet/) parent.

## Remarques

Cette propriété renvoie null si la feuille de style actuelle est une feuille de style de niveau supérieur ou si l’inclusion de feuilles de style n’est pas prise en charge.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-parentstylesheet](https://drafts.csswg.org/cssom/#dom-stylesheet-parentstylesheet) – The CSSOM definition.

### Voir aussi

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
