---
title: "واجهة IMatrix"
second_title: "مرجع API لـ Aspose.HTML للـ Java"
description: "واجهة com.aspose.html.drawing.IMatrix. تمثل مصفوفة تُستخدم للتحويلات"
type: docs

url: /ar/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

يمثل مصفوفة تُستخدم للتحويلات.

```java
public interface IMatrix
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة هي مصفوفة الهوية. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) يحصل على قيمة تشير إلى ما إذا كانت هذه المصفوفة قابلة للعكس. |
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

## الطرق

| الاسم | الوصف |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | ينشئ نسخة من هذه المصفوفة. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | يحصل على عناصر المصفوفة كمصفوفة. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | يعكس هذه المصفوفة. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | يضرب هذه المصفوفة بمصفوفة أخرى. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | يضرب هذه المصفوفة بمصفوفة أخرى بالترتيب المحدد. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | يعيد المصفوفة إلى مصفوفة الهوية. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | يدور المصفوفة بالزاوية المحددة. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | يدور المصفوفة بالزاوية المحددة بالترتيب المحدد. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | يدور المصفوفة بالزاوية المحددة حول النقطة المحددة. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | يدور المصفوفة بالزاوية المحددة حول النقطة المحددة بالترتيب المحدد. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | يقوم بتكبير المصفوفة بعوامل القياس المحددة بشكل موحد. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | يقوم بتكبير المصفوفة بعوامل القياس المحددة بالترتيب المحدد. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | يطبق تحويلًا مائلًا على المصفوفة. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | يحول النقطة المحددة باستخدام هذه المصفوفة. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | يحول مصفوفة من النقاط باستخدام هذه المصفوفة. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | يحول المستطيل المحدد باستخدام هذه المصفوفة. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | ينقل المصفوفة بقيم الإزاحة المحددة. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | ينقل المصفوفة بقيم الإزاحة المحددة بالترتيب المحدد. |

### انظر أيضًا

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
