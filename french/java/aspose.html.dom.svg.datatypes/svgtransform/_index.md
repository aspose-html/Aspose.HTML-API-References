---
title: "Classe SVGTransform"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "classe com.aspose.html.dom.svg.datatypes.SVGTransform. SVGTransform est l'interface d'une des transformations composantes au sein d'un SVGTransformList, ainsi un objet SVGTransform correspond à un seul composant, par ex. scale ou matrix, dans une spécification d'attribut de transformation"
type: docs

url: /fr/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform est l'interface d'une des transformations composantes au sein d'une SVGTransformList ; ainsi, un objet SVGTransform correspond à une composante unique (par ex., 'scale(…)' ou 'matrix(…)') dans une spécification d'attribut ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Un attribut de commodité pour SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY. Il contient l'angle qui a été spécifié. Pour SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE et SVG_TRANSFORM_SCALE, l'angle sera zéro. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) La matrice qui représente cette transformation. L'objet matrice est dynamique, ce qui signifie que toute modification apportée à l'objet SVGTransform est immédiatement reflétée dans l'objet matrice et vice‑versa. Si l'objet matrice est modifié directement (c.-à-d. sans utiliser les méthodes de l'interface SVGTransform elle‑même), alors le type de SVGTransform passe à SVG_TRANSFORM_MATRIX. Pour SVG_TRANSFORM_MATRIX, la matrice contient les valeurs a, b, c, d, e, f fournies par l'utilisateur. Pour SVG_TRANSFORM_TRANSLATE, e et f représentent les quantités de translation (a= 1, b= 0, c= 0 et d = 1). Pour SVG_TRANSFORM_SCALE, a et d représentent les quantités d'échelle (b= 0, c= 0, e= 0 et f = 0). Pour SVG_TRANSFORM_SKEWX et SVG_TRANSFORM_SKEWY, a, b, c et d représentent la matrice qui produira le cisaillement donné (e= 0 et f = 0). Pour SVG_TRANSFORM_ROTATE, a, b, c, d, e et f ensemble représentent la matrice qui produira la rotation donnée. Lorsque la rotation est autour du point central (0, 0), e et f seront zéro. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) Le type de la valeur tel que spécifié par l'une des constantes SVG_TRANSFORM_* définies sur cette interface. |

## Méthodes

| Nom | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libère les ressources non gérées et - éventuellement - gérées. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Cette méthode est utilisée pour récupérer l'objet ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Définit le type de transformation sur SVG_TRANSFORM_MATRIX, avec le paramètre matrix définissant la nouvelle transformation. Les valeurs du paramètre matrix sont copiées, le paramètre matrix ne remplace pas SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Définit le type de transformation sur SVG_TRANSFORM_ROTATE, avec le paramètre angle définissant l'angle de rotation et les paramètres cx et cy définissant le centre de rotation optionnel. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Définit le type de transformation sur SVG_TRANSFORM_SCALE, avec les paramètres sx et sy définissant les quantités d'échelle. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Définit le type de transformation sur SVG_TRANSFORM_SKEWX, avec le paramètre angle définissant la quantité de cisaillement. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Définit le type de transformation sur SVG_TRANSFORM_SKEWY, avec le paramètre angle définissant la quantité de cisaillement. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Définit le type de transformation sur SVG_TRANSFORM_TRANSLATE, avec les paramètres tx et ty définissant les quantités de translation. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Une transformation 'matrix(…)' |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Une transformation 'rotate(…)' |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Une transformation 'scale(…)'. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Une transformation 'skewX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Une transformation 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Une transformation 'translate(…)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | Le type d'unité n'est pas l'un des types prédéfinis. Il est invalide de tenter de définir une nouvelle valeur de ce type ou d'essayer de basculer une valeur existante vers ce type. |

### Voir aussi

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
