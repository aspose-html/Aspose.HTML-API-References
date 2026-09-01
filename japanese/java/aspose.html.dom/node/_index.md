---
title: "Node クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Node クラス。Node インターフェイスは、ドキュメントオブジェクトモデル全体の主要なデータ型です。ドキュメントツリー内の単一ノードを表します。Node インターフェイスを実装するすべてのオブジェクトが子ノード操作用のメソッドを公開していますが、すべてのオブジェクトが子ノードを持つわけではありません。たとえば Text ノードは子ノードを持たず、そのようなノードに子ノードを追加しようとすると DOMException が発生します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/
---
## Node class

The Node インターフェイスは、Document Object Model 全体の主要なデータ型です。これは文書ツリー内の単一ノードを表します。Node インターフェイスを実装するすべてのオブジェクトは子ノードを扱うメソッドを公開していますが、すべてのオブジェクトが子ノードを持つわけではありません。たとえば、[`Text`](../text/) ノードは子ノードを持たない場合があり、そのようなノードに子ノードを追加すると [`DOMException`](../domexception/) が発生します。

属性 [`nodeName`](./nodename/)、[`nodeValue`](./nodevalue/) および属性は、特定の派生インターフェイスにキャストせずにノード情報にアクセスする手段として含まれています。特定の [`nodeType`](./nodetype/) に対してこれらの属性の明確なマッピングが存在しない場合（例：[`Element`](../element/) の nodeValue や [`Comment`](../comment/) の属性）、null が返されます。なお、専門化されたインターフェイスは、関連情報の取得および設定のための、さらに追加された便利な手段を含む場合があります。

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) `Node` インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子ノードを返します。子ノードがない場合は null を返します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) `Node` インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子ノードを返します。親が要素である場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素が存在しない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](./element_node/) および [`ATTRIBUTE_NODE`](./attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](../document/createelement/) のような DOM Level 1 メソッドで作成されたノードに対しては、常に null が返されます。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) `Node` インターフェイスの読み取り専用 nextSibling プロパティは、指定されたノードの親の [`childNodes`](./childnodes/) 内で直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) Node の読み取り専用 nodeName プロパティは、現在のノードの名前を文字列として返します。 |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) 基底オブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `Node` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node インターフェイスの読み取り専用 ownerDocument プロパティは、そのノードの最上位ドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) `Node` インターフェイスの読み取り専用 parentElement プロパティは、DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM 要素でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) `Node` インターフェイスの読み取り専用 previousSibling プロパティは、指定されたノードの親の [`childNodes`](./firstchild/) リスト内で直前にあるノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `Node` インターフェイスの textContent プロパティは、ノードおよびその子孫のテキスト内容を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/)インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された `Node` が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。そのパッケージが対象ノードのデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプであり、定義上の特性（要素の場合は ID や子ノード数など）が一致し、属性も一致することを意味します。必要とされるデータポイントの具体的な集合は、ノードのタイプによって異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node インターフェイスの isSameNode() メソッドは、=== 厳密等価演算子のレガシーエイリアスです。つまり、2 つのノードが同一か（同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node インターフェイスの lookupNamespaceURI() メソッドは、プレフィックスをパラメータとして受け取り、対象ノード上でそれに関連付けられたパッケージ URI を見つけた場合に返し（見つからなければ null を返します）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node インターフェイスの lookupPrefix() メソッドは、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し（存在しなければ null）、複数のプレフィックスが可能な場合は最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する"normal"形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](./ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで child ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、最初に削除されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | `[`Element`](../element/) の [`Attribute`](../attr/)です。 |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | `[`CDATASection`](../cdatasection/)、例: &lt;!CDATA[[ … ]]&gt;。 |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | `[`Comment`](../comment/) ノード、例: &lt;!-- … --&gt;。 |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | `[`DocumentFragment`](../documentfragment/) ノードです。 |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | `[`Document`](../document/) ノードです。 |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | `[`DocumentType`](../documenttype/) ノード、例: &lt;!DOCTYPE html&gt;。 |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | `[`Element`](../element/) ノード、例: &lt;p&gt; や &lt;div&gt;。 |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | `[`Entity`](../entity/) ノードです。 |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | `[`EntityReference`](../entityreference/) ノードです。 |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | `[`Notation`](../notation/) ノードです。 |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | XML ドキュメントの [`ProcessingInstruction`](../processinginstruction/)、たとえば &lt;?xml-stylesheet … ?&gt;。 |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | 実際の [`Text`](../text/) は、[`Element`](../element/) または [`Attr`](../attr/) の内部です。 |

## 備考

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
