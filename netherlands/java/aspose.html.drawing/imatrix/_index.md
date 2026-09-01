---
title: "IMatrix Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.drawing.IMatrix interface. Vertegenwoordigt een matrix die wordt gebruikt voor transformaties"
type: docs

url: /nl/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Stelt een matrix voor die wordt gebruikt voor transformaties.

```java
public interface IMatrix
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Haalt een waarde op die aangeeft of deze matrix de identiteitsmatrix is. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Haalt een waarde op die aangeeft of deze matrix omkeerbaar is. |
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

| Naam | Beschrijving |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Maakt een kopie van deze matrix. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Haalt de elementen van de matrix op als een array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Keert deze matrix om. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Vermenigvuldigt deze matrix met een andere matrix. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Vermenigvuldigt deze matrix met een andere matrix in de opgegeven volgorde. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Reset de matrix naar de identiteitsmatrix. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Roteert de matrix met de opgegeven hoek. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Roteert de matrix met de opgegeven hoek in de opgegeven volgorde. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Roteert de matrix met de opgegeven hoek rond het opgegeven punt. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Roteert de matrix met de opgegeven hoek rond het opgegeven punt in de opgegeven volgorde. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Schaalt de matrix met de opgegeven schaalfactoren uniform. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Schaalt de matrix met de opgegeven schaalfactoren in de opgegeven volgorde. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Past een scheeftransformatie toe op de matrix. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Transformeert het opgegeven punt met behulp van deze matrix. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Transformeert een array van punten met behulp van deze matrix. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Transformeert de opgegeven rechthoek met behulp van deze matrix. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Verschuift de matrix met de opgegeven offsetwaarden. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Verschuift de matrix met de opgegeven offsetwaarden in de opgegeven volgorde. |

### Zie ook

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
