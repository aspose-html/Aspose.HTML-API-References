---
title: Aspose.Html.Dom.Css
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Css名前空間はすべての CSS 関連操作用です CSS 公式ドキュメントで指定されている CSS プロパティ名  値ペア に集中しています
type: docs
weight: 70
url: /ja/net/aspose.html.dom.css/
---
**Aspose.Html.Dom.Css**名前空間はすべての CSS 関連操作用です。 CSS 公式ドキュメントで指定されている CSS プロパティ名 - 値ペア に集中しています。

## クラス

| クラス | 説明 |
| --- | --- |
| [Counter](./counter/) | Counter インターフェイスは、任意のカウンターまたはカウンター関数値を表すために使用されます。このインターフェイスは、基になるスタイル プロパティの値を反映します。 |
| [CSSPrimitiveValue](./cssprimitivevalue/) | CSSPrimitiveValue インターフェイスは、単一の CSS 値を表します。このインターフェイスを使用して、現在ブロックに設定されている特定のスタイル プロパティの値を決定したり、ブロック内で特定のスタイル プロパティを明示的に設定したりできます。このインターフェースのインスタンスは、CSSStyleDeclaration インターフェースの getPropertyCSSValue メソッドから取得できます。 CSSPrimitiveValue オブジェクトは、CSS プロパティのコンテキストでのみ発生します. |
| [CSSValue](./cssvalue/) | 単純または複雑な値を表します。 CSSValue オブジェクトは、CSS プロパティのコンテキストでのみ発生します. |
| [CSSValueList](./cssvaluelist/) | CSSValueList インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。 |
| [Rect](./rect/) | Rect インターフェイスは、任意の rect 値を表すために使用されます。このインターフェイスは、基になるスタイル プロパティの値を反映します。したがって、CSSPrimitiveValue オブジェクトに加えられた変更は、スタイル プロパティを変更します. |
| [RGBColor](./rgbcolor/) | RGBColor インターフェイスは、RGB カラー値を表すために使用されます。このインターフェイスは、基になるスタイル プロパティの値を反映します。したがって、CSSPrimitiveValue オブジェクトに加えられた変更は、スタイル プロパティを変更します. |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [ICSS2Properties](./icss2properties/) | 特定の HTML 要素のコンテキストで CSS2 プロパティ セット値操作のインターフェイスを提供します |
| [ICSSCharsetRule](./icsscharsetrule/) | CSSCharsetRule インターフェイスは、CSS スタイル シートの @charset ルールを表します。 encoding 属性の値は、DOM オブジェクト内のテキスト データのエンコーディングには影響しません。このエンコーディングは常に UTF-16 です。スタイルシートが読み込まれると、encoding 属性の値は @charset ルールで見つかった値になります。元のドキュメントに @charset がなかった場合、CSSCharsetRule は作成されません。 encoding 属性の値は、スタイル シートのシリアル化で使用されるエンコーディングのヒントとしても使用できます。 |
| [ICSSCounterStyleRule](./icsscounterstylerule/) | @counter-style ルールにより、作成者はカスタム カウンター スタイルを定義できます。 |
| [ICSSFontFaceRule](./icssfontfacerule/) | CSSFontFaceRule インターフェイスは、CSS スタイル シートの @font-face ルールを表します。 @font-face ルールは、一連のフォントの説明を保持するために使用されます。 |
| [ICSSImportRule](./icssimportrule/) | CSSImportRule インターフェイスは、CSS スタイル シート内の @import ルールを表します。 @import ルールは、他のスタイル シートからスタイル ルールをインポートするために使用されます。 |
| [ICSSKeyframeRule](./icsskeyframerule/) | CSSKeyframeRule インターフェイスは、単一のキーのスタイル ルールを表します。 |
| [ICSSKeyframesRule](./icsskeyframesrule/) | CSSKeyframesRule インターフェイスは、1 つのアニメーションの完全なキーフレーム セットを表します |
| [ICSSMarginRule](./icssmarginrule/) | CSSMarginRule インターフェースはマージンアットルールを表します. |
| [ICSSMediaRule](./icssmediarule/) | CSSMediaRule インターフェイスは、CSS スタイル シートの @media ルールを表します。 @media ルールを使用して、特定のメディア タイプのスタイル ルールを区切ることができます。 |
| [ICSSPageRule](./icsspagerule/) | CSSPageRule インターフェイスは、CSS スタイル シート内の @page ルールを表します。 @page ルールは、ページ付きメディアのページ ボックスの寸法、方向、余白などを指定するために使用されます。 |
| [ICSSRule](./icssrule/) | CSSRule インターフェイスは、あらゆるタイプの CSS ステートメントの抽象基本インターフェイスです。これには、規則セットと @ 規則の両方が含まれます。ルールがパーサーによって認識されない場合でも、実装は CSS スタイル シートで指定されたすべてのルールを保持することが期待されます。認識されていないルールは、!:ICSSUnknownRuleインターフェイス. |
| [ICSSRuleList](./icssrulelist/) | CSSRuleList インターフェイスは、CSS ルールの順序付けられたコレクションの抽象化を提供します。 |
| [ICSSStyleDeclaration](./icssstyledeclaration/) | CSSStyleDeclaration インターフェイスは、単一の CSS 宣言ブロックを表します。このインターフェイスを使用して、現在ブロックに設定されているスタイル プロパティを特定したり、ブロック内でスタイル プロパティを明示的に設定したりできます。 |
| [ICSSStyleRule](./icssstylerule/) | CSSStyleRule インターフェイスは、CSS スタイル シートに設定された単一のルールを表します。 |
| [ICSSStyleSheet](./icssstylesheet/) | CSSStyleSheet インターフェイスは、CSS スタイル シート、つまりコンテンツ タイプが「text/css」のスタイル シートを表すために使用される具体的なインターフェイスです。 |
| [ICSSUnknownRule](./icssunknownrule/) | CSSUnknownRule インターフェイスは、このユーザー エージェントでサポートされていない @-規則を表します。 |
| [ICSSValueList](./icssvaluelist/) | インターフェイスは、CSS 値の順序付けられたコレクションの抽象化を提供します。 |
| [IDocumentCSS](./idocumentcss/) | このインターフェイスは、CSS ビューを持つドキュメントを表します。 |
| [IDocumentStyle](./idocumentstyle/) | DocumentStyle インターフェイスは、ドキュメントに埋め込まれたスタイル シートを取得できるメカニズムを提供します。 Document インターフェースのインスタンスでバインド固有のキャスト メソッドを使用して、DocumentStyle インターフェースのインスタンスを取得できることが期待されます。 |
| [IElementCSSInlineStyle](./ielementcssinlinestyle/) | 要素に添付されたインライン スタイル情報は、style 属性を通じて公開されます。これは、HTML 要素 (または同じ方法で STYLE 属性を使用する他のスキーマまたは DTD の要素) の STYLE 属性の内容を表します。 |
| [ILinkStyle](./ilinkstyle/) | LinkStyle インターフェイスは、ドキュメントへのリンクを担当するノードからスタイル シートを取得できるメカニズムを提供します。 LinkStyle インターフェイスのインスタンスは、リンク ノード (DOM レベル 2 の HTMLLinkElement、HTMLStyleElement、または ProcessingInstruction) のインスタンスでバインディング固有のキャスト メソッドを使用して取得できます。 |
| [IMediaList](./imedialist/) | MediaList インターフェイスは、このコレクションの実装方法を定義または制約することなく、順序付けられたメディアのコレクションの抽象化を提供します。空のリストは、メディア「all」を含むリストと同じです. |
| [IStyleSheet](./istylesheet/) | StyleSheet インターフェイスは、あらゆるタイプのスタイル シートの抽象ベース インターフェイスです。構造化ドキュメントに関連付けられた単一のスタイル シートを表します。 |
| [IStyleSheetList](./istylesheetlist/) | StyleSheetList インターフェイスは、スタイル シートの順序付けられたコレクションの抽象化を提供します。 |
| [IViewCSS](./iviewcss/) | このインターフェイスは CSS ビューを表します。 |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [CSSEngineMode](./cssenginemode/) | CSSEngine モードを指定します |


