---
title: "SVGMaskElement クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.svg.SVGMaskElement クラス。SVGMaskElement インターフェイスは mask 要素に対応します。"
type: docs

url: /ja/java/com.aspose.html.dom.svg/svgmaskelement/
---
## SVGMaskElement class

SVGMaskElement インターフェイスは ‘mask’ 要素に対応します。

```java
public class SVGMaskElement : SVGElement, ISVGTests, ISVGUnitTypes
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) このノード（Element の場合）の属性を含む NamedNodeMap、またはそれ以外の場合は null。 |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/element/children/) 現在の要素の子要素を返します。 |
| [getClassList](../../com.aspose.html.dom/element/classlist/) "class" 属性の解析から得られたトークンを含むライブ DOMTokenList を返します。 |
| [getClassName](../../com.aspose.html.dom.svg/svgelement/classname/) 指定された要素の ‘class’ 属性に対応します。 |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null を返します。 |
| [getHeight](../../com.aspose.html.dom.svg/svgmaskelement/height/) 指定された ‘mask’ 要素の属性 ‘height’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |
[getId]
[setId] The value of the ‘id’ attribute on the given element, or the empty String if ‘id’ is not present. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
| [getLocalName](../../com.aspose.html.dom/element/localname/) このノードの修飾名のローカル部分を返します。ELEMENT_NODE と ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードの場合、常に null です。 |
| [getMaskContentUnits](../../com.aspose.html.dom.svg/svgmaskelement/maskcontentunits/) 指定された ‘mask’ 要素の属性 ‘maskContentUnits’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |
| [getMaskUnits](../../com.aspose.html.dom.svg/svgmaskelement/maskunits/) 指定された ‘mask’ 要素の属性 ‘maskUnits’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) このノードの名前空間 URI を返します。未指定の場合は null です。 |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く要素兄弟ノードがない場合は null です。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 nextSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) このノードの名前を、タイプに応じて返します。 |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) 基底オブジェクトのタイプを表すコードを返します。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | `[`Node `](../../com.aspose.html.dom/node/)` インターフェイスの nodeValue プロパティは、現在のノードの値を取得または設定します。 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) Node インターフェイスの読み取り専用 ownerDocument プロパティは、そのノードの最上位ドキュメントオブジェクトを返します。 |
| [getOwnerSVGElement](../../com.aspose.html.dom.svg/svgelement/ownersvgelement/) 最も近い先祖の ‘svg’ 要素を返します。対象要素が最上位の svg 要素である場合は null です。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 parentElement プロパティは、DOM ノードの親 [`Element`](../../com.aspose.html.dom/element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) Node インターフェイスの読み取り専用 parentNode プロパティは、DOM ツリー内で指定されたノードの親ノードを返します。 |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) このノードの名前空間プレフィックスを返します。未指定の場合は null です。null に設定されている場合、設定しても効果はありません。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある要素兄弟ノードがない場合は null です。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 previousSibling プロパティは、親の [`childNodes`](../../com.aspose.html.dom/node/firstchild/) リストで指定されたノードの直前にあるノードを返します。そのリストの最初のノードである場合は null を返します。 |
| [getRequiredExtensions](../../com.aspose.html.dom.svg/svgmaskelement/requiredextensions/) 指定された要素の属性 ‘requiredExtensions’ に対応します。 |
| [getRequiredFeatures](../../com.aspose.html.dom.svg/svgmaskelement/requiredfeatures/) 指定された要素の属性 ‘requiredFeatures’ に対応します。 |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) この要素に格納されている shadowRoot を返します。閉じている場合は null です。 |
| [getStyle](../../com.aspose.html.dom.svg/svgelement/style/) 指定された要素の ‘style’ 属性に対応します。ユーザーエージェントが CSS によるスタイリングをサポートしない場合、この属性は常に null の値を持たなければなりません。 |
| [getSystemLanguage](../../com.aspose.html.dom.svg/svgmaskelement/systemlanguage/) 指定された要素の属性 ‘systemLanguage’ に対応します。 |
| [getTagName](../../com.aspose.html.dom/element/tagname/) 要素の名前を返します。 |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子ノードが削除され、かつ新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |
| [getViewportElement](../../com.aspose.html.dom.svg/svgelement/viewportelement/) 現在のビューポートを設定した要素を返します。通常は最も近い先祖の ‘svg’ 要素です。対象要素が最上位の svg 要素である場合は null です。 |
| [getWidth](../../com.aspose.html.dom.svg/svgmaskelement/width/) 指定された ‘mask’ 要素の属性 ‘width’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |
| [X](../../com.aspose.html.dom.svg/svgmaskelement/x/) { get; } | 指定された ‘mask’ 要素の属性 ‘x’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |
| [Y](../../com.aspose.html.dom.svg/svgmaskelement/y/) { get; } | 指定された ‘mask’ 要素の属性 ‘y’ に対応します。SVGUnitTypes で定義された定数のいずれかを取ります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに配送されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener() メソッドは、[EventTarget ](T:com.aspose.html.dom.EventTarget) インターフェイスのもので、指定されたイベントがターゲットに配信されるたびに呼び出される関数を設定します。 |
| [appendChild](../../com.aspose.html.dom/node/appendchild/)(Node) | appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。 |
| [attachShadow](../../com.aspose.html.dom/element/attachshadow/)(ShadowRootMode) | シャドウルートを作成し、現在の要素に添付します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)() | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [cloneNode](../../com.aspose.html.dom/node/clonenode/)(bool) | cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。 |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | 指定された [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) にイベントをディスパッチし、（同期的に）適切な順序で影響を受けた EventListener を呼び出します。通常のイベント処理規則（キャプチャフェーズやオプションのバブリングフェーズを含む）も、[`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) で手動にディスパッチされたイベントに適用されます。 |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [getAttribute](../../com.aspose.html.dom/element/getattribute/)(String) | 属性名で属性値を取得します。 |
| [getAttributeNames](../../com.aspose.html.dom/element/getattributenames/)() | 要素の属性名を文字列の配列として返します。要素に属性がない場合は空の配列を返します。 |
| [getAttributeNode](../../com.aspose.html.dom/element/getattributenode/)(String) | 属性名で属性ノードを取得します。 |
| [getAttributeNodeNS](../../com.aspose.html.dom/element/getattributenodens/)(String, String) | ローカル名とパッケージ URI で Attr ノードを取得します。 |
| [getAttributeNS](../../com.aspose.html.dom/element/getattributens/)(String, String) | ローカル名とパッケージ URI で属性値を取得します。 |
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | 引数で指定されたすべてのクラスを持つ、[`element`](../../com.aspose.html.dom/element/) 内のすべての要素を含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | 指定されたタグ名を持つすべての [`elements`](../../com.aspose.html.dom/element/) を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | 指定されたローカル名とパッケージ URI 文字列を持つすべての [`elements`](../../com.aspose.html.dom/element/) を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | この要素に指定された名前の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでなければ false を返します。 |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | この要素に指定されたローカル名とパッケージ URI の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでなければ false を返します。 |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | このノード（要素の場合）が属性を持っているかどうかを返します。 |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() メソッドは、Node インターフェイスのもので、指定された [`Node`](../../com.aspose.html.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。そのパッケージが対象ノードのデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが同じ型で、定義上の特性（要素の場合は ID、子の数など）が同じで、属性が一致するなどの場合に等しいとみなされます。必要なデータポイントの具体的な集合は、ノードの種類によって異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | Node インターフェイスの isSameNode() メソッドは、=== 厳密等価演算子のレガシーエイリアスです。つまり、2 つのノードが同一か（同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | Node インターフェイスの lookupNamespaceURI() メソッドは、プレフィックスをパラメータとして受け取り、対象ノード上でそれに関連付けられたパッケージ URI を見つけた場合に返し（見つからなければ null を返します）。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | Node インターフェイスの lookupPrefix() メソッドは、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し（存在しなければ null）、複数のプレフィックスが可能な場合は最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | この Node の下位サブツリー全体の深さにあるすべての [`Text`](../../com.aspose.html.dom/text/) ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが [`Text`](../../com.aspose.html.dom/text/) ノードを分離する「正規」形に変換します。つまり、隣接した Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された [`DOMConfiguration`](../../com.aspose.html/configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [querySelector](../../com.aspose.html.dom/element/queryselector/)(String) | ドキュメント内でセレクタに一致する最初の Element を返します。 |
| [querySelectorAll](../../com.aspose.html.dom/element/queryselectorall/)(String) | ドキュメント内でセレクタに一致するすべての Element の NodeList を返します。 |
| [remove](../../com.aspose.html.dom/element/remove/)() | このインスタンスを削除します。 |
| [removeAttribute](../../com.aspose.html.dom/element/removeattribute/)(String) | 名前で属性を削除します。 |
| [removeAttributeNode](../../com.aspose.html.dom/element/removeattributenode/)(Attr) | 指定された属性ノードを削除します。 |
| [removeAttributeNS](../../com.aspose.html.dom/element/removeattributens/)(String, String) | ローカル名とパッケージ URI で属性を削除します。 |
| [removeChild](../../com.aspose.html.dom/node/removechild/)(Node) | Node インターフェイスの `removeChild()` メソッドは、DOM から子ノードを削除し、削除されたノードを返します。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | このメソッドはイベントターゲットからイベントリスナーの削除を可能にします。イベントの処理中にリスナーが削除された場合、現在のアクションではトリガーされません。イベントリスナーは削除された後は決して呼び出されません。 |
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合、最初に削除されます。 |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | 新しい属性を追加します。要素に同名の属性が既に存在する場合、その値は value パラメータの値に変更されます。 |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | 新しい属性ノードを追加します。要素に同名 (nodeName) の属性が既に存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性が既に存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性が既に存在する場合、そのプレフィックスは qualifiedName のプレフィックス部分に変更され、値は value パラメータの値に変更されます。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

### 関連項目

* class [SVGElement](../svgelement/)
* interface [ISVGTests](../isvgtests/)
* interface [ISVGUnitTypes](../isvgunittypes/)
* package [com.aspose.html.dom.svg](../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../)
