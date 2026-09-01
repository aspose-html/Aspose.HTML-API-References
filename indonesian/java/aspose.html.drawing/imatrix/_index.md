---
title: "Antarmuka IMatrix"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "antarmuka com.aspose.html.drawing.IMatrix. Mewakili matriks yang digunakan untuk transformasi"
type: docs

url: /id/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

Mewakili matriks yang digunakan untuk transformasi.

```java
public interface IMatrix
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) Mendapatkan nilai yang menunjukkan apakah matriks ini adalah matriks identitas. |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) Mendapatkan nilai yang menunjukkan apakah matriks ini dapat diinvers. |
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

## Metode

| Nama | Deskripsi |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | Membuat salinan matriks ini. |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | Mendapatkan elemen-elemen matriks sebagai array. |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | Membalik matriks ini. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | Mengalikan matriks ini dengan matriks lain. |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | Mengalikan matriks ini dengan matriks lain dalam urutan yang ditentukan. |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | Mengatur ulang matriks ke matriks identitas. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | Memutar matriks dengan sudut yang ditentukan. |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | Memutar matriks dengan sudut yang ditentukan dalam urutan yang ditentukan. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | Memutar matriks dengan sudut yang ditentukan di sekitar titik yang ditentukan. |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | Memutar matriks dengan sudut yang ditentukan di sekitar titik yang ditentukan dalam urutan yang ditentukan. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | Menskalakan matriks dengan faktor skala yang ditentukan secara seragam. |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | Menskalakan matriks dengan faktor skala yang ditentukan dalam urutan yang ditentukan. |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | Menerapkan transformasi skew pada matriks. |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | Mengubah titik yang ditentukan menggunakan matriks ini. |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | Mengubah array titik menggunakan matriks ini. |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | Mengubah persegi panjang yang ditentukan menggunakan matriks ini. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | Mentranslasi matriks dengan nilai offset yang ditentukan. |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | Mentranslasi matriks dengan nilai offset yang ditentukan dalam urutan yang ditentukan. |

### Lihat Juga

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
