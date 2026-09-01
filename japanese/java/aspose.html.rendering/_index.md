---
title: "com.aspose.html.rendering"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering パッケージは、ドキュメント/ファイルを IDevice 実装にレンダリングする責任を持つ多数のレンダラーオブジェクトと、適切な低レベルオプションクラスで構成されています。"
type: docs

url: /ja/java/com.aspose.html.rendering/
---
**com.aspose.html.rendering** パッケージは、多数のレンダラーオブジェクトと、ドキュメント/ファイルを IDevice 実装にレンダリングするための適切な低レベルオプションクラスで構成されています。

## クラス

| クラス | 説明 |
| --- | --- |
| [CssOptions](./cssoptions/) | css レンダリングオプションを表します。 |
| [Device](./device/) | さまざまな形式や環境でグラフィックを描画するために使用されるレンダリングデバイスを実装するための基底クラスを表します。 |
| [Device&lt;TGraphicContext,TRenderingOptions&gt;](./device-2/) | 特定のレンダリングデバイスの実装のための基底クラスを表します。 |
| [EpubRenderer](./epubrenderer/) | EPub ドキュメントレンダラーを表します。 |
| [GraphicContext](./graphiccontext/) | 現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。 |
| [HtmlRenderer](./htmlrenderer/) | HTML ドキュメントレンダラーを表します。 |
| [MhtmlRenderer](./mhtmlrenderer/) | MHTML ドキュメントレンダラーを表します。 |
| [PageSetup](./pagesetup/) | ページ設定オブジェクトを表し、出力ページセットの構成に使用されます。 |
| [Renderer](./renderer/) | すべてのレンダラーの基底クラスを表し、IDisposable インターフェイスを実装します。 |
| [Renderer&lt;TSource&gt;](./renderer-1/) | すべてのレンダラーの抽象クラスを表します。 |
| [RenderingOptions](./renderingoptions/) | レンダリングオプションを表します。 |
| [SvgRenderer](./svgrenderer/) | SVG ドキュメントレンダラーを表します。 |
| [TextInfo](./textinfo/) | レンダリングされたテキストに関する情報を含みます。 |
## Structures

| 構造 | 説明 |
| --- | --- |
| [GlyphInfo](./glyphinfo/) | グリフに関する情報を含みます。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IDevice](./idevice/) | パス、テキスト、画像などのグラフィック要素のカスタムレンダリングをサポートするメソッドとプロパティを定義します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [AtPagePriority](./atpagepriority/) | ページサイズ宣言の適用順序の可能性を指定します。 |
| [FillRule](./fillrule/) | SVG と HTML のレンダリングで使用される塗りルールを指定します。 |
| [MediaType](./mediatype/) | レンダリング中に使用される可能性のあるメディアタイプを指定します。 |
| [PageLayoutOptions](./pagelayoutoptions/) | 他の PageSetup オプションと組み合わせてページのサイズとレイアウトを決定するフラグを指定します。これらのフラグは、説明に従って組み合わせることができます。 |
| [StrokeLineCap](./strokelinecap/) | SVG と HTML のレンダリングで使用されるラインキャップを指定します。 |
| [StrokeLineJoin](./strokelinejoin/) | SVG と HTML のレンダリングで使用されるラインジョインスタイルを指定します。 |
