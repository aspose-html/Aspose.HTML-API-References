---
title: "ICanvasRenderingContext2D.PutImageData"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasRenderingContext2D メソッド。指定された ImageData オブジェクトのデータをビットマップに描画します。dirty 矩形が指定された場合、その矩形内のピクセルのみが描画されます。このメソッドはキャンバスの変換行列の影響を受けません。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

指定された ImageData オブジェクトのデータをビットマップに描画します。ダーティ矩形が指定された場合、その矩形内のピクセルだけが描画されます。このメソッドはキャンバス変換行列の影響を受けません。

```java
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| imagedata | IImageData | ピクセル値の配列を含む ImageData オブジェクトです。 |
| dx | Double | 画像データを配置する先のキャンバス上の水平位置（x 座標）。 |
| dy | Double | 画像データを配置する先のキャンバス上の垂直位置（y 座標）。 |

### 関連項目

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

指定された ImageData オブジェクトのデータをビットマップに描画します。ダーティ矩形が指定された場合、その矩形内のピクセルだけが描画されます。このメソッドはキャンバス変換行列の影響を受けません。

```java
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| imagedata | IImageData | ピクセル値の配列を含む ImageData オブジェクトです。 |
| dx | Double | 画像データを配置する先のキャンバス上の水平位置（x 座標）。 |
| dy | Double | 画像データを配置する先のキャンバス上の垂直位置（y 座標）。 |
| dirtyX | Double | 水平位置（x 座標）。画像データの左上隅の x 座標です。デフォルトは 0 です。 |
| dirtyY | Double | 垂直位置（y 座標）。画像データの左上隅の y 座標です。デフォルトは 0 です。 |
| dirtyWidth | Double | 描画される矩形の幅です。デフォルトは画像データの幅です。 |
| dirtyHeight | Double | 描画される矩形の高さです。デフォルトは画像データの高さです。 |

### 関連項目

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
