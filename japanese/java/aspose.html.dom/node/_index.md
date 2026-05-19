---
title: "Node クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Node クラス。Node インターフェイスは、ドキュメントオブジェクトモデル全体の主要なデータ型です。ドキュメントツリー内の単一ノードを表します。Node インターフェイスを実装するすべてのオブジェクトが子ノード操作用のメソッドを公開していますが、すべてのオブジェクトが子ノードを持つわけではありません。たとえば Text ノードは子ノードを持たず、そのようなノードに子ノードを追加しようとすると DOMException が発生します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/
---
## Node class

Node インターフェイスは、ドキュメントオブジェクトモデル全体の主要なデータ型です。ドキュメントツリー内の単一ノードを表します。Node インターフェイスを実装するすべてのオブジェクトは子ノードを扱うメソッドを公開しますが、すべてのオブジェクトが子ノードを持つわけではありません。たとえば、[`Text`](../text/) ノードは子を持たない場合があり、そのようなノードに子を追加しようとすると [`DOMException`](../domexception/) が発生します。

属性 [`nodeName`](./nodename/)、[`nodeValue`](./nodevalue/) と属性は、特定の派生インターフェイスにキャストせずにノード情報にアクセスするメカニズムとして含まれています。特定の [`nodeType`](./nodetype/) に対して明確なマッピングがない場合（例: [`Element`](../element/) の nodeValue、または [`Comment`](../comment/) の属性）、このプロパティは null を返します。特化されたインターフェイスは、関連情報の取得・設定のために、さらに便利なメカニズムを提供することがあります。

```java
public abstract class Node : EventTarget, IXPathNSResolver
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（`Node` インターフェイス）は、ツリー内のノードの最初の子ノードを返します。子が存在しない場合は null を返します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（`Node` インターフェイス）は、ノードの最後の子ノードを返します。親が要素である場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](./element_node/) や [`ATTRIBUTE_NODE`](./attribute_node/) 以外のタイプ、または DOM Level 1 のメソッド（例: [`Document.createElement()`](../document/createelement/)）で作成されたノードの場合、常に null が返されます。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（`Node` インターフェイス）は、親の [`childNodes`](./childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| abstract [getNodeName](../../com.aspose.html.dom/node/nodename/) 読み取り専用の nodeName プロパティ（Node）は、現在のノードの名前を文字列として返します。 |
| abstract [getNodeType](../../com.aspose.html.dom/node/nodetype/) 基底オブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `Node` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 読み取り専用の ownerDocument プロパティ（Node インターフェイス）は、ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（`Node` インターフェイス）は、DOM ノードの親 [`Element`](../element/) を返します。親が存在しない、または親が DOM 要素でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（`Node` インターフェイス）は、親の [`childNodes`](./firstchild/) リスト内で指定されたノードの直前にあるノードを返します。指定されたノードがリストの最初のノードの場合は null を返します。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `Node` インターフェイスの textContent プロパティは、ノードおよびその子孫のテキスト内容を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送られたときに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（別のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/#clonenode_1)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された `Node` が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードは同じタイプであり、特徴（要素の場合は ID、子の数など）が一致し、属性も一致している場合に等しいとみなされます。必要とされるデータポイントはノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位ツリー全体の深さにあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例: [`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する「正規」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証し、特定のドキュメントツリー構造に依存する操作（例: XPointer [XPointer] ルックアップ）で使用する際に有用です。[`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトの "normalize-characters" パラメータが true の場合、`Node.ownerDocument` に付随するこのメソッドは Text ノードの文字も完全に正規化します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../documentfragment/) のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まず削除されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [ATTRIBUTE_NODE](../../com.aspose.html.dom/node/attribute_node/) | `[`Attribute`](../attr/)` は `[`Element`](../element/)` の属性です。 |
| const [CDATA_SECTION_NODE](../../com.aspose.html.dom/node/cdata_section_node/) | `[`CDATASection`](../cdatasection/)`、例として &lt;!CDATA[[ … ]]&gt;。 |
| const [COMMENT_NODE](../../com.aspose.html.dom/node/comment_node/) | `[`Comment`](../comment/)` ノード、例として &lt;!-- … --&gt;。 |
| const [DOCUMENT_FRAGMENT_NODE](../../com.aspose.html.dom/node/document_fragment_node/) | `[`DocumentFragment`](../documentfragment/)` ノードです。 |
| const [DOCUMENT_NODE](../../com.aspose.html.dom/node/document_node/) | `[`Document`](../document/)` ノードです。 |
| const [DOCUMENT_TYPE_NODE](../../com.aspose.html.dom/node/document_type_node/) | `[`DocumentType`](../documenttype/)` ノード、例として &lt;!DOCTYPE html&gt;。 |
| const [ELEMENT_NODE](../../com.aspose.html.dom/node/element_node/) | `[`Element`](../element/)` ノード、例として &lt;p&gt; や &lt;div&gt;。 |
| const [ENTITY_NODE](../../com.aspose.html.dom/node/entity_node/) | `[`Entity`](../entity/)` ノードです。 |
| const [ENTITY_REFERENCE_NODE](../../com.aspose.html.dom/node/entity_reference_node/) | `[`EntityReference`](../entityreference/)` ノードです。 |
| const [NOTATION_NODE](../../com.aspose.html.dom/node/notation_node/) | `[`Notation`](../notation/)` ノードです。 |
| const [PROCESSING_INSTRUCTION_NODE](../../com.aspose.html.dom/node/processing_instruction_node/) | XML ドキュメントの [`ProcessingInstruction`](../processinginstruction/)、例として &lt;?xml-stylesheet … ?&gt;。 |
| const [TEXT_NODE](../../com.aspose.html.dom/node/text_node/) | 実際の [`Text`](../text/) は [`Element`](../element/) または [`Attr`](../attr/) の内部にあります。 |

## Remarks

参照:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # interface-node](https://dom.spec.whatwg.org/#interface-node).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### 関連項目

* class [EventTarget](../eventtarget/)
* interface [IXPathNSResolver](../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
