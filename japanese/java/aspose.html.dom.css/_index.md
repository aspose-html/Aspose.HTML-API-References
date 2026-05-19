---
title: "com.aspose.html.dom.css"
second_title: "Aspose.HTML for Java API リファレンス"
description: "DOM Level 2 スタイル仕様のインターフェイスを提供します。Cascading Style Sheets（CSS）は、著者やユーザーがフォントや間隔などのスタイルを HTML 文書や XML アプリケーションなどの構造化文書に付加できるスタイルシート言語です。メディア固有のスタイルシートをサポートしており、著者は視覚ブラウザー、音声デバイス、プリンター、点字デバイス、ハンドヘルドデバイスなど向けに文書の表示を調整できます。また、コンテンツの位置決めやテーブルレイアウト、国際化機能、ユーザーインターフェイスに関連するいくつかのプロパティもサポートしています。文書のプレゼンテーションスタイルとコンテンツを分離することで、CSS は Web の著者作業とサイトの保守を簡素化します。"
type: docs

url: /ja/java/com.aspose.html.dom.css/
---
DOM Level 2 スタイル仕様のためのインターフェイスを提供します。カスケーディングスタイルシート（CSS）は、著者やユーザーが構造化ドキュメント（HTML ドキュメントや XML アプリケーションなど）にスタイル（フォントや間隔など）を付与できるスタイルシート言語です。メディア固有のスタイルシートをサポートし、著者は視覚ブラウザ、音声デバイス、プリンター、点字デバイス、ハンドヘルドデバイスなど向けに文書の表示を調整できます。また、コンテンツの位置指定、テーブルレイアウト、国際化機能、ユーザーインターフェイスに関連するプロパティもサポートします。文書のプレゼンテーションスタイルとコンテンツを分離することで、CSS は Web の作成とサイトの保守を簡素化します。

## クラス

| クラス | 説明 |
| --- | --- |
| [Counter](./counter/) | Counter インターフェイスは、任意のカウンタまたは counters 関数の値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。 |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue インターフェイスは CSSValue インターフェイスから派生し、CSS プロパティの現在の計算値を表します。 |
| [CSSValue](./cssvalue/) | 単純または複合的な値を表します。CSSValue オブジェクトは CSS プロパティのコンテキスト内でのみ出現します。 |
| [CSSValueList](./cssvaluelist/) | CSSValueList インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。 |
| [Rect](./rect/) | Rect インターフェイスは任意の rect 値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。そのため、[`CSSPrimitiveValue`](../com.aspose.html.dom.css/cssprimitivevalue/) オブジェクトへの変更はスタイルプロパティを変更します。 |
| [RGBColor](./rgbcolor/) | RGBColor インターフェイスは任意の RGB カラー値を表すために使用されます。このインターフェイスは基礎となるスタイルプロパティの値を反映します。そのため、CSSPrimitiveValue オブジェクトへの変更はスタイルプロパティを変更します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | `CSS2Properties` インターフェイスは、[`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) 内のプロパティを取得および設定するための便利なメカニズムを表します。このインターフェイスの属性は CSS2 で指定されたすべてのプロパティに対応しています。このインターフェイスの属性を取得することは、[`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) インターフェイスの `getPropertyValue` メソッドを呼び出すことと同等です。このインターフェイスの属性を設定することは、[`CSSStyleDeclaration`](../com.aspose.html.dom.css/icssstyledeclaration/) インターフェイスの `setProperty` メソッドを呼び出すことと同等です。 |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule インターフェイスは CSS スタイルシート内の @charset ルールを表します。encoding 属性の値は DOM オブジェクト内のテキストデータのエンコーディングには影響せず、エンコーディングは常に UTF-16 です。スタイルシートが読み込まれた後、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset が存在しなかった場合、CSSCharsetRule は作成されません。encoding 属性の値は、スタイルシートのシリアライズ時に使用されるエンコーディングのヒントとしても使用されることがあります。 |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | CSSCounterStyleRule インターフェイスは、著者がカスタムカウンタスタイルを定義できる @counter-style アットルールを表します。 |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule インターフェイスは CSS スタイルシート内の @font-face ルールを表します。@font-face ルールはフォント記述のセットを保持するために使用されます。 |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule インターフェイスは CSS スタイルシート内の @import ルールを表します。@import ルールは他のスタイルシートからスタイルルールをインポートするために使用されます。 |
| [ICSSKeyframeRule](./icsskeyframerule/) | [`CSSKeyframeRule`](../com.aspose.html.dom.css/icsskeyframerule/) インターフェイスは、特定のキーフレームに対するスタイルのセットを表すオブジェクトを記述します。これは @keyframes アットルールの単一キーフレームの内容に対応します。 |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframeRule インターフェイスの name プロパティは、animation-name プロパティで使用されるアニメーションの名前を取得および設定します。 |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule インターフェイスは、@page アットルール内のマージンアットルール（例: @top-left）を表します。 |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule インターフェイスは CSS スタイルシート内の @media ルールを表します。@media ルールは特定のメディアタイプ向けにスタイルルールを区切るために使用できます。 |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule インターフェイスは CSS スタイルシート内の @page ルールを表します。@page ルールは、ページングメディア用のページボックスの寸法、向き、余白などを指定するために使用されます。 |
| [ICSSRule](./icssrule/) | CSSRule インターフェイスは、あらゆる種類の CSS 文の抽象基底インターフェイスです。これにはルールセットとアットルールの両方が含まれます。実装は、パーサーが認識しない場合でも、CSS スタイルシートで指定されたすべてのルールを保持することが期待されます。認識されないルールはこのインターフェイスで表現されます。 |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList は、読み取り専用の [`CSSRule`](../com.aspose.html.dom.css/icssrule/) オブジェクトの順序付けられたコレクションを表します。 |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration インターフェイスは、CSS 宣言ブロックであるオブジェクトを表し、スタイル情報およびさまざまなスタイル関連のメソッドやプロパティを公開します。 |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule インターフェイスは、単一の CSS スタイルルールを表します。selectorText 属性は取得時に、関連付けられたセレクタのグループをシリアライズした結果を返さなければなりません。 |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet インターフェイスは、単一の CSS スタイルシートを表し、スタイルシートに含まれるルールのリストを検査および変更できるようにします。親である [`IStyleSheet`](../com.aspose.html.dom.css/istylesheet/) からプロパティとメソッドを継承します。 |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule インターフェイスは、このユーザーエージェントでサポートされていない at-rule を表します。 |
| [ICSSValueList](./icssvaluelist/) | CSSValueList インターフェイスは、[`CSSValue`](../com.aspose.html.dom.css/cssvalue/) インターフェイスから派生し、CSS 値の順序付きコレクションの抽象化を提供します。 |
| [IDocumentCSS](./idocumentcss/) | このインターフェイスは、CSS ビューを持つドキュメントを表します。 |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle インターフェイスは、ドキュメントに埋め込まれたスタイルシートを取得するためのメカニズムを提供します。DocumentStyle インターフェイスのインスタンスは、Document インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用して取得できると想定されています。 |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 要素に付随するインラインスタイル情報は style 属性を通じて公開されます。これは HTML 要素の STYLE 属性の内容（または同様の方法で STYLE 属性を使用する他のスキーマや DTD の要素）を表します。要素がインライン CSS スタイル情報をサポートしている場合、ElementCSSInlineStyle インターフェイスのインスタンスは、Element インターフェイスのインスタンスに対してバインディング固有のキャストメソッドを使用して取得できると想定されています。 |
| [ILinkStyle](./ilinkstyle/) | LinkStyle インターフェイスは、ドキュメントにリンクしているノードからスタイルシートを取得するためのメカニズムを提供します。LinkStyle インターフェイスのインスタンスは、リンクノード（HTMLLinkElement、 のインスタンスに対してバインディング固有のキャストメソッドを使用して取得できます。 |
| [IMediaList](./imedialist/) | MediaList インターフェイスは、メディアの順序付きコレクションの抽象化を提供し、このコレクションがどのように実装されるかを定義または制約しません。空のリストは、メディア \"all\" を含むリストと同じです。 |
| [IStyleSheet](./istylesheet/) | StyleSheet インターフェイスは、あらゆるタイプのスタイルシートの抽象基底インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイルシートを表します。HTML では、StyleSheet インターフェイスは HTML LINK 要素を介して含まれる外部スタイルシート、またはインライン STYLE 要素のいずれかを表します。XML では、このインターフェイスはスタイルシート処理命令を介して含まれる外部スタイルシートを表します。CSS スタイルシートは、さらに特化された [`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) インターフェイスを実装します。 |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList インターフェイスは、[`CSSStyleSheet`](../com.aspose.html.dom.css/icssstylesheet/) オブジェクトのリストを表します。このオブジェクトのインスタンスは、[`Document.styleSheets`](../com.aspose.html.dom/document/stylesheets/) によって返される可能性があります。 |
| [IViewCSS](./iviewcss/) | IViewCSS インターフェイスは、Window オブジェクトへの拡張を表し、要素のすべての CSS プロパティの値にアクセスできるようにします。 |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | CSSEngine モードを指定します。値は以下の意味を持ちます： |
