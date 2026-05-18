---
title: "ICSS2Properties.VerticalAlign"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété ICSS2Properties. Cette propriété affecte le positionnement vertical à l'intérieur d'une boîte de ligne des boîtes générées par un élément de niveau en ligne. Les valeurs suivantes n'ont de sens qu'en référence à un élément parent de niveau en ligne ou à un élément parent de niveau bloc si cet élément génère des boîtes en ligne anonymes ; elles n'ont aucun effet s'il n'existe aucun parent de ce type"
type: docs

url: /fr/java/com.aspose.html.dom.css/icss2properties/verticalalign/
---
## ICSS2Properties.VerticalAlign property

Cette propriété affecte le positionnement vertical à l'intérieur d'une boîte de ligne des boîtes générées par un élément de niveau en ligne. Les valeurs suivantes n'ont de sens qu'en référence à un élément parent de niveau en ligne ou à un élément parent de niveau bloc, si cet élément génère [boîtes en ligne anonymes](https://www.w3.org/TR/1998/REC-CSS2-19980512/visuren.html#anonymous); elles n'ont aucun effet s'il n'existe aucun parent de ce type.

Remarque. Les valeurs de cette propriété ont des significations légèrement différentes dans le contexte des tableaux. Veuillez consulter la section sur les [algorithmes de hauteur des tables](https://www.w3.org/TR/1998/REC-CSS2-19980512/tables.html#height-layout) pour plus de détails. baseline - Aligne la ligne de base de la boîte avec la ligne de base de la boîte parent. Si la boîte n'a pas de ligne de base, aligne le bas de la boîte avec la ligne de base du parent. middle - Aligne le point médian vertical de la boîte avec la ligne de base de la boîte parent plus la moitié de la hauteur x du parent. sub - Abaisse la ligne de base de la boîte à la position appropriée pour les indices de la boîte du parent. (Cette valeur n'affecte pas la taille de police du texte de l'élément.) super - Élève la ligne de base de la boîte à la position appropriée pour les exposants de la boîte du parent. (Cette valeur n'affecte pas la taille de police du texte de l'élément.) text-top - Aligne le haut de la boîte avec le haut de la police de l'élément parent. text-bottom - Aligne le bas de la boîte avec le bas de la police de l'élément parent. '[percentage](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-percentage)' - Monte (valeur positive) ou descend (valeur négative) la boîte de cette distance (un pourcentage de la valeur de ['line-height'](https://www.w3.org/TR/1998/REC-CSS2-19980512/visudet.html#propdef-line-height)). La valeur '0%' équivaut à 'baseline'. '[length](https://www.w3.org/TR/1998/REC-CSS2-19980512/syndata.html#value-def-length)' - Monte (valeur positive) ou descend (valeur négative) la boîte de cette distance. La valeur '0cm' équivaut à 'baseline'. top - Aligne le haut de la boîte avec le haut de la boîte de ligne. bottom - Aligne le bas de la boîte avec le bas de la boîte de ligne.

```java
public String VerticalAlign { get; set; }
```

### Valeur de retour

propriété vertical-align

### Voir aussi

* interface [ICSS2Properties](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
