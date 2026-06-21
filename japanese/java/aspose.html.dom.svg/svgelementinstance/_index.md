---
title: "SVGElementInstance クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.SVGElementInstance クラス。各 use-element シャドウツリーのルートオブジェクトは SVGUseElementShadowRoot インターフェイスを実装します。このインターフェイスは現在、ShadowRoot インターフェイスおよび DocumentOrShadowRoot ミックスインで定義されたプロパティやメソッドへの拡張を定義していません。ただし、このノードをルートとするツリーは、作者スクリプトの観点からは完全に読み取り専用です。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

各 use 要素のシャドウツリーのルートオブジェクトは SVGUseElementShadowRoot インターフェイスを実装します。このインターフェイスは現在、ShadowRoot インターフェイスおよび DocumentOrShadowRoot ミックスインで定義されたプロパティやメソッドへの拡張を定義していません。ただし、このノードを根とするツリーは、作者スクリプトから見ると完全に読み取り専用です。

```java
public class SVGElementInstance : ShadowRoot
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) 現在の要素の子要素を返します。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null を返します。 |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host はこの ShadowRoot を含む要素です。 |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) と [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) 以外のタイプのノードや、[`Document.createElement()`](../../com.aspose.html.dom/document/createelement/) のような DOM Level 1 メソッドで作成されたノードについては、常に null です。 |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) この ShadowRoot が動作するモードです。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く兄弟要素ノードがない場合は null を返します。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 nextSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) このノードの名前（タイプに応じたもの）です。 |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) 基になるオブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../../com.aspose.html.dom/node/)` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node インターフェイスの読み取り専用 ownerDocument プロパティは、そのノードの最上位ドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 parentElement プロパティは、DOM ノードの親 [`Element`](../../com.aspose.html.dom/element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある兄弟要素ノードがない場合は null を返します。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 previousSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/firstchild/) リストで指定されたノードの直前にあるノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子ノードが削除され、かつ新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配送されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() メソッドは、Node インターフェイスのもので、指定された [`Node`](../../com.aspose.html.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。そのパッケージが対象ノードのデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが同じ型で、定義上の特性（要素の場合は ID、子の数など）が同じで、属性が一致するなどの場合に等しいとみなされます。必要なデータポイントの具体的な集合は、ノードの種類によって異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node インターフェイスの isSameNode() メソッドは、=== 厳密等価演算子のレガシーエイリアスです。つまり、2 つのノードが同一か（同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node インターフェイスの lookupNamespaceURI() メソッドは、プレフィックスをパラメータとして受け取り、対象ノード上でそれに関連付けられたパッケージ URI を見つけた場合に返し（見つからなければ null を返します）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node インターフェイスの lookupPrefix() メソッドは、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し（存在しなければ null）、複数のプレフィックスが可能な場合は最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../../com.aspose.html.dom/text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが [`Text`](../../com.aspose.html.dom/text/) ノードを分離する「正規」形に変換します。つまり、隣接した Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の Element を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての Element の NodeList を返します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合、最初に削除されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
