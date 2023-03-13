---
title: ICanvasRenderingContext2D.PutImageData
second_title: Aspose.HTML for .NET API リファレンス
description: ICanvasRenderingContext2D 方法. 指定された ImageData オブジェクトのデータをビットマップに描画します ダーティな四角形が指定されている場合その四角形のピクセルのみが描画されます このメソッドはキャンバス変換マトリックスの影響を受けません.
type: docs
weight: 290
url: /ja/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(IImageData, double, double) {#putimagedata}

指定された ImageData オブジェクトのデータをビットマップに描画します。 ダーティな四角形が指定されている場合、その四角形のピクセルのみが描画されます。 このメソッドはキャンバス変換マトリックスの影響を受けません.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| imagedata | IImageData | ピクセル値の配列を含む ImageData オブジェクト。 |
| dx | Double | 宛先キャンバスに画像データを配置する水平位置 (x 座標)。 |
| dy | Double | 宛先キャンバスに画像データを配置する垂直位置 (y 座標)。 |

### 関連項目

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* 名前空間 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 組み立て [Aspose.HTML](../../../)

---

## PutImageData(IImageData, double, double, double, double, double, double) {#putimagedata_1}

指定された ImageData オブジェクトのデータをビットマップに描画します。 ダーティな四角形が指定されている場合、その四角形のピクセルのみが描画されます。 このメソッドはキャンバス変換マトリックスの影響を受けません.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| imagedata | IImageData | ピクセル値の配列を含む ImageData オブジェクト。 |
| dx | Double | 宛先キャンバスに画像データを配置する水平位置 (x 座標)。 |
| dy | Double | 宛先キャンバスに画像データを配置する垂直位置 (y 座標)。 |
| dirtyX | Double | 水平位置 (x 座標)。画像データの左上隅の x 座標。デフォルトは 0 です。 |
| dirtyY | Double | 垂直位置 (y 座標)。画像データの左上隅の y 座標。デフォルトは 0 です。 |
| dirtyWidth | Double | ペイントする四角形の幅。デフォルトは画像データの幅です。 |
| dirtyHeight | Double | ペイントする長方形の高さ。デフォルトは画像データの高さです。 |

### 関連項目

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* 名前空間 [Aspose.Html.Dom.Canvas](../../icanvasrenderingcontext2d/)
* 組み立て [Aspose.HTML](../../../)


