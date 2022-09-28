---
title: SVGTransform
second_title: Referencia de API de Aspose.HTML para .NET
description: SVGTransform es la interfaz para una de las transformaciones de componentes dentro de una SVGTransformList por lo tanto un objeto SVGTransform corresponde a un solo componente p. ej. escala ... o matriz ... dentro de una especificación de atributo de transformación.
type: docs
weight: 1310
url: /es/net/aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform es la interfaz para una de las transformaciones de componentes dentro de una SVGTransformList; por lo tanto, un objeto SVGTransform corresponde a un solo componente (p. ej., 'escala (...)' o 'matriz (...)') dentro de una especificación de atributo de 'transformación'.

```csharp
public class SVGTransform : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Angle](../../aspose.html.dom.svg.datatypes/svgtransform/angle) { get; } | Un atributo de conveniencia para SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY. Mantiene el ángulo especificado. Para SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE y SVG_TRANSFORM_SCALE, el ángulo será cero. |
| [Matrix](../../aspose.html.dom.svg.datatypes/svgtransform/matrix) { get; } | La matriz que representa esta transformación. El objeto de matriz está activo, lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto de matriz y viceversa. En caso de que el objeto de matriz se cambie directamente (es decir, sin usar los métodos en la interfaz de SVGTransform en sí), el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX, la matriz contiene a, b, c, d, e, f valores proporcionados por el usuario. Para SVG_TRANSFORM_TRANSLATE, e y f representan los montos de traducción (a= 1, b= 0, c= 0 y d = 1). Para SVG_TRANSFORM_SCALE, a y d representan los montos de escala (b= 0 , c= 0, e= 0 y f = 0). Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY, a, b, c y d representan la matriz que dará como resultado el sesgo dado (e= 0 y f = 0). Para SVG_TRANSFORM_ROTATE , a, b, c, d, e y f juntas representan la matriz que dará como resultado la rotación dada. Cuando la rotación es alrededor del punto central (0, 0), e y f serán cero. |
| [Type](../../aspose.html.dom.svg.datatypes/svgtransform/type) { get; } | El tipo de valor especificado por una de las constantes SVG_TRANSFORM_* definidas en esta interfaz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.html.dom.svg.datatypes/svgvaluetype/dispose)() | Libera recursos no administrados y, opcionalmente, administrados. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [SetMatrix](../../aspose.html.dom.svg.datatypes/svgtransform/setmatrix)(SVGMatrix) | Establece el tipo de transformación en SVG_TRANSFORM_MATRIX, con la matriz de parámetros que define la nueva transformación. Los valores de la matriz de parámetros se copian, el parámetro de matriz no reemplaza a SVGTransform::matrix. |
| [SetRotate](../../aspose.html.dom.svg.datatypes/svgtransform/setrotate)(float, float, float) | Establece el tipo de transformación en SVG_TRANSFORM_ROTATE, con el parámetro angle que define el ángulo de rotación y los parámetros cx y cy que definen el centro de rotación opcional. |
| [SetScale](../../aspose.html.dom.svg.datatypes/svgtransform/setscale)(float, float) | Establece el tipo de transformación en SVG_TRANSFORM_SCALE, con los parámetros sx y sy que definen las cantidades de escala. |
| [SetSkewX](../../aspose.html.dom.svg.datatypes/svgtransform/setskewx)(float) | Establece el tipo de transformación en SVG_TRANSFORM_SKEWX, con el ángulo del parámetro que define la cantidad de sesgo. |
| [SetSkewY](../../aspose.html.dom.svg.datatypes/svgtransform/setskewy)(float) | Establece el tipo de transformación en SVG_TRANSFORM_SKEWY, con el ángulo del parámetro que define la cantidad de sesgo. |
| [SetTranslate](../../aspose.html.dom.svg.datatypes/svgtransform/settranslate)(float, float) | Establece el tipo de transformación en SVG_TRANSFORM_TRANSLATE, con los parámetros tx y ty que definen las cantidades de traducción. |
| override [ToString](../../aspose.html.dom.svg.datatypes/svgtransform/tostring)() | Devuelve unString que representa esta instancia. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix) | Una transformación 'matriz(...)'. |
| const [SVG_TRANSFORM_ROTATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate) | Una transformación 'girar(...)'. |
| const [SVG_TRANSFORM_SCALE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale) | Una transformación de 'escala (…)'. |
| const [SVG_TRANSFORM_SKEWX](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx) | Una transformación 'sesgadaX(…)'. |
| const [SVG_TRANSFORM_SKEWY](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy) | Una transformación 'skewY(…)'. |
| const [SVG_TRANSFORM_TRANSLATE](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate) | Una transformación 'traducir(...)'. |
| const [SVG_TRANSFORM_UNKNOWN](../../aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown) | El tipo de unidad no es uno de los tipos predefinidos. No es válido intentar definir un nuevo valor de este tipo o intentar cambiar un valor existente a este tipo. |

### Ver también

* class [SVGValueType](../svgvaluetype)
* espacio de nombres [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
