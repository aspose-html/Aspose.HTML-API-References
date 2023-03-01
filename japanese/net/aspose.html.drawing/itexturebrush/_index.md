---
title: Interface ITextureBrush
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Drawing.ITextureBrush インターフェース. 画像を使用して形状の内部を塗りつぶすブラシ インターフェイスを定義します
type: docs
weight: 2740
url: /ja/net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

画像を使用して形状の内部を塗りつぶすブラシ インターフェイスを定義します。

```csharp
public interface ITextureBrush : ITransformableBrush
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | 要素数は偶数でなければなりません。すべての偶数要素は古い色です。奇数要素はすべて新しい色です. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | ブラシで使用されるイメージを取得または設定します。 |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | ブラシで使用される画像の部分を指定します。 RectangleF.Empty に等しい場合、画像全体が使用されます。 座標はピクセル単位です。 |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; } | 色変換マトリックスの不透明度値を取得します。 |

### 関連項目

* interface [ITransformableBrush](../itransformablebrush/)
* 名前空間 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 組み立て [Aspose.HTML](../../)


