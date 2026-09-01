---
title: "Entity クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Entity クラス。XML ドキュメント内の既知のエンティティ（解析済みまたは未解析）を表します。"
type: docs

url: /ja/java/com.aspose.html.dom/entity/
---
## Entity class

XML ドキュメント内の、解析済みまたは未解析の既知のエンティティを表します。

```java
public class Entity : Node
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（[`Node`](../node/) インターフェイス）は、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getInputEncoding](../../com.aspose.html.dom/entity/inputencoding/) 解析時にこのエンティティに使用されたエンコーディングを指定する属性です（外部解析エンティティの場合）。内部サブセットからのエンティティ、または不明な場合は null です。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（[`Node`](../node/) インターフェイス）は、ノードの最後の子を返します。親が要素の場合、子は通常、要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../node/element_node/) と [`ATTRIBUTE_NODE`](../node/attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](../document/createelement/) のような DOM Level 1 メソッドで作成されたノードの場合、常に null です。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../node/) インターフェイス）は、指定されたノードの親の [`childNodes`](../node/childnodes/) 内で直後のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/entity/nodename/) このノードの名前です。タイプに応じて異なります。 |
| [getNodeType](../../com.aspose.html.dom/entity/nodetype/) 基底オブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../node/)` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
| [getNotationName](../../com.aspose.html.dom/entity/notationname/) 未解析エンティティの場合、エンティティの表記名です。解析済みエンティティの場合は null です。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node インターフェイスの読み取り専用 ownerDocument プロパティは、そのノードの最上位ドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../node/) インターフェイス）は、DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../node/) インターフェイス）は、指定されたノードの親の [`childNodes`](../node/firstchild/) リストで直前のノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [getPublicId](../../com.aspose.html.dom/entity/publicid/) エンティティに関連付けられた公開識別子（指定されていれば）。指定されていない場合は null です。 |
| [getSystemId](../../com.aspose.html.dom/entity/systemid/) エンティティに関連付けられたシステム識別子（指定されていれば）。指定されていない場合は null です。絶対 URI の場合もありますし、そうでない場合もあります。 |
| [textContent](../../com.aspose.html.dom/node/textcontent/) { get; set; } | `[`Node`](../node/)` インターフェイスの textContent プロパティは、ノードおよびその子孫のテキスト内容を表します。 |
| [getXmlEncoding](../../com.aspose.html.dom/entity/xmlencoding/) テキスト宣言の一部として、このエンティティ（外部解析エンティティ）のエンコーディングを指定する属性です。その他の場合は null です。 |
| [getXmlVersion](../../com.aspose.html.dom/entity/xmlversion/) テキスト宣言の一部として、このエンティティ（外部解析エンティティ）のバージョン番号を指定する属性です。その他の場合は null です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/)インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。そのパッケージが対象ノードのデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプであり、定義上の特性（要素の場合は ID、子の数など）が一致し、属性も一致することなどを指します。必要となるデータ項目の具体的な集合は、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node インターフェイスの isSameNode() メソッドは、=== 厳密等価演算子のレガシーエイリアスです。つまり、2 つのノードが同一か（同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node インターフェイスの lookupNamespaceURI() メソッドは、プレフィックスをパラメータとして受け取り、対象ノード上でそれに関連付けられたパッケージ URI を見つけた場合に返し（見つからなければ null を返します）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node インターフェイスの lookupPrefix() メソッドは、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し（存在しなければ null）、複数のプレフィックスが可能な場合は最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体にあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../element/)、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する「正規」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで child ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、最初に削除されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [Node](../node/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
