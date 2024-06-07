---
title: SVGMatrix class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 160
url: /aspose.html.dom.svg.datatypes/svgmatrix/
is_root: false
---

## SVGMatrix class

Many of SVG's graphics operations utilize 2x3 matrices of the form:
[a c e]
[b d f]
which, when expanded into a 3x3 matrix for the purposes of matrix arithmetic, become:
[a c e]
[b d f]
[0 0 1]



**Inheritance:** [`SVGMatrix`](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix) → 
[`SVGValueType`](/html/python-net/aspose.html.dom.svg.datatypes/svgvaluetype) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The SVGMatrix type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [a](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/a) | The A component of the matrix. |
| [b](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/b) | The B component of the matrix. |
| [c](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/c) | The C component of the matrix. |
| [d](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/d) | The D component of the matrix. |
| [e](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/e) | The E component of the matrix. |
| [f](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/f) | The F component of the matrix. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [multiply](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/multiply/#aspose.html.dom.svg.datatypes.SVGMatrix) | Performs matrix multiplication. This matrix is post-multiplied by another matrix, returning the resulting new matrix. |
| [translate](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/translate/#float-float) | Post-multiplies a translation transformation on the current matrix and returns the resulting matrix. |
| [scale](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/scale/#float) | Post-multiplies a uniform scale transformation on the current matrix and returns the resulting matrix. |
| [scale_non_uniform](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/scale_non_uniform/#float-float) | Post-multiplies a non-uniform scale transformation on the current matrix and returns the resulting matrix. |
| [rotate](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/rotate/#float) | Post-multiplies a rotation transformation on the current matrix and returns the resulting matrix. |
| [skew_x](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/skew_x/#float) | Post-multiplies a skewX transformation on the current matrix and returns the resulting matrix. |
| [skew_y](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix/skew_y/#float) | Post-multiplies a skewY transformation on the current matrix and returns the resulting matrix. |



### See Also
* module [`aspose.html.dom.svg.datatypes`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`SVGMatrix`](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix)
* class [`SVGValueType`](/html/python-net/aspose.html.dom.svg.datatypes/svgvaluetype)
