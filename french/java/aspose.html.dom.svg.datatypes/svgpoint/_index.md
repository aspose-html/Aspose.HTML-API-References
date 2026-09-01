---
title: "SVGPoint classe"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint classe. De nombreuses interfaces du DOM SVG font référence à des objets de la classe SVGPoint. Un SVGPoint est une paire de coordonnées x y. Lorsqu’il est utilisé dans des opérations matricielles, un SVGPoint est traité comme un vecteur de la forme x y 1. Si un objet SVGRect est désigné comme lecture seule, toute tentative d’affectation à l’un de ses attributs entraînera le lancement d’une exception."
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

De nombreuses interfaces du DOM SVG font référence à des objets de la classe SVGPoint. Un SVGPoint est une paire de coordonnées (x, y). Lorsqu'il est utilisé dans des opérations matricielles, un SVGPoint est traité comme un vecteur de la forme : [x] [y] [1]. Si un objet SVGRect est désigné comme lecture seule, toute tentative d'affectation à l'un de ses attributs entraînera le lancement d'une exception.

```java
public class SVGPoint : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | La coordonnée X. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | La coordonnée Y. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Applique une transformation matricielle 2x3 sur cet objet SVGPoint et renvoie un nouvel objet SVGPoint transformé : newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Renvoie une chaîne qui représente cette instance. |

### Voir aussi

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
