---
title: "Element クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.Element クラス。Element インターフェイスは HTML または XML ドキュメント内の要素を表します。"
type: docs

url: /ja/java/com.aspose.html.dom/element/
---
## Element class

Element インターフェイスは、HTML または XML ドキュメント内の要素を表します。

```java
public class Element : Node, IChildNode, IParentNode
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Element](element/)(QualifiedName, Document) | `Element` クラスの新しいインスタンスを初期化します。このコンストラクタを直接呼び出さず、[`CreateElement`](../document/createelement/) または [`CreateElementNS`](../document/createelementns/) を使用してください。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) このノード（Element の場合）の属性を含む NamedNodeMap、またはそれ以外の場合は null。 |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/element/children/) 現在の要素の子要素を返します。 |
| [getClassList](../../com.aspose.html.dom/element/classlist/) \"class\" 属性の解析から得られたトークンを含むライブ DOMTokenList を返します。 |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) 読み取り専用の firstChild プロパティ（[`Node`](../node/) インターフェイス）は、ツリー内のノードの最初の子ノードを返します。子ノードがない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null を返します。 |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) 読み取り専用の lastChild プロパティ（[`Node`](../node/) インターフェイス）は、ノードの最後の子ノードを返します。親が要素である場合、子は通常、要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
| [getLocalName](../../com.aspose.html.dom/element/localname/) このノードの修飾名のローカル部分を返します。ELEMENT_NODE および ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードについては、常に null が返されます。 |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) このノードのパッケージ URI、または未指定の場合は null。 |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く要素兄弟ノードがない場合は null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/childnodes/) 内で指定されたノードの直後のノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) このノードの名前（タイプに応じて）。 |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) 基底オブジェクトのタイプを表すコード。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | [`Node `](../node/) インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 読み取り専用の ownerDocument プロパティ（Node インターフェイス）は、ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../node/) インターフェイス）は、DOM ノードの親 `Element` を返します。親が存在しない、または親が DOM Element でない場合は null が返されます。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) このノードのパッケージプレフィックス、未指定の場合は null。null に設定されている場合、設定しても効果はありません。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある要素兄弟ノードがない場合は null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../node/) インターフェイス）は、親の [`childNodes`](../node/firstchild/) リスト内で指定されたノードの直前のノードを返します。指定されたノードがリストの最初の場合は null を返します。 |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) この要素に格納された shadowRoot を返します。閉じている場合は null。 |
| [getTagName](../../com.aspose.html.dom/element/tagname/) 要素の名前。 |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子が削除され、新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | [`EventTarget `](../eventtarget/) インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送られたときに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（別のノードに追加する前に親ノードから削除する必要はありません）。 |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | シャドウルートを作成し、現在の要素に添付します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) に対してイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | 名前で属性値を取得します。 |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | 要素の属性名を文字列の配列として返します。要素に属性がない場合は空の配列を返します。 |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | 名前で属性ノードを取得します。 |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | ローカル名とパッケージ URI で Attr ノードを取得します。 |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | ローカル名とパッケージ URI で属性値を取得します。 |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | 引数で指定されたすべてのクラスを持つ、`element` 内のすべての要素を含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | 指定されたタグ名を持つすべての `elements` を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | 指定されたローカル名とパッケージ URI 文字列を持つすべての `elements` を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | この要素に指定された名前の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | この要素に指定されたローカル名とパッケージ URI の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | このノード（要素の場合）が属性を持っているかどうかを返します |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | Node インターフェイスの hasChildNodes() メソッドは、指定された [`Node`](../node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | [`Node`](../node/) インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプであり、定義上の特性（要素の場合は ID、子ノード数など）が一致し、属性も一致することを指します。必要なデータ項目の具体的なセットは、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体にあるすべての [`Text`](../text/) ノード（属性ノードを含む）を、構造（例：`elements`、[`comments`](../comment/)、[`processing instructions`](../processinginstruction/)、[`CDATA sections`](../cdatasection/)、[`entity references`](../entityreference/)）だけが [`Text`](../text/) ノードを分離する「正規」形に変換します。つまり、隣接した Text ノードや空の Text ノードは存在しません。この操作は、ドキュメントの DOM 表示が保存後に再読み込みした場合と同じになることを保証でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の要素を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての要素の NodeList を返します。 |
| [remove](../../com.aspose.html.dom/element/remove/)() | このインスタンスを削除します。 |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | 名前で属性を削除します。 |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | 指定された属性ノードを削除します。 |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | ローカル名とパッケージ URI で属性を削除します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドは、イベントターゲットからイベントリスナーを削除することを可能にします。イベント処理中にリスナーが削除された場合、現在のアクションではトリガーされません。削除されたイベントリスナーは二度と呼び出されることはありません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノードのリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../documentfragment/) のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、まず削除されます。 |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | 新しい属性を追加します。要素に同名の属性がすでに存在する場合、その値は value パラメータの値に変更されます。 |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | 新しい属性ノードを追加します。要素に同名の属性 (nodeName) がすでに存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性がすでに存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性がすでに存在する場合、そのプレフィックスは qualifiedName のプレフィックス部分に変更され、値は value パラメータの値に変更されます。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute)(String) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/#toggleattribute_1)(String, bool) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [Node](../node/)
* interface [IChildNode](../ichildnode/)
* interface [IParentNode](../iparentnode/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
