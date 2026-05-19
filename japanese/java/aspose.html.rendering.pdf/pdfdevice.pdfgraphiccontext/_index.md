---
title: "PdfDevice.PdfGraphicContext クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.pdf.PdfDevicePdfGraphicContext クラス。PdfDevice の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。"
type: docs

url: /ja/java/com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/
---
## PdfDevice.PdfGraphicContext class

PdfDevice の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。

```java
public class PdfGraphicContext : GraphicContext
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [pdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext/.ctor)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [characterSpacing](../../com.aspose.html.rendering/graphiccontext/characterspacing/) { get; set; } | 文字間隔を設定または取得します。 |
| [fillBrush](../../com.aspose.html.rendering/graphiccontext/fillbrush/) { get; set; } | パスの内部を塗りつぶすために使用されるブラシオブジェクトを設定または取得します。 |
| [font](../../com.aspose.html.rendering/graphiccontext/font/) { get; set; } | テキストのレンダリングに使用される TrueType フォントオブジェクトを設定または取得します。 |
| [fontSize](../../com.aspose.html.rendering/graphiccontext/fontsize/) { get; set; } | テキストフォントサイズを設定または取得します。 |
| [fontStyle](../../com.aspose.html.rendering/graphiccontext/fontstyle/) { get; set; } | テキストフォントスタイルを設定または取得します。 |
| [lineCap](../../com.aspose.html.rendering/graphiccontext/linecap/) { get; set; } | ストロークされた任意のオープンパスの端点の形状を指定するコードを設定または取得します。 |
| [lineDashOffset](../../com.aspose.html.rendering/graphiccontext/linedashoffset/) { get; set; } | 現在のラインダッシュパターンの位相オフセットを設定または取得します。 |
| [lineDashPattern](../../com.aspose.html.rendering/graphiccontext/linedashpattern/) { get; set; } | パスがストロークされる際に使用されるダッシュパターンの説明を設定または取得します。 |
| [lineJoin](../../com.aspose.html.rendering/graphiccontext/linejoin/) { get; set; } | ストロークされたパスの接続されたセグメント間のジョイント形状を指定するコードを設定または取得します。 |
| [lineWidth](../../com.aspose.html.rendering/graphiccontext/linewidth/) { get; set; } | ストロークされるパスの太さを設定または取得します。 |
| [miterLimit](../../com.aspose.html.rendering/graphiccontext/miterlimit/) { get; set; } | ストロークされたパスのミーテルラインジョイントの最大長さを設定または取得します。このパラメータは、線分が鋭角で結合したときに生成される「スパイク」の長さを制限します。 |
| [strokeBrush](../../com.aspose.html.rendering/graphiccontext/strokebrush/) { get; set; } | ストロークされたパスに使用されるブラシオブジェクトを設定または取得します。 |
| [getTextInfo](../../com.aspose.html.rendering/graphiccontext/textinfo/) は、レンダリングされたテキストに関する情報を含む [`TextInfo`](../../com.aspose.html.rendering/textinfo/) オブジェクトを取得します。 |
| [transformationMatrix](../../com.aspose.html.rendering/graphiccontext/transformationmatrix/) { get; set; } | 変換行列を設定または取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [clone](../../com.aspose.html.rendering/graphiccontext/clone/)() | 既存のインスタンスと同じプロパティ値を持つ GraphicContext クラスの新しいインスタンスを作成します。 |
| [transform](../../com.aspose.html.rendering/graphiccontext/transform/)(IMatrix) | 指定された行列を掛け算して現在の変換行列を変更します。 |

### 関連項目

* class [GraphicContext](../../com.aspose.html.rendering/graphiccontext/)
* class [PdfDevice](../pdfdevice/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
