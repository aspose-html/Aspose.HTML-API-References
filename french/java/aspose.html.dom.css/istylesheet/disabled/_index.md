---
title: "IStyleSheet.Disabled"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété IStyleSheet. La propriété disabled de l'interface StyleSheet détermine si la feuille de style est empêchée de s'appliquer au document."
type: docs

url: /fr/java/com.aspose.html.dom.css/istylesheet/disabled/
---
## IStyleSheet.Disabled property

La propriété disabled de l'interface [`StyleSheet`](../) détermine si la feuille de style est empêchée de s'appliquer au document.

Une feuille de style peut être désactivée en définissant manuellement cette propriété à true ou si c'est une feuille de style alternative inactive. Notez que disabled == false ne garantit pas que la feuille de style soit appliquée (elle pourrait être retirée du document, par exemple).

Modifier cet attribut peut entraîner une nouvelle résolution du style pour le document. Une feuille de style ne s'applique que si une définition de média appropriée est présente et que l'attribut disabled est false. Ainsi, si le média ne s'applique pas à l'agent utilisateur actuel, l'attribut disabled est ignoré.

```java
public bool Disabled { get; set; }
```

### Valeur de retour

L'attribut disabled, lors de la lecture, doit renvoyer true si le drapeau disabled est activé, ou false sinon. Lors de l'écriture, l'attribut disabled doit activer le drapeau disabled si la nouvelle valeur est true, ou le désactiver sinon.

### Property Value

L'attribut disabled, lors de la lecture, doit renvoyer true si le drapeau disabled est activé, ou false sinon. Lors de l'écriture, l'attribut disabled doit activer le drapeau disabled si la nouvelle valeur est true, ou le désactiver sinon.

## Remarques

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-disabled](https://drafts.csswg.org/cssom/#dom-stylesheet-disabled) – The CSSOM definition.

### Voir aussi

* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
