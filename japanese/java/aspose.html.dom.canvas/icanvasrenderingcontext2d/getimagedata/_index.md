---
title: "ICanvasRenderingContext2D.GetImageData"
second_title: "Aspose.HTML for Java API リファレンス"
description: "ICanvasRenderingContext2D メソッド。sx と sy を開始点とし、幅 sw と高さ sh を持つ矩形で示されるキャンバス領域の基礎となるピクセルデータを表す ImageData オブジェクトを返します。このメソッドはキャンバスの変換行列の影響を受けません。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

矩形 (sx, sy) から始まり、幅 sw と高さ sh を持つ領域のピクセルデータを表す ImageData オブジェクトを返します。このメソッドはキャンバスの変換行列の影響を受けません。

```java
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sx | Double | ImageData が抽出される矩形の左上隅の x 座標です。 |
| sy | Double | ImageData が抽出される矩形の左上隅の y 座標です。 |
| sw | Double | ImageData が抽出される矩形の幅です。 |
| sh | Double | ImageData が抽出される矩形の高さです。 |

### 戻り値

キャンバスの指定された矩形の画像データを含む ImageData オブジェクトです。

### 関連項目

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* package [com.aspose.html.dom.canvas](../../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../../)
