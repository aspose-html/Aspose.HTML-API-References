---
title: "Interfaccia IMatrix"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Interfaccia com.aspose.html.drawing.IMatrix. Rappresenta una matrice utilizzata per le trasformazioni"
type: docs

url: /it/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Rappresenta una matrice utilizzata per le trasformazioni.

```java
public interface IMatrix
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Ottiene un valore che indica se questa matrice è la matrice identità. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Ottiene un valore che indica se questa matrice è invertibile. |
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

## Metodi

| Nome | Descrizione |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Crea una copia di questa matrice. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Ottiene gli elementi della matrice come array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Inverte questa matrice. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Moltiplica questa matrice per un'altra matrice. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Moltiplica questa matrice per un'altra matrice nell'ordine specificato. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Ripristina la matrice alla matrice identità. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Ruota la matrice dell'angolo specificato. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Ruota la matrice dell'angolo specificato nell'ordine specificato. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Ruota la matrice dell'angolo specificato attorno al punto specificato. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Ruota la matrice dell'angolo specificato attorno al punto specificato nell'ordine specificato. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Scala la matrice dei fattori di scala specificati in modo uniforme. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Scala la matrice dei fattori di scala specificati nell'ordine specificato. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Applica una trasformazione di inclinazione alla matrice. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Trasforma il punto specificato usando questa matrice. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Trasforma un array di punti usando questa matrice. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Trasforma il rettangolo specificato usando questa matrice. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Trasla la matrice dei valori di offset specificati. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Trasla la matrice dei valori di offset specificati nell'ordine specificato. |

### Vedi anche

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
