---
title: "IStyleSheet.OwnerNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété IStyleSheet. Le nœud qui associe cette feuille de style au document. Pour HTML, il peut s'agir de l'élément LINK ou STYLE correspondant. Pour XML, il peut s'agir de l'instruction de traitement de liaison. Pour les feuilles de style incluses par d'autres feuilles de style, la valeur de cet attribut est null."
type: docs

url: /fr/java/com.aspose.html.dom.css/istylesheet/ownernode/
---
## IStyleSheet.OwnerNode property

Le nœud qui associe cette feuille de style au document. Pour HTML, il peut s'agir de l'élément LINK ou STYLE correspondant. Pour XML, il peut s'agir de l'instruction de traitement de liaison. Pour les feuilles de style incluses par d'autres feuilles de style, la valeur de cet attribut est null.

```java
public Node OwnerNode { get; }
```

### Property Value

L'attribut ownerNode doit renvoyer le nœud propriétaire.

## Remarques

Pour les feuilles de style incluses par d'autres feuilles de style, comme avec @import, la valeur de cette propriété est null.

[CSSOM](https://drafts.csswg.org/cssom/) defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.

Référence

[CSS Working Group](https://wiki.csswg.org/) - The CSS Working Group is the W3C working group chartered to develop Cascading Style Sheets (CSS).[CSS Object Model (CSSOM)](https://drafts.csswg.org/cssom/) - CSSOM defines APIs (including generic parsing and serialization rules) for Media Queries, Selectors, and of course CSS itself.[CSS Object Model (CSSOM) # dom-stylesheet-ownernode](https://drafts.csswg.org/cssom/#dom-stylesheet-ownernode) – The CSSOM definition.

### Voir aussi

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IStyleSheet](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
