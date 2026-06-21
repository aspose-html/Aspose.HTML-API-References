---
title: "com.aspose.html.dom.svg"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg パッケージのすべてのクラスは w3c SVG2 推奨事項に基づいています。このパッケージを使用すると、要件に応じて SVG ファイルを読み込み、ナビゲート、またはレンダリングできます。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/
---
**com.aspose.html.dom.svg** パッケージのすべてのクラスは、W3C SVG2 勧告に基づいています。このパッケージを使用すると、要件に応じて SVG ファイルを読み込み、ナビゲート、またはレンダリングできます。

## クラス

| クラス | 説明 |
| --- | --- |
| [SVGAElement](./svgaelement/) | SVGAElement インターフェイスは ‘a’ 要素に対応します。 |
| [SVGAnimateElement](./svganimateelement/) | SVGAnimateElement インターフェイスは ‘animate’ 要素に対応します。SVG DOM を介した ‘animate’ 要素の属性へのオブジェクト指向アクセスは利用できません。 |
| [SVGAnimateMotionElement](./svganimatemotionelement/) | SVGAnimateMotionElement インターフェイスは ‘animateMotion’ 要素に対応します。SVG DOM を介した ‘animateMotion’ 要素の属性へのオブジェクト指向アクセスは利用できません。 |
| [SVGAnimateTransformElement](./svganimatetransformelement/) | SVGAnimateTransformElement インターフェイスは ‘animateTransform’ 要素に対応します。SVG DOM を介した ‘animateTransform’ 要素の属性へのオブジェクト指向アクセスは利用できません。 |
| [SVGAnimationElement](./svganimationelement/) | SVGAnimationElement インターフェイスは、すべてのアニメーション要素インターフェイス（SVGAnimateElement、SVGSetElement、SVGAnimateColorElement、SVGAnimateMotionElement、SVGAnimateTransformElement）の基底インターフェイスです。 |
| [SVGCircleElement](./svgcircleelement/) | SVGCircleElement インターフェイスは ‘circle’ 要素に対応します。 |
| [SVGClipPathElement](./svgclippathelement/) | SVGClipPathElement インターフェイスは ‘clipPath’ 要素に対応します。 |
| [SVGComponentTransferFunctionElement](./svgcomponenttransferfunctionelement/) | このインターフェイスは、コンポーネント転送関数インターフェイスで使用される基底インターフェイスを定義します。 |
| [SVGCursorElement](./svgcursorelement/) | SVGCursorElement インターフェイスは ‘cursor’ 要素に対応します。 |
| [SVGDefsElement](./svgdefselement/) | SVGDefsElement インターフェイスは ‘defs’ 要素に対応します。 |
| [SVGDescElement](./svgdescelement/) | SVGDescElement インターフェイスは ‘desc’ 要素に対応します。 |
| [SVGDocument](./svgdocument/) | `SVGDocument` は SVG 階層のルートであり、全体のコンテンツを保持します。階層へのアクセスを提供するだけでなく、ドキュメントから特定の情報セットにアクセスするための便利なメソッドもいくつか提供します。他のパッケージからのドキュメントのコンポーネントとして ‘svg’ 要素がインラインで埋め込まれる場合、例えば ‘svg’ 要素が XHTML ドキュメント [XHTML] 内にインラインで埋め込まれる場合、`SVGDocument` オブジェクトは存在しません。その代わりに、ドキュメントオブジェクト階層のルートオブジェクトは、HTMLDocument オブジェクトなど別のタイプの Document オブジェクトになります。ただし、XML ドキュメント階層のルート要素が ‘svg’ 要素である場合、例えば単独の SVG ファイル（MIME タイプ \"image/svg+xml\" のファイル）を表示するときは、`SVGDocument` オブジェクトが確実に存在し、この場合 `SVGDocument` オブジェクトがドキュメントオブジェクトモデル階層のルートオブジェクトとなります。 |
| [SVGElement](./svgelement/) | SVG DOM のインターフェイスで、SVG 言語の要素に直接対応するもの（例： ‘path’ 要素の SVGPathElement インターフェイス）はすべて SVGElement インターフェイスから派生します。 |
| [SVGElementInstance](./svgelementinstance/) | 各 use 要素のシャドウツリーのルートオブジェクトは SVGUseElementShadowRoot インターフェイスを実装します。このインターフェイスは現在、ShadowRoot インターフェイスおよび DocumentOrShadowRoot ミックスインで定義されたプロパティやメソッドへの拡張を定義していません。ただし、このノードを根とするツリーは、作者スクリプトから見ると完全に読み取り専用です。 |
| [SVGEllipseElement](./svgellipseelement/) | SVGEllipseElement インターフェイスは ‘ellipse’ 要素に対応します。 |
| [SVGException](./svgexception/) | 特定の SVG 操作を実行できない場合にこの例外が発生します。 |
| [SVGFilterElement](./svgfilterelement/) | SVGFilterElement インターフェイスは ‘filter’ 要素に対応します。 |
| [SVGForeignObjectElement](./svgforeignobjectelement/) | SVGForeignObjectElement インターフェイスは ‘foreignObject’ 要素に対応します。 |
| [SVGGElement](./svggelement/) | SVGGElement インターフェイスは ‘g’ 要素に対応します。 |
| [SVGGeometryElement](./svggeometryelement/) | SVGGeometryElement インターフェイスは、等価のパスで定義されたジオメトリにより描画が決定され、塗りつぶしやストロークが可能な SVG 要素を表します。これにはパスや基本形状が含まれます。 |
| [SVGGradientElement](./svggradientelement/) | SVGGradientElement インターフェイスは、SVGLinearGradientElement と SVGRadialGradientElement が使用する基底インターフェイスです。 |
| [SVGGraphicsElement](./svggraphicselement/) | SVGGraphicsElement インターフェイスは、主にグループ内に直接グラフィックを描画することを目的とした SVG 要素を表します。 |
| [SVGImageElement](./svgimageelement/) | SVGImageElement インターフェイスは ‘image’ 要素に対応します。 |
| [SVGLinearGradientElement](./svglineargradientelement/) | SVGLinearGradientElement インターフェイスは ‘linearGradient’ 要素に対応します。 |
| [SVGLineElement](./svglineelement/) | SVGLineElement インターフェイスは ‘line’ 要素に対応します。 |
| [SVGMarkerElement](./svgmarkerelement/) | SVGMarkerElement インターフェイスは ‘marker’ 要素に対応します。 |
| [SVGMaskElement](./svgmaskelement/) | SVGMaskElement インターフェイスは ‘mask’ 要素に対応します。 |
| [SVGMetadataElement](./svgmetadataelement/) | SVGMetadataElement インターフェイスは ‘metadata’ 要素に対応します。 |
| [SVGMPathElement](./svgmpathelement/) | SVGMPathElement インターフェイスは ‘mpath’ 要素に対応します。 |
| [SVGPathElement](./svgpathelement/) | SVGPathElement インターフェイスは ‘path’ 要素に対応します。 |
| [SVGPatternElement](./svgpatternelement/) | SVGPatternElement インターフェイスは ‘pattern’ 要素に対応します。 |
| [SVGPolygonElement](./svgpolygonelement/) | SVGPolygonElement インターフェイスは ‘polygon’ 要素に対応します。 |
| [SVGPolylineElement](./svgpolylineelement/) | SVGPolylineElement インターフェイスは ‘polyline’ 要素に対応します。 |
| [SVGRadialGradientElement](./svgradialgradientelement/) | SVGRadialGradientElement インターフェイスは ‘radialGradient’ 要素に対応します。 |
| [SVGRectElement](./svgrectelement/) | SVGRectElement インターフェイスは ‘rect’ 要素に対応します。 |
| [SVGScriptElement](./svgscriptelement/) | SVGScriptElement インターフェイスは ‘script’ 要素に対応します。 |
| [SVGSetElement](./svgsetelement/) | SVGSetElement インターフェイスは ‘set’ 要素に対応します。SVG DOM を介した ‘set’ 要素の属性へのオブジェクト指向アクセスは利用できません。 |
| [SVGStopElement](./svgstopelement/) | SVGStopElement インターフェイスは ‘stop’ 要素に対応します。 |
| [SVGStyleElement](./svgstyleelement/) | SVGStyleElement インターフェイスは ‘style’ 要素に対応します。 |
| [SVGSVGElement](./svgsvgelement/) | 主要なインターフェイス定義は SVGSVGElement インターフェイスで、‘svg’ 要素に対応するインターフェイスです。このインターフェイスには、行列演算や視覚レンダリングデバイスでの再描画時間を制御する機能など、さまざまな一般的に使用されるユーティリティメソッドが含まれています。 |
| [SVGSwitchElement](./svgswitchelement/) | SVGSwitchElement インターフェイスは ‘switch’ 要素に対応します。 |
| [SVGSymbolElement](./svgsymbolelement/) | SVGSymbolElement インターフェイスは ‘symbol’ 要素に対応します。 |
| [SVGTextContentElement](./svgtextcontentelement/) | SVGTextContentElement は、SVGTextElement、SVGTSpanElement、SVGTRefElement、SVGAltGlyphElement、SVGTextPathElement などのさまざまなテキスト関連インターフェイスで継承されます。このインターフェイスのメソッドで文字のインデックスや文字数を参照する場合、これらはそれぞれ UTF-16 コード単位へのインデックスまたは UTF-16 コード単位の数として解釈されます。これは、CharacterData インターフェイスのメソッドが文字データ内でインデックスやカウントに UTF-16 コード単位を使用する DOM Level 2 Core と一貫性を保つためです。したがって、例えば ‘text’ 要素のテキスト内容が単一の非 BMP 文字（例：U+10000）である場合、その要素で getNumberOfChars を呼び出すと、1 文字を表すのに使用される 2 つの UTF-16 コード単位（サロゲートペア）があるため、結果は 2 が返されます。 |
| [SVGTextElement](./svgtextelement/) | SVGTextElement インターフェイスは ‘text’ 要素に対応します。 |
| [SVGTextPathElement](./svgtextpathelement/) | SVGTextPathElement インターフェイスは ‘textPath’ 要素に対応します。 |
| [SVGTextPositioningElement](./svgtextpositioningelement/) | SVGTextPositioningElement インターフェイスは、テキスト関連インターフェイスである SVGTextElement、SVGTSpanElement、SVGTRefElement、SVGAltGlyphElement に継承されます。 |
| [SVGTitleElement](./svgtitleelement/) | SVGTitleElement インターフェイスは ‘title’ 要素に対応します。 |
| [SVGTSpanElement](./svgtspanelement/) | SVGTSpanElement インターフェイスは ‘tspan’ 要素に対応します。 |
| [SVGUseElement](./svguseelement/) | SVGUseElement インターフェイスは ‘use’ 要素に対応します。 |
| [SVGViewElement](./svgviewelement/) | SVGViewElement インターフェイスは ‘view’ 要素に対応します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [ISVGAnimatedPoints](./isvganimatedpoints/) | SVGAnimatedPoints インターフェイスは、‘points’ 属性を持ち、座標値のリストを保持し、その属性をアニメーション化する機能をサポートする要素を対象としています。さらに、XML DOM（例: getAttribute() メソッド呼び出しを使用）でアクセスした元の要素の ‘points’ 属性は、ポイントに加えられた変更を反映します。 |
| [ISVGFitToViewBox](./isvgfittoviewbox/) | Interface SVGFitToViewBox は、‘viewBox’ と ‘preserveAspectRatio’ という XML 属性を持つ要素に適用される DOM 属性を定義します。 |
| [ISVGRenderingIntent](./isvgrenderingintent/) | SVGRenderingIntent インターフェイスは、‘rendering-intent’ 属性またはディスクリプタの可能な値の列挙リストを定義します。 |
| [ISVGTests](./isvgtests/) | Interface SVGTests は、‘requiredFeatures’、‘requiredExtensions’、‘systemLanguage’ 属性を持つすべての要素に適用されるインターフェイスを定義します。 |
| [ISVGUnitTypes](./isvgunittypes/) | SVGUnitTypes インターフェイスは、一般的に使用される定数のセットを定義し、SVGGradientElement、SVGPatternElement、SVGClipPathElement、SVGMaskElement、SVGFilterElement が使用する基底インターフェイスです。 |
| [ISVGURIReference](./isvgurireference/) | Interface SVGURIReference は、‘xlink:href’ などの XLink 属性のコレクションを持ち、URI 参照を定義するすべての要素に適用されるインターフェイスを定義します。 |
| [ISVGZoomAndPan](./isvgzoomandpan/) | SVGZoomAndPan インターフェイスは、属性 zoomAndPan とそれに関連する定数を定義します。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [SVGRenderingIntent](./svgrenderingintent/) | SVGRenderingIntent 列挙体は、‘rendering-intent’ 属性またはディスクリプタの可能な値の列挙リストを定義します。 |
| [SVGUnitTypes](./svgunittypes/) | SVGUnitTypes 列挙体は、一般的に使用される定数のセットを定義し、SVGGradientElement、SVGPatternElement、SVGClipPathElement、SVGMaskElement、SVGFilterElement が使用する基底インターフェイスです。 |
| [SVGZoomAndPan](./svgzoomandpan/) | SVGZoomAndPan 列挙体は、属性 zoomAndPan とそれに関連する定数を定義します。 |
