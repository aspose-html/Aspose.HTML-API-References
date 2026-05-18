---
title: "IMatrix 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.IMatrix 接口。表示用于变换的矩阵"
type: docs

url: /zh/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

表示用于变换的矩阵。

```java
public interface IMatrix
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) 获取一个值，指示此矩阵是否为单位矩阵。 |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) 获取一个值，指示此矩阵是否可逆。 |
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

## 方法

| 名称 | 描述 |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | 创建此矩阵的副本。 |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | 获取矩阵的元素作为数组。 |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | 对该矩阵求逆。 |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | 将此矩阵乘以另一个矩阵。 |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | 按指定顺序将此矩阵乘以另一个矩阵。 |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | 将矩阵重置为单位矩阵。 |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | 按指定角度旋转矩阵。 |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | 按指定顺序按指定角度旋转矩阵。 |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | 围绕指定点按指定角度旋转矩阵。 |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | 按指定顺序围绕指定点按指定角度旋转矩阵。 |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | 按指定比例因子均匀缩放矩阵。 |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | 按指定顺序按指定比例因子缩放矩阵。 |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | 对矩阵应用倾斜变换。 |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | 使用此矩阵转换指定点。 |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | 使用此矩阵转换点数组。 |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | 使用此矩阵转换指定矩形。 |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | 按指定偏移值平移矩阵。 |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | 按指定顺序按指定偏移值平移矩阵。 |

### 另请参阅

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
