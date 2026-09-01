---
title: "Attr クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Attr クラス。Attr インターフェイスは Element オブジェクト内の属性を表します。通常、属性に許容される値はドキュメントに関連付けられたスキーマで定義されます。"
type: docs

url: /ja/java/com.aspose.html.dom/attr/
---
## Attr class

Attr インターフェイスは Element オブジェクト内の属性を表します。通常、属性の許容値はドキュメントに関連付けられたスキーマで定義されます。

```java
public sealed class Attr : Node
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（[`Node`](../node/) インターフェイス）は、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（[`Node`](../node/) インターフェイス）は、ノードの最後の子を返します。親が要素の場合、子は通常、要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLocalName](../../com.aspose.html.dom/attr/localname/) このノードの修飾名のローカル部分を返します。ELEMENT_NODE と ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードの場合、常に null が返されます。 |
| [getName](../../com.aspose.html.dom/attr/name/) この属性の名前を返します。 |
| [getNamespaceURI](../../com.aspose.html.dom/attr/packageuri/) このノードのパッケージ URI を返します。未指定の場合は null です。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../node/) インターフェイス）は、指定されたノードの親の [`childNodes`](../node/childnodes/) 内で直後のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/attr/nodename/) このノードの名前を、タイプに応じて返します。 |
| [getNodeType](../../com.aspose.html.dom/attr/nodetype/) 基底オブジェクトのタイプを表すコードです。 |
| [nodeValue](../../com.aspose.html.dom/attr/nodevalue/) { get; set; } | このノードの値を、タイプに応じて返します。 |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node インターフェイスの読み取り専用 ownerDocument プロパティは、そのノードの最上位ドキュメントオブジェクトを返します。 |
| [getOwnerElement](../../com.aspose.html.dom/attr/ownerelement/) この属性が付属している Element ノードを返します。使用されていない場合は null です。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../node/) インターフェイス）は、DOM ノードの親 [`Element`](../element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [getPrefix](../../com.aspose.html.dom/attr/prefix/) このノードのパッケージプレフィックスを返します。未指定の場合は null です。null に設定されている場合、設定しても効果はありません。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../node/) インターフェイス）は、指定されたノードの親の [`childNodes`](../node/firstchild/) リストで直前のノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [getSpecified](../../com.aspose.html.dom/attr/specified/) インスタンスドキュメントでこの属性に明示的に値が設定されていれば true、そうでなければ false を返します。 |
| [textContent](../../com.aspose.html.dom/attr/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子ノードが削除され、かつ新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |
[getValue]
[setValue] On retrieval, the value of the attribute is returned as a String. |

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
