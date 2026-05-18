---
title: "Interface IMatrix"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "interface com.aspose.html.drawing.IMatrix. Représente une matrice utilisée pour les transformations"
type: docs

url: /fr/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Représente une matrice utilisée pour les transformations.

```java
public interface IMatrix
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Obtient une valeur indiquant si cette matrice est la matrice identité. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Obtient une valeur indiquant si cette matrice est inversible. |
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

## Méthodes

| Nom | Description |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Crée une copie de cette matrice. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Obtient les éléments de la matrice sous forme de tableau. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Inverse cette matrice. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Multiplie cette matrice par une autre matrice. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Multiplie cette matrice par une autre matrice dans l'ordre spécifié. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Réinitialise la matrice à la matrice identité. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Fait pivoter la matrice selon l'angle spécifié. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Fait pivoter la matrice selon l'angle spécifié dans l'ordre spécifié. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Fait pivoter la matrice selon l'angle spécifié autour du point spécifié. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Fait pivoter la matrice selon l'angle spécifié autour du point spécifié dans l'ordre spécifié. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Redimensionne la matrice selon les facteurs d'échelle spécifiés de manière uniforme. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Redimensionne la matrice selon les facteurs d'échelle spécifiés dans l'ordre spécifié. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Applique une transformation de cisaillement à la matrice. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transforme le point spécifié en utilisant cette matrice. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transforme un tableau de points en utilisant cette matrice. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transforme le rectangle spécifié en utilisant cette matrice. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Déplace la matrice selon les valeurs de décalage spécifiées. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Déplace la matrice selon les valeurs de décalage spécifiées dans l'ordre spécifié. |

### Voir aussi

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
