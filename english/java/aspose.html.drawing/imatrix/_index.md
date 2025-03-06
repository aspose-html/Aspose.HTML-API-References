---
title: IMatrix Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.drawing.IMatrix interface. Represents a matrix used for transformations
type: docs

url: /java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Represents a matrix used for transformations.

```java
public interface IMatrix
```

## Properties

| Name | Description |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Gets a value indicating whether this matrix is the identity matrix. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Gets a value indicating whether this matrix is invertible. |
[getM11]
[setM11] Gets or sets the value in the first row and first column of the matrix. |
[getM12]
[setM12] Gets or sets the value in the first row and second column of the matrix. |
[getM21]
[setM21] Gets or sets the value in the second row and first column of the matrix. |
[getM22]
[setM22] Gets or sets the value in the second row and second column of the matrix. |
[getM31]
[setM31] Gets or sets the value in the third row and first column of the matrix. |
[getM32]
[setM32] Gets or sets the value in the third row and second column of the matrix. |

## Methods

| Name | Description |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Creates a copy of this matrix. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Gets the elements of the matrix as an array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Inverts this matrix. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Multiplies this matrix by another matrix. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Multiplies this matrix by another matrix in the specified order. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Resets the matrix to the identity matrix. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Rotates the matrix by the specified angle. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Rotates the matrix by the specified angle in the specified order. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Rotates the matrix by the specified angle around the specified point. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Rotates the matrix by the specified angle around the specified point in the specified order. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Scales the matrix by the specified scale factors uniformly. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Scales the matrix by the specified scale factors in the specified order. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Applies a skew transformation to the matrix. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transforms the specified point using this matrix. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transforms an array of points using this matrix. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transforms the specified rectangle using this matrix. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Translates the matrix by the specified offset values. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Translates the matrix by the specified offset values in the specified order. |

### See Also

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
