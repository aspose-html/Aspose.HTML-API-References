---
title: IMatrix Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Drawing.IMatrix interface. Represents a matrix used for transformations
type: docs
weight: 2910
url: /net/aspose.html.drawing/imatrix/
---
## IMatrix interface

Represents a matrix used for transformations.

```csharp
public interface IMatrix
```

## Properties

| Name | Description |
| --- | --- |
| [IsIdentity](../../aspose.html.drawing/imatrix/isidentity/) { get; } | Gets a value indicating whether this matrix is the identity matrix. |
| [IsInvertible](../../aspose.html.drawing/imatrix/isinvertible/) { get; } | Gets a value indicating whether this matrix is invertible. |
| [M11](../../aspose.html.drawing/imatrix/m11/) { get; set; } | Gets or sets the value in the first row and first column of the matrix. |
| [M12](../../aspose.html.drawing/imatrix/m12/) { get; set; } | Gets or sets the value in the first row and second column of the matrix. |
| [M21](../../aspose.html.drawing/imatrix/m21/) { get; set; } | Gets or sets the value in the second row and first column of the matrix. |
| [M22](../../aspose.html.drawing/imatrix/m22/) { get; set; } | Gets or sets the value in the second row and second column of the matrix. |
| [M31](../../aspose.html.drawing/imatrix/m31/) { get; set; } | Gets or sets the value in the third row and first column of the matrix. |
| [M32](../../aspose.html.drawing/imatrix/m32/) { get; set; } | Gets or sets the value in the third row and second column of the matrix. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](../../aspose.html.drawing/imatrix/clone/)() | Creates a copy of this matrix. |
| [GetElements](../../aspose.html.drawing/imatrix/getelements/)() | Gets the elements of the matrix as an array. |
| [Invert](../../aspose.html.drawing/imatrix/invert/)() | Inverts this matrix. |
| [Multiply](../../aspose.html.drawing/imatrix/multiply/#multiply)(*IMatrix*) | Multiplies this matrix by another matrix. |
| [Multiply](../../aspose.html.drawing/imatrix/multiply/#multiply_1)(*IMatrix, [WebMatrixOrder](../webmatrixorder/)*) | Multiplies this matrix by another matrix in the specified order. |
| [Reset](../../aspose.html.drawing/imatrix/reset/)() | Resets the matrix to the identity matrix. |
| [Rotate](../../aspose.html.drawing/imatrix/rotate/#rotate)(*float*) | Rotates the matrix by the specified angle. |
| [Rotate](../../aspose.html.drawing/imatrix/rotate/#rotate_1)(*float, [WebMatrixOrder](../webmatrixorder/)*) | Rotates the matrix by the specified angle in the specified order. |
| [RotateAt](../../aspose.html.drawing/imatrix/rotateat/#rotateat)(*float, PointF*) | Rotates the matrix by the specified angle around the specified point. |
| [RotateAt](../../aspose.html.drawing/imatrix/rotateat/#rotateat_1)(*float, PointF, [WebMatrixOrder](../webmatrixorder/)*) | Rotates the matrix by the specified angle around the specified point in the specified order. |
| [Scale](../../aspose.html.drawing/imatrix/scale/#scale)(*float, float*) | Scales the matrix by the specified scale factors uniformly. |
| [Scale](../../aspose.html.drawing/imatrix/scale/#scale_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Scales the matrix by the specified scale factors in the specified order. |
| [Skew](../../aspose.html.drawing/imatrix/skew/)(*float, float*) | Applies a skew transformation to the matrix. |
| [TransformPoint](../../aspose.html.drawing/imatrix/transformpoint/)(*PointF*) | Transforms the specified point using this matrix. |
| [TransformPoints](../../aspose.html.drawing/imatrix/transformpoints/)(*PointF[]*) | Transforms an array of points using this matrix. |
| [TransformRectangle](../../aspose.html.drawing/imatrix/transformrectangle/)(*RectangleF*) | Transforms the specified rectangle using this matrix. |
| [Translate](../../aspose.html.drawing/imatrix/translate/#translate)(*float, float*) | Translates the matrix by the specified offset values. |
| [Translate](../../aspose.html.drawing/imatrix/translate/#translate_1)(*float, float, [WebMatrixOrder](../webmatrixorder/)*) | Translates the matrix by the specified offset values in the specified order. |

### See Also

* namespace [Aspose.Html.Drawing](../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../)
