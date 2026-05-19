---
title: "Clase SVGMatrix"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.svg.datatypes.SVGMatrix. Muchas de las operaciones gráficas de SVG utilizan matrices 2x3 de la forma a c e b d f que, al expandirse a una matriz 3x3 para fines de aritmética matricial, se convierten en a c e b d f 0 0 1"
type: docs

url: /es/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Muchas de las operaciones gráficas de SVG utilizan matrices 2x3 de la forma: [a c e] [b d f] que, al expandirse a una matriz 3x3 para fines de aritmética de matrices, se convierten en: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | El componente A de la matriz. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | El componente B de la matriz. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | El componente C de la matriz. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | El componente D de la matriz. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | El componente E de la matriz. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | El componente F de la matriz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Libera recursos no administrados y, opcionalmente, administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Realiza la multiplicación de matrices. Esta matriz se post-multiplica por otra matriz, devolviendo la nueva matriz resultante. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplica una transformación de rotación en la matriz actual y devuelve la matriz resultante. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplica una transformación de escala uniforme en la matriz actual y devuelve la matriz resultante. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplica una transformación de escala no uniforme en la matriz actual y devuelve la matriz resultante. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Multiplica posteriormente una transformación skewX en la matriz actual y devuelve la matriz resultante. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Multiplica posteriormente una transformación skewY en la matriz actual y devuelve la matriz resultante. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Devuelve una cadena que representa esta instancia. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Multiplica posteriormente una transformación de traslación en la matriz actual y devuelve la matriz resultante. |

### Ver también

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
