---
title: "IMatrix インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.drawing.IMatrix インターフェイス。変換に使用される行列を表します。"
type: docs

url: /ja/java/com.aspose.html.drawing/imatrix/
---
## IMatrix interface

変換に使用される行列を表します。

```java
public interface IMatrix
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getIsIdentity](../../com.aspose.html.drawing/imatrix/isidentity/) この行列が単位行列かどうかを示す値を取得します。 |
| [getIsInvertible](../../com.aspose.html.drawing/imatrix/isinvertible/) この行列が可逆かどうかを示す値を取得します。 |
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

## メソッド

| 名前 | 説明 |
| --- | --- |
| [clone](../../com.aspose.html.drawing/imatrix/clone/)() | この行列のコピーを作成します。 |
| [getElements](../../com.aspose.html.drawing/imatrix/getelements/)() | 行列の要素を配列として取得します。 |
| [invert](../../com.aspose.html.drawing/imatrix/invert/)() | この行列を反転させます。 |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply)(IMatrix) | この行列を別の行列と乗算します。 |
| [multiply](../../com.aspose.html.drawing/imatrix/multiply/#multiply_1)(IMatrix, WebMatrixOrder) | この行列を指定された順序で別の行列と乗算します。 |
| [reset](../../com.aspose.html.drawing/imatrix/reset/)() | 行列を単位行列にリセットします。 |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate)(float) | 行列を指定された角度で回転させます。 |
| [rotate](../../com.aspose.html.drawing/imatrix/rotate/#rotate_1)(float, WebMatrixOrder) | 行列を指定された順序で指定された角度だけ回転させます。 |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat)(float, PointF) | 行列を指定された点の周りで指定された角度だけ回転させます。 |
| [rotateAt](../../com.aspose.html.drawing/imatrix/rotateat/#rotateat_1)(float, PointF, WebMatrixOrder) | 行列を指定された順序で、指定された点の周りで指定された角度だけ回転させます。 |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale)(float, float) | 行列を指定されたスケール係数で均等に拡大縮小します。 |
| [scale](../../com.aspose.html.drawing/imatrix/scale/#scale_1)(float, float, WebMatrixOrder) | 行列を指定された順序で、指定されたスケール係数で拡大縮小します。 |
| [skew](../../com.aspose.html.drawing/imatrix/skew/)(float, float) | 行列に斜め変換を適用します。 |
| [transformPoint](../../com.aspose.html.drawing/imatrix/transformpoint/)(PointF) | この行列を使用して指定された点を変換します。 |
| [transformPoints](../../com.aspose.html.drawing/imatrix/transformpoints/)(PointF[]) | この行列を使用して点の配列を変換します。 |
| [transformRectangle](../../com.aspose.html.drawing/imatrix/transformrectangle/)(RectangleF) | この行列を使用して指定された矩形を変換します。 |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate)(float, float) | 行列を指定されたオフセット値で平行移動します。 |
| [translate](../../com.aspose.html.drawing/imatrix/translate/#translate_1)(float, float, WebMatrixOrder) | 行列を指定された順序で、指定されたオフセット値で平行移動します。 |

### 関連項目

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
