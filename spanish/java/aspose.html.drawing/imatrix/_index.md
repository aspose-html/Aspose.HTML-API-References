---
title: "Interfaz IMatrix"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.drawing.IMatrix. Representa una matriz utilizada para transformaciones"
type: docs

url: /es/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Representa una matriz utilizada para transformaciones.

```java
public interface IMatrix
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Obtiene un valor que indica si esta matriz es la matriz identidad. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Obtiene un valor que indica si esta matriz es invertible. |
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

## Métodos

| Nombre | Descripción |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Crea una copia de esta matriz. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Obtiene los elementos de la matriz como una matriz. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Invierte esta matriz. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Multiplica esta matriz por otra matriz. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Multiplica esta matriz por otra matriz en el orden especificado. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Restablece la matriz a la matriz identidad. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Rota la matriz por el ángulo especificado. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Rota la matriz por el ángulo especificado en el orden especificado. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Rota la matriz por el ángulo especificado alrededor del punto especificado. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Rota la matriz por el ángulo especificado alrededor del punto especificado en el orden especificado. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Escala la matriz por los factores de escala especificados de forma uniforme. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Escala la matriz por los factores de escala especificados en el orden especificado. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Aplica una transformación de sesgo a la matriz. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transforma el punto especificado usando esta matriz. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transforma una matriz de puntos usando esta matriz. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transforma el rectángulo especificado usando esta matriz. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Traslada la matriz por los valores de desplazamiento especificados. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Traslada la matriz por los valores de desplazamiento especificados en el orden especificado. |

### Ver también

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
