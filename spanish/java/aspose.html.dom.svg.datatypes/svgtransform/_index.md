---
title: "Clase SVGTransform"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.svg.datatypes.SVGTransform. SVGTransform es la interfaz para una de las transformaciones componentes dentro de una SVGTransformList, por lo que un objeto SVGTransform corresponde a un solo componente, p. ej., escala o matriz dentro de la especificación de un atributo de transformación"
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform es la interfaz para una de las transformaciones componentes dentro de un SVGTransformList; por lo tanto, un objeto SVGTransform corresponde a un único componente (p. ej., 'scale(…)' o 'matrix(…)') dentro de una especificación del atributo ‘transform’.

```java
public class SVGTransform : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) Un atributo de conveniencia para SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY. Contiene el ángulo especificado. Para SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE y SVG_TRANSFORM_SCALE, el ángulo será cero. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) La matriz que representa esta transformación. El objeto matriz es dinámico, lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto matriz y viceversa. En caso de que el objeto matriz se modifique directamente (es decir, sin usar los métodos de la propia interfaz SVGTransform), el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX, la matriz contiene los valores a, b, c, d, e, f proporcionados por el usuario. Para SVG_TRANSFORM_TRANSLATE, e y f representan las cantidades de traslación (a=1, b=0, c=0 y d=1). Para SVG_TRANSFORM_SCALE, a y d representan las cantidades de escala (b=0, c=0, e=0 y f=0). Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY, a, b, c y d representan la matriz que producirá la inclinación dada (e=0 y f=0). Para SVG_TRANSFORM_ROTATE, a, b, c, d, e y f juntos representan la matriz que producirá la rotación dada. Cuando la rotación es alrededor del punto central (0, 0), e y f serán cero. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) El tipo del valor según lo especificado por una de las constantes SVG_TRANSFORM_* definidas en esta interfaz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Establece el tipo de transformación a SVG_TRANSFORM_MATRIX, con el parámetro matrix que define la nueva transformación. Los valores del parámetro matrix se copian; el parámetro matrix no reemplaza a SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Establece el tipo de transformación a SVG_TRANSFORM_ROTATE, con el parámetro angle que define el ángulo de rotación y los parámetros cx y cy que definen el centro de rotación opcional. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Establece el tipo de transformación a SVG_TRANSFORM_SCALE, con los parámetros sx y sy que definen las cantidades de escala. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Establece el tipo de transformación a SVG_TRANSFORM_SKEWX, con el parámetro angle que define la cantidad de sesgo. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Establece el tipo de transformación a SVG_TRANSFORM_SKEWY, con el parámetro angle que define la cantidad de sesgo. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Establece el tipo de transformación a SVG_TRANSFORM_TRANSLATE, con los parámetros tx y ty que definen las cantidades de traslación. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Devuelve una cadena que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | Una transformación 'matrix(…)'. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | Una transformación 'rotate(…)'. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | Una transformación 'scale(…)' |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | Una transformación 'skewX(…)' |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | Una transformación 'skewY(…)' |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | Una transformación 'translate(…)' |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | El tipo de unidad no es uno de los tipos predefinidos. Es inválido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
