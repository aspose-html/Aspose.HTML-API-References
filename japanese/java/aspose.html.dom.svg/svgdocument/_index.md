---
title: "SVGDocument クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.SVGDocument クラス。SVGDocument は SVG 階層のルートであり、全コンテンツを保持します。階層へのアクセスを提供するだけでなく、ドキュメントから特定の情報セットにアクセスするための便利なメソッドもいくつか提供します。svg 要素が別パッケージのドキュメントのコンポーネントとしてインラインで埋め込まれる場合（例：XHTML ドキュメント内にインラインで埋め込まれた svg 要素）、SVGDocument オブジェクトは存在せず、ドキュメントオブジェクト階層のルートオブジェクトは HTMLDocument などの別タイプの Document オブジェクトになります。ただし、XML ドキュメント階層のルート要素が svg 要素である場合（例：単独の SVG ファイル、すなわち MIME タイプ image/svgxml のファイルを表示する場合）には、SVGDocument オブジェクトが確実に存在し、この場合 SVGDocument オブジェクトがドキュメントオブジェクトモデル階層のルートオブジェクトとなります。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgdocument/
---
## SVGDocument class

`SVGDocument` は SVG 階層のルートであり、全体のコンテンツを保持します。階層へのアクセスを提供するだけでなく、ドキュメントから特定の情報セットにアクセスするための便利なメソッドもいくつか提供します。他のパッケージからのドキュメントのコンポーネントとして ‘svg’ 要素がインラインで埋め込まれる場合、例えば ‘svg’ 要素が XHTML ドキュメント [XHTML] 内にインラインで埋め込まれる場合、`SVGDocument` オブジェクトは存在しません。その代わりに、ドキュメントオブジェクト階層のルートオブジェクトは、HTMLDocument オブジェクトなど別のタイプの Document オブジェクトになります。ただし、XML ドキュメント階層のルート要素が ‘svg’ 要素である場合、例えば単独の SVG ファイル（MIME タイプ \"image/svg+xml\" のファイル）を表示するときは、`SVGDocument` オブジェクトが確実に存在し、この場合 `SVGDocument` オブジェクトがドキュメントオブジェクトモデル階層のルートオブジェクトとなります。

```java
public class SVGDocument : Document, IDocumentCSS
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SVGDocument](svgdocument/#constructor)() | 新しい `SVGDocument` クラスのインスタンスを初期化します。 |
| [SVGDocument](svgdocument/#constructor_1)(Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。 |
| [SVGDocument](svgdocument/#constructor_2)(RequestMessage) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_10)(String) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_4)(Url) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_3)(RequestMessage, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_8)(Stream, String) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [SVGDocument](svgdocument/#constructor_6)(Stream, Url) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [SVGDocument](svgdocument/#constructor_11)(String, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_14)(String, String) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_12)(String, Url) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_5)(Url, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_9)(Stream, String, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [SVGDocument](svgdocument/#constructor_7)(Stream, Url, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [SVGDocument](svgdocument/#constructor_15)(String, String, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |
| [SVGDocument](svgdocument/#constructor_13)(String, Url, Configuration) | 新しい `SVGDocument` クラスのインスタンスを初期化します。コンストラクタは同期的に動作し、すべての外部リソース（画像、スクリプト等）の読み込みが完了するまで待機します。ドキュメントを非同期に読み込むには [`Navigate`](../../com.aspose.html.dom/document/navigate/) メソッドまたはそのオーバーロードを使用します。また、[`Security`](../../com.aspose.html.dom/ibrowsingcontext/security/) で適切なフラグを設定することで、一部の外部リソースの読み込みを無効にすることもできます。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) このノードの絶対ベース URI、取得できなかった場合は null。 |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) ドキュメントのエンコーディングを取得します。 |
| [getCharset](../../com.aspose.html.dom/document/charset/) ドキュメントのエンコーディングを取得します。 |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) この要素の子要素ノード（nodeType が 1 のもの）の現在の数を返します。子ノードが存在しない場合は 0 を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/document/children/) 子要素を返します。 |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) ドキュメントのコンテンツタイプを取得します。 |
| [getContext](../../com.aspose.html.dom/document/context/) 現在の閲覧コンテキストを取得します。 |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Document インターフェイスの defaultView IDL 属性は、取得時に、この Document に関連付けられた閲覧コンテキストがある場合はその閲覧コンテキストの WindowProxy オブジェクトを返し、そうでない場合は null を返す必要があります。 |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) このドキュメントに関連付けられた文書型宣言 (Document Type Declaration)。 |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) これは、ドキュメントの文書要素である子ノードへ直接アクセスできる便利な属性です。 |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) ドキュメントの場所、未定義の場合や DOMImplementation.createDocument を使用して作成されたドキュメントの場合は null。 |
| [getDomain](../../com.aspose.html.dom.svg/svgdocument/domain/) ドキュメントを提供したサーバーのドメイン名、ドメイン名でサーバーを特定できない場合は null 文字列。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null。 |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) このドキュメントを処理する DOMImplementation オブジェクト。 |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) ドキュメントのエンコーディングを取得します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) と [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](../../com.aspose.html.dom/document/createelement/) のような DOM Level 1 メソッドで作成されたノードについては、常に null です。 |
| [getLocation](../../com.aspose.html.dom/document/location/) ドキュメントの場所。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く要素兄弟ノードがない場合は null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 nextSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) このノードの名前（タイプに応じて）。 |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) 基になるオブジェクトのタイプを表すコード。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../../com.aspose.html.dom/node/)` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getOrigin](../../com.aspose.html.dom/document/origin/) ドキュメントのオリジンを取得します。 |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) 所有ドキュメントを取得します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 parentElement プロパティは、DOM ノードの親 [`Element`](../../com.aspose.html.dom/element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある要素兄弟ノードがない場合は null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 previousSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/firstchild/) リストで指定されたノードの直前にあるノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) ドキュメントの準備状態を返します。Document が読み込み中のときは "loading"、解析が完了したがサブリソースの読み込みが続いているときは "interactive"、完全に読み込まれたときは "complete"。 |
| [getReferrer](../../com.aspose.html.dom.svg/svgdocument/referrer/) このページへのリンク元ページの URI を返します。ユーザーが直接（リンク経由ではなく、たとえばブックマークから）ページに移動した場合、値は空文字列です。 |
| [getRootElement](../../com.aspose.html.dom.svg/svgdocument/rootelement/) ドキュメント階層のルート ‘svg’。 |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) ドキュメントに明示的にリンクまたは埋め込まれたすべてのスタイルシートを含むリストです。HTML ドキュメントの場合、外部スタイルシート（HTML LINK 要素で含まれる）とインライン STYLE 要素が含まれます。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | [`Node`](../../com.aspose.html.dom/node/) インターフェイスの textContent プロパティは、ノードとその子孫のテキストコンテンツを表します。 |
| [getTitle](../../com.aspose.html.dom.svg/svgdocument/title/) ドキュメントのタイトルは、‘svg’ ルート要素の ‘title’ サブ要素で指定されます（例: Here is the title...）。 |
| [getURL](../../com.aspose.html.dom.svg/svgdocument/url/) ドキュメントの完全な URI です。 |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配送されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Document.createAttribute() メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [`Attr`](../../com.aspose.html.dom/attr/) インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [Attr](T:com.aspose.html.dom.Attr) インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | 指定された文字列を値とする [`CDATASection`](../../com.aspose.html.dom/cdatasection/) ノードを作成します。 |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | 指定された文字列を使用して [`Comment`](../../com.aspose.html.dom/comment/) ノードを作成します。 |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | DOM ノードを追加してオフスクリーン DOM ツリーを構築できる、新しい空の [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) を作成します。 |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | このメソッドは [`DocumentType`](../../com.aspose.html.dom/documenttype/) オブジェクトを返します。このオブジェクトはドキュメント作成時に DOMImplementation.createDocument と共に使用できるか、Node.insertBefore() や Node.replaceChild() などのメソッドでドキュメントに挿入できます。 |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | HTML ドキュメントでは、document.createElement() メソッドは tagName で指定された HTML 要素を作成します。tagName が認識されない場合は [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) が作成されます。 |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | 指定された修飾名とパッケージ URI の要素を作成します。 |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | EntityReference オブジェクトを作成します。さらに、参照されたエンティティが既知の場合、EntityReference ノードの子リストは対応する Entity ノードと同じになります。 |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | 実装がサポートするタイプの [`Event`](../../com.aspose.html.dom.events/event/) を作成します。 |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | 解決されたパッケージを持つ解析済み XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式の文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できます。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | 任意の DOM ノードをパッケージ解決に適応させ、XPath 式をそのノードが文書内に現れたコンテキストに対して簡単に評価できるようにします。このアダプタは、DOM Level 3 の `lookupNamespaceURI` メソッドと同様に機能し、呼び出し時点でノード階層に利用可能な情報を使用して、指定されたプレフィックスから packageURI を解決し、暗黙の xml プレフィックスも正しく解決します。 |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | 指定された名前とデータ文字列を使用して ProcessingInstruction ノードを作成します。 |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | 指定された文字列を使用して Text ノードを作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | XPath 式の文字列を評価し、可能であれば指定された型の結果を返します。 |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document の getElementById() メソッドは、id プロパティが指定された文字列と一致する要素を表す [`Element`](../../com.aspose.html.dom/element/) オブジェクトを返します。要素 ID は指定された場合は一意である必要があるため、特定の要素に迅速にアクセスする便利な方法です。 |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | [`Document`](../../com.aspose.html.dom/document/) インターフェイスの getElementsByClassName メソッドは、指定されたクラス名すべてを持つすべての子要素の配列に似たオブジェクトを返します。 |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | [`Document`](../../com.aspose.html.dom/document/) インターフェイスの getElementsByTagName メソッドは、指定されたタグ名を持つ要素の [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) を返します。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | 指定されたパッケージに属する、指定されたタグ名を持つ要素のリストを返します。ルートノードを含む文書全体が検索されます。 |
| [getOverrideStyle](../../com.aspose.html.dom.svg/svgdocument/getoverridestyle/)(Element, String) | このメソッドは、指定された要素および指定された疑似要素のオーバーライドスタイル宣言を取得するために使用されます。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() メソッドは、Node インターフェイスのもので、指定された [`Node`](../../com.aspose.html.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | 別のドキュメントからノードをこのドキュメントにインポートします。元のドキュメントのソースノードは変更または削除されず、このメソッドはソースノードの新しいコピーを作成します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。そのパッケージが対象ノードのデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが同じ型で、定義上の特性（要素の場合は ID、子の数など）が同じで、属性が一致するなどの場合に等しいとみなされます。必要なデータポイントの具体的な集合は、ノードの種類によって異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node インターフェイスの isSameNode() メソッドは、=== 厳密等価演算子のレガシーエイリアスです。つまり、2 つのノードが同一か（同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node インターフェイスの lookupNamespaceURI() メソッドは、プレフィックスをパラメータとして受け取り、対象ノード上でそれに関連付けられたパッケージ URI を見つけた場合に返し（見つからなければ null を返します）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node インターフェイスの lookupPrefix() メソッドは、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し（存在しなければ null）、複数のプレフィックスが可能な場合は最初のプレフィックスが返されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(RequestMessage) | 指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String) | 指定された Uniform Resource Locator (URL) のドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Url) | 指定された Uniform Resource Locator (URL) のドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, String) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(Stream, Url) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, String) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/)(String, Url) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../../com.aspose.html.dom/text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが [`Text`](../../com.aspose.html.dom/text/) ノードを分離する「正規」形に変換します。つまり、隣接した Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の Element を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての Element の NodeList を返します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [renderTo](../../com.aspose.html.dom.svg/svgdocument/renderto/)(IDevice) | このメソッドは、現在のドキュメントの内容を指定されたデバイスに印刷するために使用されます。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合、最初に削除されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save)(ResourceHandler) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_6)(String) | `path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_3)(Url) | `url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_1)(ResourceHandler, SVGSaveFormat) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_2)(ResourceHandler, SVGSaveOptions) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_7)(String, SVGSaveFormat) | `path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_8)(String, SVGSaveOptions) | `path` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_4)(Url, SVGSaveFormat) | `url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [save](../../com.aspose.html.dom.svg/svgdocument/save/#save_5)(Url, SVGSaveOptions) | `url` で指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されるすべてのリソースは、隣接フォルダーに保存され、その名前は output_file_name + "_files" のように構成されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |
| [write](../../com.aspose.html.dom/document/write/)(params String[]) | open() で開かれたドキュメントストリームにテキストの文字列を書き込みます。なお、この関数は必ずしも DTD によって制御されるドキュメントを生成するわけではなく、ドキュメントのコンテキストで無効な結果になる可能性があります。 |
| [writeLn](../../com.aspose.html.dom/document/writeln/)(params String[]) | open() で開かれたドキュメントストリームにテキストの文字列と改行文字を書き込みます。なお、この関数は必ずしも DTD によって制御されるドキュメントを生成するわけではなく、ドキュメントのコンテキストで無効な結果になる可能性があります。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnAbort](../../com.aspose.html.dom/document/onabort/) | OnAbort イベントのハンドラを取得または設定します。 |
| event [OnBlur](../../com.aspose.html.dom/document/onblur/) | OnBlur イベントのハンドラを取得または設定します。 |
| event [OnCancel](../../com.aspose.html.dom/document/oncancel/) | OnCancel イベントのハンドラを取得または設定します。 |
| event [OnCanplay](../../com.aspose.html.dom/document/oncanplay/) | OnCanplay イベントのハンドラを取得または設定します。 |
| event [OnCanPlayThrough](../../com.aspose.html.dom/document/oncanplaythrough/) | OnCanPlayThrough イベントのハンドラを取得または設定します。 |
| event [OnChange](../../com.aspose.html.dom/document/onchange/) | OnChange イベントのハンドラを取得または設定します。 |
| event [OnClick](../../com.aspose.html.dom/document/onclick/) | OnClick イベントのハンドラを取得または設定します。 |
| event [OnCueChange](../../com.aspose.html.dom/document/oncuechange/) | OnCueChange イベントのハンドラを取得または設定します。 |
| event [OnDblClick](../../com.aspose.html.dom/document/ondblclick/) | OnDblClick イベントのハンドラを取得または設定します。 |
| event [OnDurationChange](../../com.aspose.html.dom/document/ondurationchange/) | OnDurationChange イベントのハンドラを取得または設定します。 |
| event [OnEmptied](../../com.aspose.html.dom/document/onemptied/) | OnEmptied イベントのハンドラを取得または設定します。 |
| event [OnEnded](../../com.aspose.html.dom/document/onended/) | OnEnded イベントのハンドラを取得または設定します。 |
| event [OnError](../../com.aspose.html.dom/document/onerror/) | OnError イベントのハンドラを取得または設定します。 |
| event [OnFocus](../../com.aspose.html.dom/document/onfocus/) | OnFocus イベントのハンドラを取得または設定します。 |
| event [OnInput](../../com.aspose.html.dom/document/oninput/) | OnInput イベントのハンドラを取得または設定します。 |
| event [OnInvalid](../../com.aspose.html.dom/document/oninvalid/) | OnInvalid イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyDown](../../com.aspose.html.dom/document/onkeydown/) | OnKeyDown イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyPress](../../com.aspose.html.dom/document/onkeypress/) | OnKeyPress イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyUp](../../com.aspose.html.dom/document/onkeyup/) | OnKeyUp イベントのイベントハンドラを取得または設定します。 |
| event [OnLoad](../../com.aspose.html.dom/document/onload/) | OnLoad イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadedData](../../com.aspose.html.dom/document/onloadeddata/) | OnLoadedData イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadedMetadata](../../com.aspose.html.dom/document/onloadedmetadata/) | OnLoadedMetadata イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadStart](../../com.aspose.html.dom/document/onloadstart/) | OnLoadStart イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseDown](../../com.aspose.html.dom/document/onmousedown/) | OnMouseDown イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseEnter](../../com.aspose.html.dom/document/onmouseenter/) | OnMouseEnter イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseLeave](../../com.aspose.html.dom/document/onmouseleave/) | OnMouseLeave イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseMove](../../com.aspose.html.dom/document/onmousemove/) | OnMouseMove イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseOut](../../com.aspose.html.dom/document/onmouseout/) | OnMouseOut イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseOver](../../com.aspose.html.dom/document/onmouseover/) | OnMouseOver イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseUp](../../com.aspose.html.dom/document/onmouseup/) | OnMouseUp イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseWheel](../../com.aspose.html.dom/document/onmousewheel/) | OnMouseWheel イベントのイベントハンドラを取得または設定します。 |
| event [OnPause](../../com.aspose.html.dom/document/onpause/) | OnPause イベントのイベントハンドラを取得または設定します。 |
| event [OnPlay](../../com.aspose.html.dom/document/onplay/) | OnPlay イベントのイベントハンドラを取得または設定します。 |
| event [OnPlaying](../../com.aspose.html.dom/document/onplaying/) | OnPlaying イベントのイベントハンドラを取得または設定します。 |
| event [OnProgress](../../com.aspose.html.dom/document/onprogress/) | OnProgress イベントのイベントハンドラを取得または設定します。 |
| event [OnRateChange](../../com.aspose.html.dom/document/onratechange/) | OnRateChange イベントのイベントハンドラを取得または設定します。 |
| event [OnReadyStateChange](../../com.aspose.html.dom/document/onreadystatechange/) | OnReadyStateChange イベントのイベントハンドラを取得または設定します。 |
| event [OnReset](../../com.aspose.html.dom/document/onreset/) | OnReset イベントのイベントハンドラを取得または設定します。 |
| event [OnResize](../../com.aspose.html.dom/document/onresize/) | OnResize イベントのイベントハンドラを取得または設定します。 |
| event [OnScroll](../../com.aspose.html.dom/document/onscroll/) | OnScroll イベントのイベントハンドラを取得または設定します。 |
| event [OnSeeked](../../com.aspose.html.dom/document/onseeked/) | OnSeeked イベントのハンドラを取得または設定します。 |
| event [OnSeeking](../../com.aspose.html.dom/document/onseeking/) | OnSeeking イベントのハンドラを取得または設定します。 |
| event [OnSelect](../../com.aspose.html.dom/document/onselect/) | OnSelect イベントのハンドラを取得または設定します。 |
| event [OnShow](../../com.aspose.html.dom/document/onshow/) | OnShow イベントのハンドラを取得または設定します。 |
| event [OnStalled](../../com.aspose.html.dom/document/onstalled/) | OnStalled イベントのハンドラを取得または設定します。 |
| event [OnSubmit](../../com.aspose.html.dom/document/onsubmit/) | OnSubmit イベントのハンドラを取得または設定します。 |
| event [OnSuspend](../../com.aspose.html.dom/document/onsuspend/) | OnSuspend イベントのハンドラを取得または設定します。 |
| event [OnTimeUpdate](../../com.aspose.html.dom/document/ontimeupdate/) | OnTimeUpdate イベントのハンドラを取得または設定します。 |
| event [OnToggle](../../com.aspose.html.dom/document/ontoggle/) | OnToggle イベントのハンドラを取得または設定します。 |
| event [OnVolumeChange](../../com.aspose.html.dom/document/onvolumechange/) | OnVolumeChange イベントのハンドラを取得または設定します。 |
| event [OnWaiting](../../com.aspose.html.dom/document/onwaiting/) | OnWaiting イベントのハンドラを取得または設定します。 |

### 関連項目

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
