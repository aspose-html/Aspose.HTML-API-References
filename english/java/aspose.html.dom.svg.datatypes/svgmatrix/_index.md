---
title: SVGMatrix Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.datatypes.SVGMatrix class. Many of SVGs graphics operations utilize 2x3 matrices of the form a c e b d f which when expanded into a 3x3 matrix for the purposes of matrix arithmetic become a c e b d f 0 0 1
type: docs

url: /java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Many of SVG's graphics operations utilize 2x3 matrices of the form: [a c e] [b d f] which, when expanded into a 3x3 matrix for the purposes of matrix arithmetic, become: [a c e] [b d f] [0 0 1]

```java
public class SVGMatrix : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | The A component of the matrix. |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | The B component of the matrix. |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | The C component of the matrix. |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | The D component of the matrix. |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | The E component of the matrix. |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | The F component of the matrix. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | Performs matrix multiplication. This matrix is post-multiplied by another matrix, returning the resulting new matrix. |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | Post-multiplies a rotation transformation on the current matrix and returns the resulting matrix. |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | Post-multiplies a uniform scale transformation on the current matrix and returns the resulting matrix. |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | Post-multiplies a non-uniform scale transformation on the current matrix and returns the resulting matrix. |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | Post-multiplies a skewX transformation on the current matrix and returns the resulting matrix. |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | Post-multiplies a skewY transformation on the current matrix and returns the resulting matrix. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | Returns a String that represents this instance. |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | Post-multiplies a translation transformation on the current matrix and returns the resulting matrix. |

### See Also

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
