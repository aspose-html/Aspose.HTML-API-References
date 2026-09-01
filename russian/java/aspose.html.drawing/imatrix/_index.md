---
title: "Интерфейс IMatrix"
second_title: "Справочник API Aspose.HTML для Java"
description: "Интерфейс com.aspose.html.drawing.IMatrix. Представляет матрицу, используемую для преобразований"
type: docs

url: /ru/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Представляет матрицу, используемую для преобразований.

```java
public interface IMatrix
```

## Свойства

| Имя | Описание |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Возвращает значение, указывающее, является ли эта матрица единичной. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Возвращает значение, указывающее, является ли эта матрица обратимой. |
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

## Методы

| Имя | Описание |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Создаёт копию этой матрицы. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Получает элементы матрицы в виде массива. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Инвертирует эту матрицу. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Умножает эту матрицу на другую матрицу. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Умножает эту матрицу на другую матрицу в указанном порядке. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Сбрасывает матрицу к единичной матрице. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Поворачивает матрицу на указанный угол. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Поворачивает матрицу на указанный угол в указанном порядке. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Поворачивает матрицу на указанный угол вокруг указанной точки. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Поворачивает матрицу на указанный угол вокруг указанной точки в указанном порядке. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Масштабирует матрицу на указанные коэффициенты масштабирования равномерно. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Масштабирует матрицу на указанные коэффициенты масштабирования в указанном порядке. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Применяет к матрице трансформацию наклона. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Преобразует указанную точку с помощью этой матрицы. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Преобразует массив точек с помощью этой матрицы. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Преобразует указанный прямоугольник с помощью этой матрицы. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Смещает матрицу на указанные значения смещения. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Смещает матрицу на указанные значения смещения в указанном порядке. |

### См. также

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
