---
title: "ICSSValueList.Item"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "ICSSValueList property. Cette méthode est utilisée pour récupérer un CSSValue par indice ordinal. L'ordre dans cette collection représente l'ordre des valeurs dans la propriété de style CSS. Si l'indice est supérieur ou égal au nombre de valeurs dans la liste, cela renvoie null."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

Cette méthode est utilisée pour récupérer un CSSValue par indice ordinal. L'ordre dans cette collection représente l'ordre des valeurs dans la propriété de style CSS. Si l'indice est supérieur ou égal au nombre de valeurs dans la liste, cela renvoie null.

Voir également le [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList).

```java
public CSSValue this[int index] { get; }
```

### Valeur de retour

Le [`CSSValue`](../../cssvalue/) à la position d'index dans le [`CSSValueList`](../../cssvaluelist/), ou null si cet indice n'est pas valide.

### Property Value

L'indice dans la collection.

## Remarques

Cette fonctionnalité a été initialement définie dans la spécification [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style), mais a été abandonnée dans tout effort de normalisation depuis.

Elle a été remplacée par une [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) moderne mais incompatible, qui est désormais sur la voie de la standardisation.

### Voir aussi

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
