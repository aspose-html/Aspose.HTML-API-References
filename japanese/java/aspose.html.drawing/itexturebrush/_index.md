---
title: "ITextureBrush インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.drawing.ITextureBrush インターフェイス。画像を使用して形状の内部を塗りつぶすブラシインターフェイスを定義します。"
type: docs

url: /ja/java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

画像を使用して形状の内部を塗りつぶすブラシインターフェイスを定義します。

```java
public interface ITextureBrush : ITransformableBrush
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) 要素数は偶数でなければなりません。偶数番目の要素は古い色、奇数番目の要素は新しい色です。 |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) ブラシで使用される画像を取得または設定します。 |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) ブラシで使用される画像の領域を指定します。RectangleF.Empty と等しい場合、画像全体が使用されます。座標はピクセル単位です。 |
[getOpacity]
[setOpacity] Get opacity value in a color transform matrix. |

### 関連項目

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
