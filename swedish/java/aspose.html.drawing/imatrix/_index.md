---
title: "IMatrix-gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.drawing.IMatrix-gränssnitt. Representerar en matris som används för transformationer"
type: docs

url: /sv/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Representerar en matris som används för transformationer.

```java
public interface IMatrix
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Hämtar ett värde som indikerar om denna matris är identitetsmatrisen. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Hämtar ett värde som indikerar om denna matris är inverterbar. |
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

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Skapar en kopia av denna matris. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Hämtar elementen i matrisen som en array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Inverterar denna matris. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Multiplicerar denna matris med en annan matris. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Multiplicerar denna matris med en annan matris i den angivna ordningen. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Återställer matrisen till identitetsmatrisen. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Roterar matrisen med den angivna vinkeln. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Roterar matrisen med den angivna vinkeln i den angivna ordningen. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Roterar matrisen med den angivna vinkeln runt den angivna punkten. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Roterar matrisen med den angivna vinkeln runt den angivna punkten i den angivna ordningen. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Skalar matrisen med de angivna skalningsfaktorerna enhetligt. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Skalar matrisen med de angivna skalningsfaktorerna i den angivna ordningen. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Tillämpar en skev transformation på matrisen. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transformerar den angivna punkten med hjälp av denna matris. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transformerar en array av punkter med hjälp av denna matris. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transformerar den angivna rektangeln med hjälp av denna matris. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Översätter matrisen med de angivna förskjutningsvärdena. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Översätter matrisen med de angivna förskjutningsvärdena i den angivna ordningen. |

### Se även

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
