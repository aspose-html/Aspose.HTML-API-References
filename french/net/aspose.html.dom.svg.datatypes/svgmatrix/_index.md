---
title: Class SVGMatrix
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Dom.Svg.DataTypes.SVGMatrix classe. De nombreuses opérations graphiques de SVG utilisent des matrices 2x3 de la forme  ace bdf qui lorsquelles sont développées en une matrice 3x3 à des fins darithmétique matricielle deviennent  ace bdf 0 0 1
type: docs
weight: 1220
url: /fr/net/aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

De nombreuses opérations graphiques de SVG utilisent des matrices 2x3 de la forme : [ace] [bdf] qui, lorsqu'elles sont développées en une matrice 3x3 à des fins d'arithmétique matricielle, deviennent : [ace] [bdf] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Propriétés

| Nom | La description |
| --- | --- |
| [A](../../aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | Le composant A de la matrice. |
| [B](../../aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | La composante B de la matrice. |
| [C](../../aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | Le composant C de la matrice. |
| [D](../../aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | Le composant D de la matrice. |
| [E](../../aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | Le composant E de la matrice. |
| [F](../../aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | La composante F de la matrice. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [Multiply](../../aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Effectue une multiplication matricielle. Cette matrice est post-multipliée par une autre matrice, renvoyant la nouvelle matrice résultante. |
| [Rotate](../../aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplie une transformation de rotation sur la matrice actuelle et renvoie la matrice résultante. |
| [Scale](../../aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplie une transformation d'échelle uniforme sur la matrice actuelle et renvoie la matrice résultante. |
| [ScaleNonUniform](../../aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplie une transformation d'échelle non uniforme sur la matrice actuelle et renvoie la matrice résultante. |
| [SkewX](../../aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Post-multiplie une transformation skewX sur la matrice actuelle et renvoie la matrice résultante. |
| [SkewY](../../aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Post-multiplie une transformation asymétrique sur la matrice actuelle et renvoie la matrice résultante. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgmatrix/tostring/)() | Renvoie unString qui représente cette instance. |
| [Translate](../../aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Post-multiplie une transformation de translation sur la matrice actuelle et renvoie la matrice résultante. |

### Voir également

* class [SVGValueType](../svgvaluetype/)
* espace de noms [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes/)
* Assemblée [Aspose.HTML](../../)


