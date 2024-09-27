---
title: IMatrix class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.html.drawing/imatrix/
is_root: false
---

## IMatrix class

Represents a matrix used for transformations.



The IMatrix type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [is_identity](/html/python-net/aspose.html.drawing/imatrix/is_identity) | Gets a value indicating whether this matrix is the identity matrix. |
| [m11](/html/python-net/aspose.html.drawing/imatrix/m11) | Gets or sets the value in the first row and first column of the matrix. |
| [m12](/html/python-net/aspose.html.drawing/imatrix/m12) | Gets or sets the value in the first row and second column of the matrix. |
| [m21](/html/python-net/aspose.html.drawing/imatrix/m21) | Gets or sets the value in the second row and first column of the matrix. |
| [m22](/html/python-net/aspose.html.drawing/imatrix/m22) | Gets or sets the value in the second row and second column of the matrix. |
| [m31](/html/python-net/aspose.html.drawing/imatrix/m31) | Gets or sets the value in the third row and first column of the matrix. |
| [m32](/html/python-net/aspose.html.drawing/imatrix/m32) | Gets or sets the value in the third row and second column of the matrix. |
| [is_invertible](/html/python-net/aspose.html.drawing/imatrix/is_invertible) | Gets a value indicating whether this matrix is invertible. |


### Methods
| Method | Description |
| :- | :- |
| [scale](/html/python-net/aspose.html.drawing/imatrix/scale/#float-float-aspose.html.drawing.WebMatrixOrder) | Scales the matrix by the specified scale factors in the specified order. |
| [scale](/html/python-net/aspose.html.drawing/imatrix/scale/#float-float) | Scales the matrix by the specified scale factors uniformly. |
| [translate](/html/python-net/aspose.html.drawing/imatrix/translate/#float-float-aspose.html.drawing.WebMatrixOrder) | Translates the matrix by the specified offset values in the specified order. |
| [translate](/html/python-net/aspose.html.drawing/imatrix/translate/#float-float) | Translates the matrix by the specified offset values. |
| [multiply](/html/python-net/aspose.html.drawing/imatrix/multiply/#aspose.html.drawing.IMatrix-aspose.html.drawing.WebMatrixOrder) | Multiplies this matrix by another matrix in the specified order. |
| [multiply](/html/python-net/aspose.html.drawing/imatrix/multiply/#aspose.html.drawing.IMatrix) | Multiplies this matrix by another matrix. |
| [rotate](/html/python-net/aspose.html.drawing/imatrix/rotate/#float-aspose.html.drawing.WebMatrixOrder) | Rotates the matrix by the specified angle in the specified order. |
| [rotate](/html/python-net/aspose.html.drawing/imatrix/rotate/#float) | Rotates the matrix by the specified angle. |
| [rotate_at](/html/python-net/aspose.html.drawing/imatrix/rotate_at/#float-aspose.pydrawing.PointF-aspose.html.drawing.WebMatrixOrder) | Rotates the matrix by the specified angle around the specified point in the specified order. |
| [rotate_at](/html/python-net/aspose.html.drawing/imatrix/rotate_at/#float-aspose.pydrawing.PointF) | Rotates the matrix by the specified angle around the specified point. |
| [invert](/html/python-net/aspose.html.drawing/imatrix/invert/#) | Inverts this matrix. |
| [get_elements](/html/python-net/aspose.html.drawing/imatrix/get_elements/#) | Gets the elements of the matrix as an array. |
| [transform_point](/html/python-net/aspose.html.drawing/imatrix/transform_point/#aspose.pydrawing.PointF) | Transforms the specified point using this matrix. |
| [transform_points](/html/python-net/aspose.html.drawing/imatrix/transform_points/#aspose.pydrawing.PointF[]) | Transforms an array of points using this matrix. |
| [transform_rectangle](/html/python-net/aspose.html.drawing/imatrix/transform_rectangle/#aspose.pydrawing.RectangleF) | Transforms the specified rectangle using this matrix. |
| [skew](/html/python-net/aspose.html.drawing/imatrix/skew/#float-float) | Applies a skew transformation to the matrix. |
| [reset](/html/python-net/aspose.html.drawing/imatrix/reset/#) | Resets the matrix to the identity matrix. |
| [clone](/html/python-net/aspose.html.drawing/imatrix/clone/#) | Creates a copy of this matrix. |



### See Also
* module [`aspose.html.drawing`](..)
