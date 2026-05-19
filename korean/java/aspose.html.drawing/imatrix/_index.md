---
title: "IMatrix 인터페이스"
second_title: "Aspose.HTML for Java API 참조"
description: "com.aspose.html.drawing.IMatrix 인터페이스. 변환에 사용되는 행렬을 나타냅니다"
type: docs

url: /ko/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

변환에 사용되는 행렬을 나타냅니다.

```java
public interface IMatrix
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) 이 행렬이 단위 행렬인지 여부를 나타내는 값을 가져옵니다. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) 이 행렬이 가역인지 여부를 나타내는 값을 가져옵니다. |
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

## 메서드

| 이름 | 설명 |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | 이 행렬의 복사본을 생성합니다. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | 행렬의 요소를 배열로 가져옵니다. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | 이 행렬을 역전시킵니다. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | 이 행렬을 다른 행렬과 곱합니다. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | 지정된 순서대로 이 행렬을 다른 행렬과 곱합니다. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | 행렬을 단위 행렬로 재설정합니다. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | 지정된 각도만큼 행렬을 회전시킵니다. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | 지정된 순서대로 지정된 각도만큼 행렬을 회전시킵니다. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | 지정된 점을 중심으로 지정된 각도만큼 행렬을 회전시킵니다. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | 지정된 순서대로 지정된 점을 중심으로 지정된 각도만큼 행렬을 회전시킵니다. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | 지정된 스케일 팩터를 균일하게 적용하여 행렬을 확대/축소합니다. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | 지정된 순서대로 지정된 스케일 팩터를 적용하여 행렬을 확대/축소합니다. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | 행렬에 기울이기 변환을 적용합니다. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | 이 행렬을 사용하여 지정된 점을 변환합니다. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | 이 행렬을 사용하여 점 배열을 변환합니다. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | 이 행렬을 사용하여 지정된 사각형을 변환합니다. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | 지정된 오프셋 값만큼 행렬을 평행 이동합니다. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | 지정된 순서대로 지정된 오프셋 값만큼 행렬을 평행 이동합니다. |

### 또 보기

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
