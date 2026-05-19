---
title: "Document クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Document クラス。Document は HTML、XML、または SVG ドキュメント全体を表します。概念的にはドキュメントツリーのルートであり、ドキュメントデータへの主要なアクセス手段を提供します。"
type: docs

url: /ja/java/com.aspose.html.dom/document/
---
## Document class

Document は HTML、XML、または SVG ドキュメント全体を表します。概念的にはドキュメントツリーのルートであり、ドキュメントデータへの主要なアクセス手段を提供します。

```java
public class Document : Node, IDocumentEvent, IDocumentStyle, IDocumentTraversal, 
    IGlobalEventHandlers, INonElementParentNode, IParentNode, IXPathEvaluator
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/document/baseuri/) このノードの絶対ベース URI、取得できなかった場合は null です。 |
| [getCharacterSet](../../com.aspose.html.dom/document/characterset/) ドキュメントのエンコーディングを取得します。 |
| [getCharset](../../com.aspose.html.dom/document/charset/) ドキュメントのエンコーディングを取得します。 |
| [getChildElementCount](../../com.aspose.html.dom/document/childelementcount/) この要素の子要素ノード（nodeType が 1 のもの）の現在の数を返します。子ノードが存在しない場合は 0 です。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/document/children/) 子要素を返します。 |
| [getContentType](../../com.aspose.html.dom/document/contenttype/) ドキュメントのコンテンツタイプを取得します。 |
| [getContext](../../com.aspose.html.dom/document/context/) 現在の閲覧コンテキストを取得します。 |
| [getDefaultView](../../com.aspose.html.dom/document/defaultview/) Document インターフェイスの defaultView IDL 属性は、取得時に、この Document に関連付けられた閲覧コンテキストがある場合はその閲覧コンテキストの WindowProxy オブジェクトを、そうでない場合は null を返さなければなりません。 |
| [getDoctype](../../com.aspose.html.dom/document/doctype/) このドキュメントに関連付けられた文書型宣言です。 |
| [getDocumentElement](../../com.aspose.html.dom/document/documentelement/) これは、ドキュメントの文書要素である子ノードへ直接アクセスできる便利な属性です。 |
| [getDocumentURI](../../com.aspose.html.dom/document/documenturi/) ドキュメントの場所、未定義の場合または DOMImplementation.createDocument を使用して作成された場合は null です。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（[`Node`](../node/) インターフェイス）は、ツリー内のノードの最初の子ノードを返します。子ノードがない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/document/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null です。 |
| [getImplementation](../../com.aspose.html.dom/document/implementation/) このドキュメントを処理する DOMImplementation オブジェクトです。 |
| [getInputEncoding](../../com.aspose.html.dom/document/inputencoding/) ドキュメントのエンコーディングを取得します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（[`Node`](../node/) インターフェイス）は、ノードの最後の子ノードを返します。親が要素である場合、子は通常、要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/document/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../node/element_node/) および [`ATTRIBUTE_NODE`](../node/attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](./createelement/) のような DOM Level 1 メソッドで作成されたノードの場合、常に null です。 |
| [getLocation](../../com.aspose.html.dom/document/location/) ドキュメントの場所です。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextElementSibling](../../com.aspose.html.dom/document/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に来る要素の兄弟ノードがない場合は null です。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/childnodes/) 内で指定されたノードの直後のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/document/nodename/) このノードの名前（タイプに応じて）です。 |
| [getNodeType](../../com.aspose.html.dom/document/nodetype/) 基になるオブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | [`Node `](../node/) インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getOrigin](../../com.aspose.html.dom/document/origin/) ドキュメントのオリジンを取得します。 |
| [getOwnerDocument](../../com.aspose.html.dom/document/ownerdocument/) 所有ドキュメントを取得します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../node/) インターフェイス）は、DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/document/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前に来る要素の兄弟ノードがない場合は null です。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/firstchild/) リスト内で指定されたノードの直前のノードを返します。指定されたノードがリストの最初の場合は null を返します。 |
| [getReadyState](../../com.aspose.html.dom/document/readystate/) ドキュメントの準備状態を返します。Document が読み込み中のときは "loading"、解析が完了しサブリソースをまだ読み込み中のときは "interactive"、完全に読み込まれたときは "complete" です。 |
[getStrictErrorChecking]
[setStrictErrorChecking] An attribute specifying whether error checking is enforced or not. When set to false, the implementation is free to not test every possible error case normally defined on DOM operations, and not raise any DOMException on DOM operations or report errors while using Document.normalizeDocument(). In case of error, the behavior is undefined. This attribute is true by default. |
| [getStyleSheets](../../com.aspose.html.dom/document/stylesheets/) ドキュメントに明示的にリンクされ、または埋め込まれたすべてのスタイルシートのリストです。HTML ドキュメントの場合、外部スタイルシート（HTML LINK 要素で含まれるもの）とインライン STYLE 要素が含まれます。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | [`Node`](../node/) インターフェイスの textContent プロパティは、ノードおよびその子孫のテキスト内容を表します。 |
[getXmlStandalone]
[setXmlStandalone] An attribute specifying, as part of the XML declaration, whether this document is standalone. This is false when unspecified. |
[getXmlVersion]
[setXmlVersion] An attribute specifying, as part of the XML declaration, the version number of this document. If there is no declaration and if this document supports the "XML" feature, the value is "1.0". If this document does not support the "XML" feature, the value is always null. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送られたときに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（別のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [createAttribute](../../com.aspose.html.dom/document/createattribute/)(String) | Document.createAttribute() メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [`Attr`](../attr/) インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [createAttributeNS](../../com.aspose.html.dom/document/createattributens/)(String, String) | Document.createAttribute() メソッドは新しい属性ノードを作成し、返します。作成されたオブジェクトは [Attr](T:com.aspose.html.dom.Attr) インターフェイスを実装するノードです。DOM はこの方法で特定の要素に追加できる属性の種類を強制しません。 |
| [createCDATASection](../../com.aspose.html.dom/document/createcdatasection/)(String) | 指定された文字列を値とする [`CDATASection`](../cdatasection/) ノードを作成します。 |
| [createComment](../../com.aspose.html.dom/document/createcomment/)(String) | 指定された文字列を内容とする [`Comment`](../comment/) ノードを作成します。 |
| [createDocumentFragment](../../com.aspose.html.dom/document/createdocumentfragment/)() | 新しい空の [`DocumentFragment`](../documentfragment/) を作成し、そこに DOM ノードを追加してオフスクリーンの DOM ツリーを構築できます。 |
| [createDocumentType](../../com.aspose.html.dom/document/createdocumenttype/)(String, String, String, String) | このメソッドは [`DocumentType`](../documenttype/) オブジェクトを返します。このオブジェクトはドキュメント作成時に DOMImplementation.createDocument と共に使用できるか、Node.insertBefore() や Node.replaceChild() などのメソッドでドキュメントに挿入できます。 |
| [createElement](../../com.aspose.html.dom/document/createelement/)(String) | HTML ドキュメントでは、document.createElement() メソッドは tagName で指定された HTML 要素を作成します。tagName が認識されない場合は [`HTMLUnknownElement`](../../com.aspose.html/htmlunknownelement/) が作成されます。 |
| [createElementNS](../../com.aspose.html.dom/document/createelementns/)(String, String) | 指定された修飾名とパッケージ URI の要素を作成します。 |
| [createEntityReference](../../com.aspose.html.dom/document/createentityreference/)(String) | EntityReference オブジェクトを作成します。さらに、参照されたエンティティが既知の場合、EntityReference ノードの子リストは対応する Entity ノードと同じになります。 |
| [createEvent](../../com.aspose.html.dom/document/createevent/)(String) | 実装がサポートするタイプの [`Event`](../../com.aspose.html.dom.events/event/) を作成します。 |
| [createExpression](../../com.aspose.html.dom/document/createexpression/)(String, IXPathNSResolver) | 解決されたパッケージを持つ解析済み XPath 式を作成します。式をアプリケーションで再利用する場合に便利で、式文字列をより効率的な内部形式にコンパイルし、式内に出現するすべてのパッケージプレフィックスを事前に解決できます。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator)(Node) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_1)(Node, long) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom/document/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNSResolver](../../com.aspose.html.dom/document/creatensresolver/)(Node) | 任意の DOM ノードを適応させてパッケージを解決し、XPath 式をドキュメント内でそのノードが出現したコンテキストに対して簡単に評価できるようにします。このアダプタは、DOM Level 3 の `lookupNamespaceURI` メソッドと同様に動作し、lookupNamespaceURI が呼び出された時点でノード階層に利用可能な情報を使用して、指定されたプレフィックスから packageURI を解決し、暗黙の xml プレフィックスも正しく解決します。 |
| [createProcessingInstruction](../../com.aspose.html.dom/document/createprocessinginstruction/)(String, String) | 指定された名前とデータ文字列を使用して ProcessingInstruction ノードを作成します。 |
| [createTextNode](../../com.aspose.html.dom/document/createtextnode/)(String) | 指定された文字列を使用して Text ノードを作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker)(Node) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_1)(Node, long) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom/document/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [evaluate](../../com.aspose.html.dom/document/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | XPath 式文字列を評価し、可能であれば指定された型の結果を返します。 |
| [getElementById](../../com.aspose.html.dom/document/getelementbyid/)(String) | Document のメソッド getElementById() は、指定された文字列と id プロパティが一致する要素を表す [`Element`](../element/) オブジェクトを返します。要素の ID は指定された場合一意である必要があるため、特定の要素に迅速にアクセスする便利な手段となります。 |
| [getElementsByClassName](../../com.aspose.html.dom/document/getelementsbyclassname/)(String) | `Document` インターフェイスの getElementsByClassName メソッドは、指定されたクラス名すべてを持つすべての子要素を配列のようなオブジェクトとして返します。 |
| [getElementsByTagName](../../com.aspose.html.dom/document/getelementsbytagname/)(String) | `Document` インターフェイスの getElementsByTagName メソッドは、指定されたタグ名を持つ要素の [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) を返します。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/document/getelementsbytagnamens/)(String, String) | 指定されたパッケージに属する、指定されたタグ名を持つ要素のリストを返します。ルートノードを含むドキュメント全体が検索されます。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [importNode](../../com.aspose.html.dom/document/importnode/)(Node, bool) | 別のドキュメントからノードをこのドキュメントにインポートします。元のドキュメントのソースノードは変更または削除されず、このメソッドはソースノードの新しいコピーを作成します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプであり、定義上の特性（要素の場合は ID、子ノード数など）が一致し、属性も一致することを指します。必要なデータ項目の具体的なセットは、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate)(RequestMessage) | 指定されたリクエストオブジェクトに基づいてドキュメントをロードし、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_4)(String) | 指定された Uniform Resource Locator（URL）からドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_1)(Url) | 指定された Uniform Resource Locator（URL）からドキュメントを現在のインスタンスに読み込み、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_3)(Stream, String) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_2)(Stream, Url) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。ドキュメントの読み込みはストリームの現在位置から開始されます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_6)(String, String) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [navigate](../../com.aspose.html.dom/document/navigate/#navigate_5)(String, Url) | 指定されたコンテンツからドキュメントを読み込み、baseUri を使用して相対リソースを解決し、以前の内容を置き換えます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する「"normal"」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/document/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の要素を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/document/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての要素の NodeList を返します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [renderTo](../../com.aspose.html.dom/document/renderto/)(IDevice) | このメソッドは、現在のドキュメントの内容を指定されたグラフィックデバイスにレンダリングするために使用されます。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../documentfragment/) のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まず削除されます。 |
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

* class [Node](../node/)
* interface [IDocumentEvent](../../com.aspose.html.dom.events/idocumentevent/)
* interface [IDocumentStyle](../../com.aspose.html.dom.css/idocumentstyle/)
* interface [IDocumentTraversal](../../com.aspose.html.dom.traversal/idocumenttraversal/)
* interface [IGlobalEventHandlers](../iglobaleventhandlers/)
* interface [INonElementParentNode](../inonelementparentnode/)
* interface [IParentNode](../iparentnode/)
* interface [IXPathEvaluator](../../com.aspose.html.dom.xpath/ixpathevaluator/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
