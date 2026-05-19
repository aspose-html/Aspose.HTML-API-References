---
title: "ICanvasRenderingContext2D.StrokeText"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasRenderingContext2D のメソッド。指定された x, y 位置に与えられたテキストの輪郭を描画します。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/
---
## StrokeText(String, double, double) {#stroketext}

指定された (x, y) の位置に、指定されたテキストを描画（ストローク）します。

```java
public void StrokeText(String text, double x, double y)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| テキスト | 文字列 | 現在のフォント、textAlign、textBaseline、direction の値を使用して描画するテキストです。 |
| x | Double | テキスト開始点の座標の x 軸です。 |
| y | Double | テキスト開始点の座標の y 軸です。 |

### 関連項目

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## StrokeText(String, double, double, double?) {#stroketext_1}

指定された (x, y) の位置に、指定されたテキストを描画（ストローク）します。

```java
public void StrokeText(String text, double x, double y, double? maxWidth)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| テキスト | 文字列 | 現在のフォント、textAlign、textBaseline、direction の値を使用して描画するテキストです。 |
| x | Double | テキスト開始点の座標の x 軸です。 |
| y | Double | テキスト開始点の座標の y 軸です。 |
| maxWidth | Nullable`1 | 描画する最大幅です。指定され、文字列の幅がこの幅を超えると、利用可能な場合はより横に圧縮されたフォント（または現在のフォントを横方向にスケーリングして合理的に読みやすいフォントを合成できる場合）に調整するか、フォントサイズを小さくします。 |

### 関連項目

* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
