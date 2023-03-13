---
title: Class DocDevice.DocGraphicContext
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Doc.DocDeviceDocGraphicContext クラス. DocDevice の現在のグラフィック制御パラメーターを保持します これらのパラメーターはグラフィック オペレーターが実行されるグローバル フレームワークを定義します
type: docs
weight: 4180
url: /ja/net/aspose.html.rendering.doc/docdevice.docgraphiccontext/
---
## DocDevice.DocGraphicContext class

DocDevice の現在のグラフィック制御パラメーターを保持します。 これらのパラメーターは、グラフィック オペレーターが実行されるグローバル フレームワークを定義します。

```csharp
public class DocGraphicContext : GraphicContext
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DocGraphicContext](docgraphiccontext/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 文字間隔を設定または取得します。 |
| virtual [FillBrush](../../aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | パスの内部を塗りつぶすために使用されるブラシ オブジェクトを設定または取得します。 |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | テキストのレンダリングに使用される True Type フォント オブジェクトを設定または取得します。 |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | テキストのフォント サイズを設定または取得します。 |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | テキストのフォント スタイルを設定または取得します。 |
| virtual [LineCap](../../aspose.html.rendering/graphiccontext/linecap/) { get; set; } | ストロークされた開いたパスの端点の形状を指定するコードを設定または取得します。 |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 現在の破線パターンの位相オフセットを設定または取得します。 |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | パスがストロークされるときに使用される破線パターンの説明を設定または取得します。 |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | のセットは、ストローク パスの破線のスタイルを取得します。 |
| virtual [LineJoin](../../aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | ストローク パスの接続されたセグメント間のジョイントの形状を指定するコードを設定または取得します。 |
| virtual [LineWidth](../../aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | ストロークするパスの太さを設定または取得します。 |
| virtual [MiterLimit](../../aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | ストローク パスの留め継ぎ線結合の最大長を設定または取得します。 このパラメータは、線分が鋭角で結合するときに生成される「スパイク」の長さを制限します. |
| virtual [StrokeBrush](../../aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | ストローク パスに使用されるブラシ オブジェクトを設定または取得します。 |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | を取得します[`TextInfo`](../../aspose.html.rendering/textinfo/)レンダリングされたテキストに関する情報を含むオブジェクト. |
| override [TransformationMatrix](../../aspose.html.rendering.doc/docgraphiccontext/transformationmatrix/) { get; set; } | 変換行列を設定または取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.html.rendering.doc/docgraphiccontext/clone/)() | の新しいインスタンスを作成します[`GraphicContext`](../../aspose.html.rendering/graphiccontext/)既存のインスタンスと同じプロパティ値を持つクラス. |
| override [Transform](../../aspose.html.rendering.doc/docgraphiccontext/transform/)(Matrix) | 指定された行列を乗算して、現在の変換行列を変更します。 |

### 関連項目

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [DocDevice](../docdevice/)
* 名前空間 [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* 組み立て [Aspose.HTML](../../)


