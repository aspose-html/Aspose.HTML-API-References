---
title: Class PdfDevice.PdfGraphicContext
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Pdf.PdfDevicePdfGraphicContext クラス. PdfDevice の現在のグラフィック コントロール パラメータを保持します これらのパラメータはグラフィック オペレータが実行されるグローバル フレームワークを定義します
type: docs
weight: 4450
url: /ja/net/aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

PdfDevice の現在のグラフィック コントロール パラメータを保持します。 これらのパラメータは、グラフィック オペレータが実行されるグローバル フレームワークを定義します。

```csharp
public class PdfGraphicContext : GraphicContext
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfGraphicContext](pdfgraphiccontext/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [CharacterSpacing](../../aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 文字間隔を設定または取得します。 |
| override [FillBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/fillbrush/) { get; set; } | パスの内部を塗りつぶすために使用されるブラシ オブジェクトを設定または取得します。 |
| virtual [Font](../../aspose.html.rendering/graphiccontext/font/) { get; set; } | テキストのレンダリングに使用される True Type フォント オブジェクトを設定または取得します。 |
| virtual [FontSize](../../aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | テキストのフォント サイズを設定または取得します。 |
| virtual [FontStyle](../../aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | テキストのフォント スタイルを設定または取得します。 |
| override [LineCap](../../aspose.html.rendering.pdf/pdfgraphiccontext/linecap/) { get; set; } | ストロークされた開いたパスの端点の形状を指定するコードを設定または取得します。 |
| virtual [LineDashOffset](../../aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 現在の破線パターンの位相オフセットを設定または取得します。 |
| virtual [LineDashPattern](../../aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | パスがストロークされるときに使用される破線パターンの説明を設定または取得します。 |
| virtual [LineDashStyle](../../aspose.html.rendering/graphiccontext/linedashstyle/) { get; set; } | のセットは、ストローク パスの破線のスタイルを取得します。 |
| override [LineJoin](../../aspose.html.rendering.pdf/pdfgraphiccontext/linejoin/) { get; set; } | ストローク パスの接続されたセグメント間のジョイントの形状を指定するコードを設定または取得します。 |
| override [LineWidth](../../aspose.html.rendering.pdf/pdfgraphiccontext/linewidth/) { get; set; } | ストロークするパスの太さを設定または取得します。 |
| override [MiterLimit](../../aspose.html.rendering.pdf/pdfgraphiccontext/miterlimit/) { get; set; } | ストローク パスの留め継ぎ線結合の最大長を設定または取得します。 このパラメータは、線分が鋭角で結合するときに生成される「スパイク」の長さを制限します. |
| override [StrokeBrush](../../aspose.html.rendering.pdf/pdfgraphiccontext/strokebrush/) { get; set; } | ストローク パスに使用されるブラシ オブジェクトを設定または取得します。 |
| virtual [TextInfo](../../aspose.html.rendering/graphiccontext/textinfo/) { get; } | を取得します[`TextInfo`](../../aspose.html.rendering/textinfo/)レンダリングされたテキストに関する情報を含むオブジェクト. |
| override [TransformationMatrix](../../aspose.html.rendering.pdf/pdfgraphiccontext/transformationmatrix/) { get; set; } | 変換行列を設定または取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Clone](../../aspose.html.rendering.pdf/pdfgraphiccontext/clone/)() | 既存のインスタンスと同じプロパティ値を持つクラスの新しいインスタンスを作成します。 |
| override [Transform](../../aspose.html.rendering.pdf/pdfgraphiccontext/transform/)(Matrix) | 指定された行列を乗算して、現在の変換行列を変更します。 |

### 関連項目

* class [GraphicContext](../../aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* 名前空間 [Aspose.Html.Rendering.Pdf](../../aspose.html.rendering.pdf/)
* 組み立て [Aspose.HTML](../../)


