---
title: "ICSS2Properties.UnicodeBidi"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "ICSS2Properties propriété. Les valeurs de cette propriété ont les significations suivantes"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/unicodebidi/
---
## ICSS2Properties.UnicodeBidi property

Les valeurs de cette propriété ont les significations suivantes:

normal - L'élément n'ouvre pas de niveau d'imbrication supplémentaire par rapport à l'algorithme bidirectionnel. Pour les éléments en ligne, le réordonnancement implicite fonctionne à travers les limites des éléments. embed - Si l'élément est en ligne, cette valeur ouvre un niveau d'imbrication supplémentaire par rapport à l'algorithme bidirectionnel. La direction de ce niveau d'imbrication est donnée par la propriété ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction). À l'intérieur de l'élément, le réordonnancement est effectué implicitement. Cela correspond à l'ajout d'un LRE (U+202A; for 'direction: ltr') ou RLE (U+202B; for 'direction: rtl') au début de l'élément et d'un PDF (U+202C) à la fin de l'élément. bidi-override - Si l'élément est en ligne ou un élément de bloc qui ne contient que des éléments en ligne, cela crée une substitution. Cela signifie qu'à l'intérieur de l'élément, le réordonnancement suit strictement la séquence selon la propriété ['direction'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#propdef-direction); la partie implicite de l'algorithme bidirectionnel est ignorée. Cela correspond à l'ajout d'un LRO (U+202D; for 'direction: ltr') ou RLO (U+202E; for 'direction: rtl') au début de l'élément et d'un PDF (U+202C) à la fin de l'élément.

```java
public String UnicodeBidi { get; set; }
```

### Valeur de retour

propriété unicode-bidi

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
