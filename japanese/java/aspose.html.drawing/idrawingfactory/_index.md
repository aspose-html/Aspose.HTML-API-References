---
title: "IDrawingFactory インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.drawing.IDrawingFactory インターフェイス。描画関連オブジェクトの作成用ファクトリを表します。"
type: docs

url: /ja/java/com.aspose.html.drawing/idrawingfactory/
---
## IDrawingFactory interface

描画関連オブジェクトを作成するファクトリを表します。

```java
public interface IDrawingFactory : IDisposable
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [createInterpolationColor](../../com.aspose.html.drawing/idrawingfactory/createinterpolationcolor/)(Color, float) | 指定された色と位置で補間色を作成します。 |
| [createLinearGradientBrush](../../com.aspose.html.drawing/idrawingfactory/createlineargradientbrush/)(RectangleF, IInterpolationColor[]) | 指定されたパラメーターで線形グラデーションブラシを作成します。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix)() | 新しい単位行列を作成します。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix_1)(IMatrix) | 指定された行列と同じ内容の新しい行列を作成します。 |
| [createMatrix](../../com.aspose.html.drawing/idrawingfactory/creatematrix/#creatematrix_2)(float, float, float, float, float, float) | 指定された要素で新しい行列を作成します。 |
| [createSolidBrush](../../com.aspose.html.drawing/idrawingfactory/createsolidbrush/)(Color) | 指定された色でソリッドブラシを作成します。 |
| [createTextureBrush](../../com.aspose.html.drawing/idrawingfactory/createtexturebrush/)(byte[]) | 指定されたパラメーターでテクスチャブラシを作成します。 |

### 関連項目

* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
