---
title: "HTMLDocument クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.HTMLDocument クラス。HTML ドキュメントを表します。すべてのトップレベル HTML オブジェクトはこのオブジェクトに追加されます。このクラスは、ブラウザで表示される HTML ページを表現します。すべてのフォーム、テーブル、スクリプトなどは、このクラスのインターフェイスを通じて HTML ページに追加されます。HTMLDocument は、最も一般的な Document インターフェイスの HTML 実装であり、両者は DOM（Document Object Model）のコアまたはルートポイントです。これらの概念は公式のウェブ開発の基礎や標準に完全に合致しています。ウェブ開発の目的では、HTMLDocument は基盤となる Document のエイリアスと考えて構いません。"
type: docs

url: /ja/java/com.aspose.html/htmldocument/
---
## HTMLDocument class

HTML ドキュメントを表します。すべてのトップレベル HTML オブジェクトはこのオブジェクトに追加されます。このクラスは、ブラウザで表示される HTML ページを表します。すべてのフォーム、テーブル、スクリプトなどは、このクラスのインターフェイスを通じて HTML ページに追加されます。[HTMLDocument](https://dom.spec.whatwg.org/#ref-for-dom-domimplementation-createhtmldocument) は、最も汎用的な [Document](https://dom.spec.whatwg.org/#document) インターフェイスの HTML 実装であり、両者は [DOM](https://dom.spec.whatwg.org/)（Document Object Model）のコアまたはルートポイントです。これらの概念は公式のウェブ開発の基礎や標準に完全に合致しています。ウェブ開発の目的では、HTMLDocument は Document のエイリアスと考えて構いません。

```java
public class HTMLDocument : Document, IDocumentCSS
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [HTMLDocument](htmldocument/#constructor)() | HTMLDocument コンストラクタは、ブラウザで読み込まれたウェブページであり、ページのコンテンツへのエントリーポイントとなる新しい HTML Document オブジェクトを作成します。 |
| [HTMLDocument](htmldocument/#constructor_1)(Configuration) | HTMLDocument コンストラクタは、ブラウザで読み込まれたウェブページであり、ページのコンテンツへのエントリーポイントとなる新しい HTML Document オブジェクトを作成します。 |
| [HTMLDocument](htmldocument/#constructor_2)(RequestMessage) | [`RequestMessage`](../../com.aspose.html.net/requestmessage/) オブジェクトから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_10)(String) | アドレスから HTML ドキュメントを読み込みます。 |
| [HTMLDocument](htmldocument/#constructor_4)(Url) | URL から HTML ドキュメントを読み込みます。 |
| [HTMLDocument](htmldocument/#constructor_3)(RequestMessage, Configuration) | [RequestMessage](T:com.aspose.html.net.RequestMessage) オブジェクトから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_8)(Stream, String) | 指定された base-uri を使用して相対リソースのパスを解決するための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_6)(Stream, Url) | 指定された base-uri を使用して相対リソースのパスを解決するための [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_11)(String, Configuration) | 指定された環境構成設定を使用してアドレスから HTML ドキュメントを読み込みます。 |
| [HTMLDocument](htmldocument/#constructor_14)(String, String) | 指定された base-uri を使用して文字列コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_12)(String, Url) | 指定された base-uri を使用して文字列コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_5)(Url, Configuration) | 指定された環境構成設定を使用して URL から HTML ドキュメントを読み込みます。 |
| [HTMLDocument](htmldocument/#constructor_9)(Stream, String, Configuration) | 指定された base-uri と環境構成設定を使用して [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_7)(Stream, Url, Configuration) | 指定された base-uri と環境構成設定を使用して [Stream](https://docs.microsoft.com/en-us/dotnet/api/system.io.stream) コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_15)(String, String, Configuration) | 指定された base-uri と環境構成設定を使用して文字列コンテンツから HTML ドキュメントを作成します。 |
| [HTMLDocument](htmldocument/#constructor_13)(String, Url, Configuration) | 指定された base-uri と環境構成設定を使用して文字列コンテンツから HTML ドキュメントを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAnchors](../../com.aspose.html/htmldocument/anchors/) ドキュメント内の `name` 属性を持つすべてのアンカー（`A`）要素のコレクション。下位互換性のため、返されるアンカー集合には `name` 属性で作成されたアンカーのみが含まれ、`id` 属性で作成されたものは含まれません。[[XHTML 1.0](http://www.w3.org/TR/2002/REC-xhtml1-20020801)] では、`name` 属性（セクション 4.10 参照）は意味を持たず、レガシーユーザーエージェントのためだけに存在し、代わりに `id` 属性が使用されます。ユーザーは代わりに [[DOM Level 2 Traversal](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)] が提供するイテレータ機構を使用すべきです。 |
| [getApplets](../../com.aspose.html/htmldocument/applets/) ドキュメント内のアプレットと `APPLET`（非推奨）要素を含むすべての `OBJECT` 要素のコレクション。 |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) このノードの絶対ベース URI、取得できなかった場合は null。 |
[getBody]
[setBody] The element that contains the content for the document. In documents with `BODY` contents, returns the `BODY`element. In frameset documents, this returns the outermost `FRAMESET` element. |
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
| [getDomain](../../com.aspose.html/htmldocument/domain/) ドキュメントを提供したサーバーのドメイン名、またはサーバーがドメイン名で特定できない場合は `null`。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null。 |
| [getForms](../../com.aspose.html/htmldocument/forms/) ドキュメント内のすべてのフォームのコレクション。 |
| [getImages](../../com.aspose.html/htmldocument/images/) ドキュメント内のすべての `IMG` 要素のコレクション。下位互換性のため、動作は `IMG` 要素に限定されています。[[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] の推奨どおり、画像を含めるには作者は `OBJECT` 要素または `IMG` 要素を使用できます。したがって、この属性を使用してドキュメント内の画像を検索するのではなく、HTML 4.01 の `getElementsByTagName` または XHTML 1.0 の `getElementsByTagNameNS` を使用することが推奨されます。 |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) このドキュメントを処理する DOMImplementation オブジェクト。 |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) ドキュメントのエンコーディングを取得します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null。 |
| [getLinks](../../com.aspose.html/htmldocument/links/) `href` 属性を持つドキュメント内のすべての `AREA` 要素とアンカー（`A`）要素のコレクション。 |
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
| [getReferrer](../../com.aspose.html/htmldocument/referrer/) このページへリンクしたページの URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt)] を返します。ユーザーが直接（リンク経由ではなく、たとえばブックマーク経由で）ページに移動した場合、値は空の文字列になります。 |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) ドキュメントに明示的にリンクまたは埋め込まれたすべてのスタイルシートを含むリストです。HTML ドキュメントの場合、外部スタイルシート（HTML LINK 要素で含まれる）とインライン STYLE 要素が含まれます。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | [`Node`](../../com.aspose.html.dom/node/) インターフェイスの textContent プロパティは、ノードとその子孫のテキストコンテンツを表します。 |
[getTitle]
[setTitle] The title of a document as specified by the `TITLE` element in the head of the document. |
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
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | HTML ドキュメントでは、document.createElement() メソッドは tagName で指定された HTML 要素を作成し、tagName が認識されない場合は [`HTMLUnknownElement`](../htmlunknownelement/) を作成します。 |
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
| [getOverrideStyle](../../com.aspose.html/htmldocument/getoverridestyle/)(Element, String) | このメソッドは、指定された要素および指定された疑似要素のオーバーライドスタイル宣言を取得するために使用されます。 |
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
| [normalize](../../com.aspose.html.dom/node/normalize/)() | このノードの下位サブツリー全体の深さにあるすべての[`Text`](../../com.aspose.html.dom/text/)ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが[`Text`](../../com.aspose.html.dom/text/)ノードと分離された「標準」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された[`DOMConfiguration`](../configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の Element を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての Element の NodeList を返します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [renderTo](../../com.aspose.html/htmldocument/renderto/)(IDevice) | このメソッドは、現在のドキュメントの内容を指定されたデバイスに印刷するために使用されます。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合、最初に削除されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save)(ResourceHandler) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html/htmldocument/save/#save_10)(String) | パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_5)(Url) | ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_1)(ResourceHandler, HTMLSaveFormat) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html/htmldocument/save/#save_2)(ResourceHandler, HTMLSaveOptions) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html/htmldocument/save/#save_3)(ResourceHandler, MarkdownSaveOptions) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html/htmldocument/save/#save_4)(ResourceHandler, MHTMLSaveOptions) | [`ResourceHandler`](../../com.aspose.html.saving.resourcehandlers/resourcehandler/) を使用してドキュメントの内容とリソースを保存します。 |
| [save](../../com.aspose.html/htmldocument/save/#save_11)(String, HTMLSaveFormat) | ドキュメントを path で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_12)(String, HTMLSaveOptions) | パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_13)(String, MarkdownSaveOptions) | パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_14)(String, MHTMLSaveOptions) | パスで指定されたローカルファイルにドキュメントを保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" の形式で作成されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_6)(Url, HTMLSaveFormat) | ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は output_file_name + "_files" として構築されます。 |
| [save](../../com.aspose.html/htmldocument/save/#save_7)(Url, HTMLSaveOptions) | ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。 |
| [save](../../com.aspose.html/htmldocument/save/#save_8)(Url, MarkdownSaveOptions) | ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。 |
| [save](../../com.aspose.html/htmldocument/save/#save_9)(Url, MHTMLSaveOptions) | ドキュメントを url で指定されたローカルファイルに保存します。このドキュメントで使用されたすべてのリソースは、隣接するフォルダーに保存され、その名前は次のように構築されます: output_file_name + "_files"。 |
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

## 備考

HTMLDocument、Document、DOM に関する詳細情報は、一般的なウェブ開発リソースで入手できます:

[General Document interface](https://developer.mozilla.org/en-US/docs/Web/API/Document).[Html specific HTMLDocument interface](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDocument).[What is the HTML DOM](https://www.w3schools.com/js/js_htmldom.asp).

標準リファレンス:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # htmldocument](https://html.spec.whatwg.org/multipage/window-object.html#htmldocument).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

## サンプル

```java
    // HTML ドキュメントのインスタンスを作成します
	using (var document = new HTMLDocument())
      {
        // style 要素を作成し、クラス名が 'gr' のすべての要素に緑色を割り当てます。
        var style = document.CreateElement("style");
        style.TextContent = ".gr { color: green }";

        // ドキュメントのヘッダー要素を見つけ、style 要素をヘッダーに追加します
        var head = document.GetElementsByTagName("head").First();
        head.AppendChild(style);

        // クラス名 'gr' の段落要素を作成します。
        var p = (HTMLParagraphElement)document.CreateElement("p");
        p.ClassName = "gr";

        // テキストノードを作成します
        var text = document.CreateTextNode("Hello World!!");

        // テキストノードを段落に追加します
        p.AppendChild(text);

        // 段落をドキュメントの body 要素に追加します
        document.Body.AppendChild(p);

        // HTML ドキュメントをファイルに保存します 
        document.Save(Path.Combine(OutputDir, "using-dom.html"));

        // PDF 出力デバイスのインスタンスを作成し、ドキュメントをそのデバイスにレンダリングします
        using (var device = new PdfDevice(Path.Combine(OutputDir, "using-dom.pdf")))
        {
          // HTML を PDF にレンダリングします
          document.RenderTo(device);
        }
      }       
```

### 関連項目

* class [Document](../../com.aspose.html.dom/document/)
* interface [IDocumentCSS](../../com.aspose.html.dom.css/idocumentcss/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
