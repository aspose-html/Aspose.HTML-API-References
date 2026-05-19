---
title: "SVGElementInstance クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.SVGElementInstance クラス。各 use-element シャドウツリーのルートオブジェクトは SVGUseElementShadowRoot インターフェイスを実装します。このインターフェイスは現在、ShadowRoot インターフェイスおよび DocumentOrShadowRoot ミックスインで定義されたプロパティやメソッドへの拡張を定義していません。ただし、このノードをルートとするツリーは、作者スクリプトの観点からは完全に読み取り専用です。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgelementinstance/
---
## SVGElementInstance class

各 use 要素のシャドウツリーのルートオブジェクトは SVGUseElementShadowRoot インターフェイスを実装します。このインターフェイスは現在、ShadowRoot インターフェイスと DocumentOrShadowRoot ミックスインで定義されたプロパティやメソッドへの拡張を定義していません。ただし、このノードを根とするツリーは、作者スクリプトから見ると完全に読み取り専用です。

```java
public class SVGElementInstance : ShadowRoot
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildElementCount](../../com.aspose.html.dom/documentfragment/childelementcount/) 現在この要素の子である要素ノードの数を返します。nodeType 1 の子ノードがない場合は 0 です。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/documentfragment/children/) 現在の要素の子要素を返します。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/documentfragment/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null です。 |
| [getHost](../../com.aspose.html.dom/shadowroot/host/) Host はこの ShadowRoot を含む要素です。 |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/documentfragment/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
| [getLocalName](../../com.aspose.html.dom/node/localname/) このノードの修飾名のローカル部分を返します。[`ELEMENT_NODE`](../../com.aspose.html.dom/node/element_node/) および [`ATTRIBUTE_NODE`](../../com.aspose.html.dom/node/attribute_node/) 以外のタイプのノード、または DOM Level 1 のメソッド（例: [`Document.createElement()`](../../com.aspose.html.dom/document/createelement/)）で作成されたノードの場合、常に null です。 |
| [getMode](../../com.aspose.html.dom/shadowroot/mode/) この ShadowRoot が動作するモードです。 |
| [getNamespaceURI](../../com.aspose.html.dom/node/packageuri/) Element.packageURI 読み取り専用プロパティは要素のパッケージ URI を返し、要素がパッケージに属さない場合は null を返します。 |
| [getNextElementSibling](../../com.aspose.html.dom/documentfragment/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く兄弟要素ノードがない場合は null です。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、親の [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/documentfragment/nodename/) このノードの名前（タイプに応じたもの）です。 |
| [getNodeType](../../com.aspose.html.dom/documentfragment/nodetype/) 基になるオブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue プロパティ（[`Node `](../../com.aspose.html.dom/node/) インターフェイス）は、現在のノードの値を取得または設定します。 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 読み取り専用の ownerDocument プロパティ（Node インターフェイス）は、ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、DOM ノードの親 [`Element`](../../com.aspose.html.dom/element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [prefix](../../com.aspose.html.dom/node/prefix/) { get; set; } | prefix 読み取り専用プロパティは、指定された要素のパッケージプレフィックスを返し、プレフィックスが指定されていない場合は null を返します。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/documentfragment/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある兄弟要素ノードがない場合は null です。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、親の [`childNodes`](../../com.aspose.html.dom/node/firstchild/) リストで指定されたノードの直前にあるノードを返します。そのリストで指定ノードが最初の場合は null を返します。 |
| [textContent](../../com.aspose.html.dom/documentfragment/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子が削除され、新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（別のノードに追加する前に親ノードから削除する必要はありません）。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() メソッドは、Node インターフェイスのもので、指定された [`Node`](../../com.aspose.html.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプと定義上の特性（要素の場合は ID、子の数など）を持ち、属性が一致するなどの場合です。必要となるデータポイントの具体的な集合は、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../../com.aspose.html.dom/text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが [`Text`](../../com.aspose.html.dom/text/) ノードを分離する「正規」形に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）で有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/documentfragment/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の要素を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/documentfragment/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての要素の NodeList を返します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、子リスト内で置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) のすべての子で置き換えられ、同じ順序で挿入されます。newChild がすでにツリーに存在する場合、まず削除されます。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [ShadowRoot](../../com.aspose.html.dom/shadowroot/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
