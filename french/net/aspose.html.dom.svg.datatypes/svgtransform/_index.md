---
title: SVGTransform
second_title: Référence de l'API Aspose.HTML pour .NET
description: SVGTransform est linterface pour lune des transformations de composants dans une SVGTransformList  ainsi un objet SVGTransform correspond à un composant unique par exemple scale ou matrix dans une spécification dattribut transform.
type: docs
weight: 1310
url: /fr/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform est l'interface pour l'une des transformations de composants dans une SVGTransformList ; ainsi, un objet SVGTransform correspond à un composant unique (par exemple, 'scale(…)' ou 'matrix(…)') dans une spécification d'attribut 'transform'.

```csharp
public class SVGTransform : SVGValueType
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle) { get; } | Un attribut de commodité pour SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY. Il contient l'angle spécifié. Pour SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE et SVG_TRANSFORM_SCALE, l'angle sera égal à zéro. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix) { get; } | La matrice qui représente cette transformation. L'objet matrice est actif, ce qui signifie que toute modification apportée à l'objet SVGTransform est immédiatement reflétée dans l'objet matrice et vice versa. Dans le cas où l'objet matrice est modifié directement (c'est-à-dire sans utiliser les méthodes de l'interface SVGTransform elle-même), le type de SVGTransform devient SVG_TRANSFORM_MATRIX. Pour SVG_TRANSFORM_MATRIX, la matrice contient a, b, c, d, e, f valeurs fournies par l'utilisateur. Pour SVG_TRANSFORM_TRANSLATE, e et f représentent les montants de translation (a= 1, b= 0, c= 0 et d = 1). Pour SVG_TRANSFORM_SCALE, a et d représentent les montants d'échelle (b= 0 , c= 0, e= 0 et f = 0). Pour SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY, a, b, c et d représentent la matrice qui résultera en l'inclinaison donnée (e= 0 et f = 0). Pour SVG_TRANSFORM_ROTATE , a, b, c, d, e et f représentent ensemble la matrice qui entraînera la rotation donnée. Lorsque la rotation est autour du point central (0, 0), e et f seront nuls. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type) { get; } | Le type de la valeur tel que spécifié par l'une des constantes SVG_TRANSFORM_* définies sur cette interface. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | Libère les ressources non gérées et - éventuellement - gérées. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Cette méthode est utilisée pour récupérer l'objet ECMAScriptType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix)(SVGMatrix) | Définit le type de transformation sur SVG_TRANSFORM_MATRIX, avec le paramètre matrix définissant la nouvelle transformation. Les valeurs du paramètre matrix sont copiées, le paramètre matrix ne remplace pas SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate)(float, float, float) | Définit le type de transformation sur SVG_TRANSFORM_ROTATE, avec le paramètre angle définissant l'angle de rotation et les paramètres cx et cy définissant le centre de rotation facultatif. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale)(float, float) | Définit le type de transformation sur SVG_TRANSFORM_SCALE, avec les paramètres sx et sy définissant les montants d'échelle. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx)(float) | Définit le type de transformation sur SVG_TRANSFORM_SKEWX, avec le paramètre angle définissant la quantité d'inclinaison. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy)(float) | Définit le type de transformation sur SVG_TRANSFORM_SKEWY, avec le paramètre angle définissant la quantité d'inclinaison. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate)(float, float) | Définit le type de transformation sur SVG_TRANSFORM_TRANSLATE, avec les paramètres tx et ty définissant les quantités de traduction. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix) | Une transformation 'matrice(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate) | Une transformation 'rotation(…)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale) | Une transformation 'échelle(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx) | Une transformation 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy) | Une transformation 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate) | Une transformation 'translate(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown) | Le type d'unité ne fait pas partie des types prédéfinis. Il n'est pas valide de tenter de définir une nouvelle valeur de ce type ou de tenter de basculer une valeur existante vers ce type. |

### Voir également

* class [SVGValueType](../svgvaluetype)
* espace de noms [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* Assemblée [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
