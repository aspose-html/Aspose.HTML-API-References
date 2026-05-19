---
title: "DocumentType クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.DocumentType クラス。DocumentType は、ドキュメントに定義されたエンティティのリストへのインターフェイスを提供します。"
type: docs

url: /ja/java/com.aspose.html.dom/documenttype/
---
## DocumentType class

DocumentType は、ドキュメントに定義されたエンティティのリストへのインターフェイスを提供します。

```java
public class DocumentType : Node
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocumentType](documenttype/)(String, String, String, String, Document) | 新しい `DocumentType` クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（[`Node`](../node/) インターフェイス）は、ツリー内のノードの最初の子ノードを返します。子ノードがない場合は null を返します。 |
| [getInternalSubset](../../com.aspose.html.dom/documenttype/internalsubset/) 内部サブセットを文字列として返します。存在しない場合は null です。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（[`Node`](../node/) インターフェイス）は、ノードの最後の子ノードを返します。親が要素である場合、子は通常、要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../node/element_node/) および [`ATTRIBUTE_NODE`](../node/attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](../document/createelement/) のような DOM Level 1 メソッドで作成されたノードの場合、常に null です。 |
| [getName](../../com.aspose.html.dom/documenttype/name/) DTD の名前です。つまり、DOCTYPE キーワードの直後に続く名前です。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/childnodes/) 内で指定されたノードの直後のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/documenttype/nodename/) このノードの名前は、タイプに応じて決まります。 |
| [getNodeType](../../com.aspose.html.dom/documenttype/nodetype/) 基になるオブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | [`Node `](../node/) インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 読み取り専用の ownerDocument プロパティ（Node インターフェイス）は、ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../node/) インターフェイス）は、DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/firstchild/) リスト内で指定されたノードの直前のノードを返します。指定されたノードがリストの最初の場合は null を返します。 |
| [getPublicId](../../com.aspose.html.dom/documenttype/publicid/) 外部サブセットの公開識別子です。 |
| [getSystemId](../../com.aspose.html.dom/documenttype/systemid/) 外部サブセットのシステム識別子です。絶対 URI の場合もありますし、そうでない場合もあります。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | [`Node`](../node/) インターフェイスの textContent プロパティは、ノードおよびその子孫のテキスト内容を表します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送られたときに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（別のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプであり、定義上の特性（要素の場合は ID、子ノード数など）が一致し、属性も一致することを指します。必要なデータ項目の具体的なセットは、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する「"normal"」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../documentfragment/) のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まず削除されます。 |
| [toString](../../com.aspose.html.dom/documenttype/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
