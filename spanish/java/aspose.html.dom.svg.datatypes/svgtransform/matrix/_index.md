---
title: "SVGTransform.Matrix"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad SVGTransform. La matriz que representa esta transformación. El objeto matriz está activo, lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto matriz y viceversa. En caso de que el objeto matriz se cambie directamente, es decir, sin usar los métodos de la interfaz SVGTransform, el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX, la matriz contiene los valores a b c d e f suministrados por el usuario. Para SVG_TRANSFORM_TRANSLATE, e y f representan las cantidades de traslación (a= 1, b= 0, c= 0 y d= 1). Para SVG_TRANSFORM_SCALE, a y d representan las cantidades de escala (b= 0, c= 0, e= 0 y f= 0). Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY, a b c y d representan la matriz que producirá la inclinación dada (e= 0 y f= 0). Para SVG_TRANSFORM_ROTATE, a b c d e y f juntos representan la matriz que producirá la rotación dada. Cuando la rotación es alrededor del punto central (0, 0), e y f serán cero."
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

La matriz que representa esta transformación. El objeto matriz está activo, lo que significa que cualquier cambio realizado en el objeto SVGTransform se refleja inmediatamente en el objeto matriz y viceversa. En caso de que el objeto matriz se cambie directamente (es decir, sin usar los métodos de la interfaz SVGTransform), el tipo de SVGTransform cambia a SVG_TRANSFORM_MATRIX. Para SVG_TRANSFORM_MATRIX, la matriz contiene los valores a, b, c, d, e, f suministrados por el usuario. Para SVG_TRANSFORM_TRANSLATE, e y f representan las cantidades de traslación (a= 1, b= 0, c= 0 y d = 1). Para SVG_TRANSFORM_SCALE, a y d representan las cantidades de escala (b= 0, c= 0, e= 0 y f = 0). Para SVG_TRANSFORM_SKEWX y SVG_TRANSFORM_SKEWY, a, b, c y d representan la matriz que producirá la inclinación dada (e= 0 y f = 0). Para SVG_TRANSFORM_ROTATE, a, b, c, d, e y f juntos representan la matriz que producirá la rotación dada. Cuando la rotación es alrededor del punto central (0, 0), e y f serán cero.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

La matriz que representa esta transformación.

### Ver también

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
