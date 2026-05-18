---
title: "IMatrix Schnittstelle"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.drawing.IMatrix Schnittstelle. Stellt eine Matrix dar, die für Transformationen verwendet wird"
type: docs

url: /de/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Stellt eine Matrix dar, die für Transformationen verwendet wird.

```java
public interface IMatrix
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Gibt einen Wert zurück, der angibt, ob diese Matrix die Einheitsmatrix ist. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Gibt einen Wert zurück, der angibt, ob diese Matrix invertierbar ist. |
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

## Methoden

| Name | Beschreibung |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Erstellt eine Kopie dieser Matrix. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Liefert die Elemente der Matrix als Array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Invertiert diese Matrix. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Multipliziert diese Matrix mit einer anderen Matrix. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Multipliziert diese Matrix mit einer anderen Matrix in der angegebenen Reihenfolge. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Setzt die Matrix auf die Einheitsmatrix zurück. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Dreht die Matrix um den angegebenen Winkel. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Dreht die Matrix um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Dreht die Matrix um den angegebenen Winkel um den angegebenen Punkt. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Dreht die Matrix um den angegebenen Winkel um den angegebenen Punkt in der angegebenen Reihenfolge. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Skaliert die Matrix um die angegebenen Skalierungsfaktoren einheitlich. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Skaliert die Matrix um die angegebenen Skalierungsfaktoren in der angegebenen Reihenfolge. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Wendet eine Schertransformation auf die Matrix an. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transformiert den angegebenen Punkt mit dieser Matrix. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transformiert ein Array von Punkten mit dieser Matrix. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transformiert das angegebene Rechteck mit dieser Matrix. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Verschiebt die Matrix um die angegebenen Offset-Werte. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Verschiebt die Matrix um die angegebenen Offset-Werte in der angegebenen Reihenfolge. |

### Siehe auch

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
