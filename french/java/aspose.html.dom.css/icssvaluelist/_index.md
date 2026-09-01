---
title: "Interface ICSSValueList"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.dom.css.ICSSValueList. L'interface CSSValueList dérive de l'interface CSSValue et fournit l'abstraction d'une collection ordonnée de valeurs CSS."
type: docs

url: /fr/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

L'interface CSSValueList dérive de l'interface [`CSSValue`](../cssvalue/) et fournit l'abstraction d'une collection ordonnée de valeurs CSS.

Certaines propriétés autorisent une liste vide dans leur syntaxe. Dans ce cas, ces propriétés utilisent l'identifiant none. Ainsi, une liste vide signifie que la propriété a la valeur none.

Les éléments de la CSSValueList sont accessibles via un indice entier, à partir de 0.

```java
public interface ICSSValueList
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) Cette méthode est utilisée pour récupérer un CSSValue par indice ordinal. L'ordre dans cette collection représente l'ordre des valeurs dans la propriété de style CSS. Si l'indice est supérieur ou égal au nombre de valeurs dans la liste, elle renvoie null. |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) La propriété en lecture seule length de l'interface CSSValueList représente le nombre de CSSValues dans la liste. L'intervalle des valeurs valides des indices est de 0 à length-1 inclus. |

## Remarques

Cette interface faisait partie d'une tentative de création d'un modèle d'objet CSS typé. Cette tentative a été abandonnée, et la plupart des navigateurs ne l'implémentent pas.

Pour atteindre votre objectif, vous pouvez utiliser :

le [CSS Object Model](https://drafts.csswg.org/cssom/) non typé, largement supporté, ou le moderne [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects), moins supporté et considéré comme expérimental.

### Voir aussi

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
