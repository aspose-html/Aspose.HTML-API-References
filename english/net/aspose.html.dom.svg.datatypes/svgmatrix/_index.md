---
title: SVGMatrix
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 1330
url: /net/aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

Many of SVG's graphics operations utilize 2x3 matrices of the form: [a c e] [b d f] which, when expanded into a 3x3 matrix for the purposes of matrix arithmetic, become: [a c e] [b d f] [0 0 1]

```csharp
public class SVGMatrix : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [A](a) { get; set; } | The A component of the matrix. |
| [B](b) { get; set; } | The B component of the matrix. |
| [C](c) { get; set; } | The C component of the matrix. |
| [D](d) { get; set; } | The D component of the matrix. |
| [E](e) { get; set; } | The E component of the matrix. |
| [F](f) { get; set; } | The F component of the matrix. |

## Methods

| Name | Description |
| --- | --- |
| [Multiply](multiply)(SVGMatrix) | Performs matrix multiplication. This matrix is post-multiplied by another matrix, returning the resulting new matrix. |
| [Rotate](rotate)(float) | Post-multiplies a rotation transformation on the current matrix and returns the resulting matrix. |
| [Scale](scale)(float) | Post-multiplies a uniform scale transformation on the current matrix and returns the resulting matrix. |
| [ScaleNonUniform](scalenonuniform)(float, float) | Post-multiplies a non-uniform scale transformation on the current matrix and returns the resulting matrix. |
| [SkewX](skewx)(float) | Post-multiplies a skewX transformation on the current matrix and returns the resulting matrix. |
| [SkewY](skewy)(float) | Post-multiplies a skewY transformation on the current matrix and returns the resulting matrix. |
| override [ToString](tostring)() | Returns a String that represents this instance. |
| [Translate](translate)(float, float) | Post-multiplies a translation transformation on the current matrix and returns the resulting matrix. |

### See Also

* class [SVGValueType](../svgvaluetype)
* namespace [Aspose.Html.Dom.Svg.DataTypes](../../aspose.html.dom.svg.datatypes)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->