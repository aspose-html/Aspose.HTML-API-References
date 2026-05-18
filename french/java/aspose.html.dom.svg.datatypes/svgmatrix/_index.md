---
title: "Classe SVGMatrix"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.svg.datatypes.SVGMatrix. De nombreuses opérations graphiques SVG utilisent des matrices 2x3 de la forme a c e b d f qui, lorsqu'elles sont développées en une matrice 3x3 aux fins de l'arithmétique matricielle, deviennent a c e b d f 0 0 1"
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

De nombreuses opérations graphiques de SVG utilisent des matrices 2x3 de la forme : [a c e] [b d f] qui, lorsqu'elles sont étendues en une matrice 3x3 aux fins de l'arithmétique matricielle, deviennent : [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Le composant A de la matrice. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | Le composant B de la matrice. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Le composant C de la matrice. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Le composant D de la matrice. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Le composant E de la matrice. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | Le composant F de la matrice. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Effectue une multiplication matricielle. Cette matrice est post-multiplée par une autre matrice, renvoyant la nouvelle matrice résultante. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplie une transformation de rotation sur la matrice actuelle et renvoie la matrice résultante. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplie une transformation d'échelle uniforme sur la matrice actuelle et renvoie la matrice résultante. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplie une transformation d'échelle non uniforme sur la matrice actuelle et renvoie la matrice résultante. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Effectue une post‑multiplication d’une transformation skewX sur la matrice actuelle et renvoie la matrice résultante. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Effectue une post‑multiplication d’une transformation skewY sur la matrice actuelle et renvoie la matrice résultante. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Renvoie une chaîne qui représente cette instance. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Effectue une post‑multiplication d’une transformation de translation sur la matrice actuelle et renvoie la matrice résultante. |

### Voir aussi

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
