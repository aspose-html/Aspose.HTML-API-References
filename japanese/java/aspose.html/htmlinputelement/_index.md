---
title: "HTMLInputElement クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.HTMLInputElement クラス。フォームコントロール。ページが表示される環境によっては、ファイルアップロード入力タイプの value プロパティが読み取り専用になる場合があります。パスワード入力タイプの場合、実際に返される値は不正使用を防ぐためにマスクされることがあります。HTML 4.01 の INPUT 要素の定義を参照してください。また、Document Object Model DOM Level 2 HTML Specification も参照してください。"
type: docs

url: /ja/java/com.aspose.html/htmlinputelement/
---
## HTMLInputElement class

フォームコントロール。ページが表示される環境に応じて、ファイルアップロード入力タイプの場合、value プロパティは読み取り専用になることがあります。\"password\" 入力タイプの場合、実際に返される値は不正使用を防ぐためにマスクされることがあります。[[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)] の INPUT 要素の定義を参照してください。また、[Document object Model (DOM) Level 2 HTML Specification](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109) も参照してください。

```java
public class HTMLInputElement : HTMLElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getAccept]
[setAccept] A comma-separated list of content types that a server processing this form will handle correctly. See the accept attribute definition in HTML 4.01. |
[getAccessKey]
[setAccessKey] A single character access key to give access to the form control. See the accesskey attribute definition in HTML 4.01. |
[getAlign]
[setAlign] Aligns this object (vertically or horizontally) with respect to its surrounding text. See the align attribute definition in HTML 4.01. This attribute is deprecated in HTML 4.01. |
[getAlt]
[setAlt] Alternate text for user agents not rendering the normal content of this element. See the alt attribute definition in HTML 4.01. |
| [getAttributes](../../com.aspose.html.dom/element/attributes/) このノード（Element の場合）の属性を含む NamedNodeMap、またはそれ以外の場合は null。 |
| [getBaseURI](../../com.aspose.html.dom/node/baseuri/) Node インターフェイスの読み取り専用 baseURI プロパティは、ノードを含むドキュメントの絶対ベース URL を返します。 |
[getChecked]
[setChecked] When the `type` attribute of the element has the value "radio" or "checkbox", this represents the current state of the form control, in an interactive user agent. Changes to this attribute change the state of the form control, but do not change the value of the HTML checked attribute of the INPUT element.During the handling of a click event on an input element with a type attribute that has the value "radio" or "checkbox", some implementations may change the value of this property before the event is being dispatched in the document. If the default action of the event is canceled, the value of the property may be changed back to its original value. This means that the value of this property during the handling of click events is implementation dependent. |
| [getChildElementCount](../../com.aspose.html.dom/element/childelementcount/) この要素の子である要素ノードの現在の数を返します。nodeType が 1 の子ノードがない場合は 0 を返します。 |
| [getChildNodes](../../com.aspose.html.dom/node/childnodes/) Node インターフェイスの読み取り専用 childNodes プロパティは、指定された要素の子ノードのライブ [`NodeList`](../../com.aspose.html.collections/nodelist/) を返します。最初の子ノードはインデックス 0 が割り当てられます。子ノードには要素、テキスト、コメントが含まれます。 |
| [getChildren](../../com.aspose.html.dom/element/children/) 現在の要素の子要素を返します。 |
| [getClassList](../../com.aspose.html.dom/element/classlist/) \"class\" 属性の解析から得られたトークンを含むライブ DOMTokenList を返します。 |
[getClassName]
[setClassName] The class attribute of the element. This attribute has been renamed due to conflicts with the "class" keyword exposed by many languages. See the class attribute definition in HTML 4.01. |
[getDefaultChecked]
[setDefaultChecked] When `type` has the value "radio" or "checkbox", this represents the HTML checked attribute of the element. The value of this attribute does not change if the state of the corresponding form control, in an interactive user agent, changes. See the checked attribute definition in HTML 4.01. |
[getDefaultValue]
[setDefaultValue] When the `type` attribute of the element has the value "text", "file" or "password", this represents the HTML value attribute of the element. The value of this attribute does not change if the contents of the corresponding form control, in an interactive user agent, changes. See the value attribute definition in HTML 4.01. |
[getDir]
[setDir] Specifies the base direction of directionally neutral text and the directionality of tables. See the dir attribute definition in HTML 4.01. |
[getDisabled]
[setDisabled] The control is unavailable in this context. See the disabled attribute definition in HTML 4.01. |
| [getFiles](../../com.aspose.html/htmlinputelement/files/) files IDL 属性により、スクリプトは要素の選択されたファイルにアクセスできます。取得時に IDL 属性が適用される場合、現在選択されているファイルを表す FileList オブジェクトを返す必要があります。選択されたファイルのリストが変更されるまで同じオブジェクトを返し続けます。IDL 属性が適用されない場合は、代わりに null を返す必要があります。 [FILEAPI] |
| [getFirstChild](../../com.aspose.html.dom/node/firstchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 firstChild プロパティは、ツリー内のノードの最初の子を返します。子がない場合は null を返します。 |
| [getFirstElementChild](../../com.aspose.html.dom/element/firstelementchild/) この要素の最初の子要素ノードを返します。子要素がない場合は null を返します。 |
[getForm]
[setForm] Returns the `FORM` element containing this control. Returns `null` if this control is not within the context of a form. |
[getId]
[setId] The element's identifier. See the id attribute definition in HTML 4.01. |
[getInnerHTML]
[setInnerHTML] Returns a fragment of HTML or XML that represents the element's contents. Can be set, to replace the contents of the element with nodes parsed from the given String. |
[getLang]
[setLang] Language code defined in RFC 1766. See the lang attribute definition in HTML 4.01. |
| [getLastChild](../../com.aspose.html.dom/node/lastchild/) [`Node`](../../com.aspose.html.dom/node/) インターフェイスの読み取り専用 lastChild プロパティは、ノードの最後の子を返します。親が要素の場合、子は通常要素ノード、テキストノード、またはコメントノードです。子要素がない場合は null を返します。 |
| [getLastElementChild](../../com.aspose.html.dom/element/lastelementchild/) この要素の最後の子要素ノードを返します。子要素がない場合は null です。 |
[getList]
[setList] The list attribute is used to identify an element that lists predefined options suggested to the user. If present, its value must be the ID of a datalist element in the same document. |
| [getLocalName](../../com.aspose.html.dom/element/localname/) このノードの修飾名のローカル部分を返します。ELEMENT_NODE および ATTRIBUTE_NODE 以外のタイプのノードや、Document.createElement() のような DOM Level 1 メソッドで作成されたノードについては、常に null が返されます。 |
[getMaxLength]
[setMaxLength] Maximum number of characters for text fields, when `type`has the value "text" or "password". See the maxlength attribute definition in HTML 4.01. |
[getName]
[setName] Form control or object name when submitted with a form. See the name attribute definition in HTML 4.01. |
| [getNamespaceURI](../../com.aspose.html.dom/element/packageuri/) このノードのパッケージ URI、または未指定の場合は null。 |
| [getNextElementSibling](../../com.aspose.html.dom/element/nextelementsibling/) この要素の次の兄弟要素ノードを返します。文書ツリーでこの要素の後に続く要素兄弟ノードがない場合は null。 |
| [getNextSibling](../../com.aspose.html.dom/node/nextsibling/) 読み取り専用の nextSibling プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、親の [`childNodes`](../../com.aspose.html.dom/node/childnodes/) 内で指定されたノードの直後にあるノードを返します。指定されたノードが親要素の最後の子である場合は null を返します。 |
| [getNodeName](../../com.aspose.html.dom/element/nodename/) このノードの名前（タイプに応じて）。 |
| [getNodeType](../../com.aspose.html.dom/element/nodetype/) 基底オブジェクトのタイプを表すコード。 |
| [nodeValue](../../com.aspose.html.dom/node/nodevalue/) { get; set; } | nodeValue プロパティ（[`Node `](../../com.aspose.html.dom/node/) インターフェイス）は、現在のノードの値を取得または設定します。 |
[getOuterHTML]
[setOuterHTML] Returns a fragment of HTML or XML that represents the element and its contents. Can be set, to replace the element with nodes parsed from the given String. |
| [getOwnerDocument](../../com.aspose.html.dom/node/ownerdocument/) 読み取り専用の ownerDocument プロパティ（Node インターフェイス）は、ノードのトップレベルのドキュメントオブジェクトを返します。 |
| [getParentElement](../../com.aspose.html.dom/node/parentelement/) 読み取り専用の parentElement プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、DOM ノードの親 [`Element`](../../com.aspose.html.dom/element/) を返します。ノードに親がない、または親が DOM Element でない場合は null を返します。 |
| [getParentNode](../../com.aspose.html.dom/node/parentnode/) 読み取り専用の parentNode プロパティ（Node インターフェイス）は、DOM ツリー内で指定されたノードの親を返します。 |
| [getPrefix](../../com.aspose.html.dom/element/prefix/) このノードのパッケージプレフィックス、未指定の場合は null。null に設定されている場合、設定しても効果はありません。 |
| [getPreviousElementSibling](../../com.aspose.html.dom/element/previouselementsibling/) この要素の前の兄弟要素ノードを返します。文書ツリーでこの要素の前にある要素兄弟ノードがない場合は null。 |
| [getPreviousSibling](../../com.aspose.html.dom/node/previoussibling/) 読み取り専用の previousSibling プロパティ（[`Node`](../../com.aspose.html.dom/node/) インターフェイス）は、親の [`childNodes`](../../com.aspose.html.dom/node/firstchild/) リストで指定されたノードの直前にあるノードを返します。そのリストで指定ノードが最初の場合は null を返します。 |
[getReadOnly]
[setReadOnly] This control is read-only. Relevant only when `type` has the value "text" or "password". See the readonly attribute definition in HTML 4.01. |
| [getShadowRoot](../../com.aspose.html.dom/element/shadowroot/) この要素に格納された shadowRoot を返します。閉じている場合は null。 |
[getSize]
[setSize] Size information. The precise meaning is specific to each type of field. See the size attribute definition in HTML 4.01. @version DOM Level 2 |
[getSrc]
[setSrc] When the `type` attribute has the value "image", this attribute specifies the location of the image to be used to decorate the graphical submit button. See the src attribute definition in HTML 4.01. |
| [getStyle](../../com.aspose.html/htmlelement/style/) 特定の要素に直接スタイル情報を適用できるようにするスタイル属性を表します。 |
[getTabIndex]
[setTabIndex] Index that represents the element's position in the tabbing order. See the tabindex attribute definition in HTML 4.01. |
| [getTagName](../../com.aspose.html.dom/element/tagname/) 要素の名前。 |
| [textContent](../../com.aspose.html.dom/element/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキストコンテンツを返します。null に設定されている場合、設定しても効果はありません。設定すると、このノードが持つ可能性のあるすべての子が削除され、新しい文字列が空でなく null でもない場合は、その文字列を含む単一の Text ノードに置き換えられます。 |
[getTitle]
[setTitle] The element's advisory title. See the title attribute definition in HTML 4.01. |
[getType]
[setType] The type of control created (all lower case). See the type attribute definition in HTML 4.01. @version DOM Level 2 |
[getUseMap]
[setUseMap] Use client-side image map. See the usemap attribute definition in HTML 4.01. |
[getValue]
[setValue] When the `type` attribute of the element has the value "text", "file" or "password", this represents the current contents of the corresponding form control, in an interactive user agent. Changing this attribute changes the contents of the form control, but does not change the value of the HTML value attribute of the element. When the `type` attribute of the element has the value "button", "hidden", "submit", "reset", "image", "checkbox" or "radio", this represents the HTML value attribute of the element. See the value attribute definition in HTML 4.01. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | `[`EventTarget `](../../com.aspose.html.dom/eventtarget/)` インターフェイスの addEventListener() メソッドは、指定されたイベントがターゲットに送信されるたびに呼び出される関数を設定します。 |
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
| [getElementsByClassName](../../com.aspose.html.dom/element/getelementsbyclassname/)(String) | 引数で指定されたすべてのクラスを持つ、[`element`](../../com.aspose.html.dom/element/) 内のすべての要素を含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagName](../../com.aspose.html.dom/element/getelementsbytagname/)(String) | 指定されたタグ名を持つすべての [`elements`](../../com.aspose.html.dom/element/) を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getElementsByTagNameNS](../../com.aspose.html.dom/element/getelementsbytagnamens/)(String, String) | 指定されたローカル名とパッケージ URI 文字列を持つすべての [`elements`](../../com.aspose.html.dom/element/) を文書順で含む [`HTMLCollection`](../../com.aspose.html.collections/htmlcollection/) オブジェクトを返します。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [hasAttribute](../../com.aspose.html.dom/element/hasattribute/)(String) | この要素に指定された名前の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [hasAttributeNS](../../com.aspose.html.dom/element/hasattributens/)(String, String) | この要素に指定されたローカル名とパッケージ URI の属性が存在するか、デフォルト値を持つ場合は true を返し、そうでない場合は false を返します。 |
| [hasAttributes](../../com.aspose.html.dom/element/hasattributes/)() | このノード（要素の場合）が属性を持っているかどうかを返します |
| [hasChildNodes](../../com.aspose.html.dom/node/haschildnodes/)() | hasChildNodes() メソッドは、Node インターフェイスのもので、指定された [`Node`](../../com.aspose.html.dom/node/) が子ノードを持つかどうかを示すブール値を返します。 |
| [insertBefore](../../com.aspose.html.dom/node/insertbefore/)(Node, Node) | insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。 |
| [isDefaultNamespace](../../com.aspose.html.dom/node/isdefaultpackage/)(String) | isDefaultNamespace() メソッドは、Node インターフェイスのもので、パッケージ URI を引数として受け取ります。指定されたノードでそのパッケージがデフォルトパッケージである場合は true、そうでない場合は false を返します。 |
| [isEqualNode](../../com.aspose.html.dom/node/isequalnode/)(Node) | `Node` インターフェイスの isEqualNode() メソッドは、2 つのノードが等しいかどうかをテストします。ノードが等しいとは、同じタイプと定義上の特性（要素の場合は ID、子の数など）を持ち、属性が一致するなどの場合です。必要となるデータポイントの具体的な集合は、ノードのタイプに応じて異なります。 |
| [isSameNode](../../com.aspose.html.dom/node/issamenode/)(Node) | isSameNode() メソッドは、Node インターフェイスのレガシーエイリアスで、=== の厳密等価演算子の代わりです。つまり、2 つのノードが同一か（言い換えれば、同じオブジェクトを参照しているか）をテストします。 |
| [lookupNamespaceURI](../../com.aspose.html.dom/node/lookuppackageuri/)(String) | lookupNamespaceURI() メソッドは、Node インターフェイスのもので、プレフィックスをパラメータとして受け取り、該当ノード上でそれに関連付けられたパッケージ URI を見つかれば返し、見つからなければ null を返します。 |
| [lookupPrefix](../../com.aspose.html.dom/node/lookupprefix/)(String) | lookupPrefix() メソッドは、Node インターフェイスのもので、指定されたパッケージ URI に対するプレフィックスを含む文字列を返し、存在しなければ null を返します。複数のプレフィックスが可能な場合は、最初のプレフィックスが返されます。 |
| [normalize](../../com.aspose.html.dom/node/normalize/)() | このノード以下のサブツリー全体の深さにあるすべての[`Text`](../../com.aspose.html.dom/text/)ノード（属性ノードを含む）を、構造（例：[`elements`](../../com.aspose.html.dom/element/)、[`comments`](../../com.aspose.html.dom/comment/)、[`processing instructions`](../../com.aspose.html.dom/processinginstruction/)、[`CDATA sections`](../../com.aspose.html.dom/cdatasection/)、[`entity references`](../../com.aspose.html.dom/entityreference/)）だけが[`Text`](../../com.aspose.html.dom/text/)ノードを分離する「通常」形式に変換します。つまり、隣接する Text ノードや空の Text ノードは存在しません。これは、ドキュメントの DOM 表示が保存して再読み込みした場合と同じになることを保証するために使用でき、特定のドキュメントツリー構造に依存する操作（例：XPointer [XPointer] ルックアップ）を使用する際に有用です。[`Node.ownerDocument`](../../com.aspose.html.dom/node/ownerdocument/) に添付された[`DOMConfiguration`](../configuration/) オブジェクトのパラメータ "normalize-characters" が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
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
| [replaceChild](../../com.aspose.html.dom/node/replacechild/)(Node, Node) | 子ノード oldChild を newChild に置き換え、子リスト内で置き換え、oldChild ノードを返します。newChild が [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) オブジェクトの場合、oldChild はその [`DocumentFragment`](../../com.aspose.html.dom/documentfragment/) のすべての子で置き換えられ、同じ順序で挿入されます。newChild がすでにツリーに存在する場合、まず削除されます。 |
| [setAttribute](../../com.aspose.html.dom/element/setattribute/)(String, String) | 新しい属性を追加します。要素に同名の属性がすでに存在する場合、その値は value パラメータの値に変更されます。 |
| [setAttributeNode](../../com.aspose.html.dom/element/setattributenode/)(Attr) | 新しい属性ノードを追加します。要素に同名の属性 (nodeName) がすでに存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNodeNS](../../com.aspose.html.dom/element/setattributenodens/)(Attr) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性がすでに存在する場合、新しい属性で置き換えられます。 |
| [setAttributeNS](../../com.aspose.html.dom/element/setattributens/)(String, String, String) | 新しい属性を追加します。要素に同じローカル名とパッケージ URI の属性がすでに存在する場合、そのプレフィックスは qualifiedName のプレフィックス部分に変更され、値は value パラメータの値に変更されます。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toggleAttribute](../../com.aspose.html.dom/element/toggleattribute/)(String, bool) | force が指定されていない場合、qualifiedName を「トグル」し、存在すれば削除し、存在しなければ追加します。force が true の場合は qualifiedName を追加し、false の場合は削除します。 |
| [toString](../../com.aspose.html.dom/node/toString/)() | このインスタンスを表す文字列を返します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnAbort](../../com.aspose.html/htmlelement/onabort/) | OnAbort イベントのハンドラを取得または設定します。 |
| event [OnBlur](../../com.aspose.html/htmlelement/onblur/) | OnBlur イベントのハンドラを取得または設定します。 |
| event [OnCancel](../../com.aspose.html/htmlelement/oncancel/) | OnCancel イベントのハンドラを取得または設定します。 |
| event [OnCanplay](../../com.aspose.html/htmlelement/oncanplay/) | OnCanplay イベントのハンドラを取得または設定します。 |
| event [OnCanPlayThrough](../../com.aspose.html/htmlelement/oncanplaythrough/) | OnCanPlayThrough イベントのハンドラを取得または設定します。 |
| event [OnChange](../../com.aspose.html/htmlelement/onchange/) | OnChange イベントのハンドラを取得または設定します。 |
| event [OnClick](../../com.aspose.html/htmlelement/onclick/) | OnClick イベントのハンドラを取得または設定します。 |
| event [OnCueChange](../../com.aspose.html/htmlelement/oncuechange/) | OnCueChange イベントのハンドラを取得または設定します。 |
| event [OnDblClick](../../com.aspose.html/htmlelement/ondblclick/) | OnDblClick イベントのハンドラを取得または設定します。 |
| event [OnDurationChange](../../com.aspose.html/htmlelement/ondurationchange/) | OnDurationChange イベントのハンドラを取得または設定します。 |
| event [OnEmptied](../../com.aspose.html/htmlelement/onemptied/) | OnEmptied イベントのハンドラを取得または設定します。 |
| event [OnEnded](../../com.aspose.html/htmlelement/onended/) | OnEnded イベントのハンドラを取得または設定します。 |
| event [OnError](../../com.aspose.html/htmlelement/onerror/) | OnError イベントのハンドラを取得または設定します。 |
| event [OnFocus](../../com.aspose.html/htmlelement/onfocus/) | OnFocus イベントのハンドラを取得または設定します。 |
| event [OnInput](../../com.aspose.html/htmlelement/oninput/) | OnInput イベントのハンドラを取得または設定します。 |
| event [OnInvalid](../../com.aspose.html/htmlelement/oninvalid/) | OnInvalid イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyDown](../../com.aspose.html/htmlelement/onkeydown/) | OnKeyDown イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyPress](../../com.aspose.html/htmlelement/onkeypress/) | OnKeyPress イベントのイベントハンドラを取得または設定します。 |
| event [OnKeyUp](../../com.aspose.html/htmlelement/onkeyup/) | OnKeyUp イベントのイベントハンドラを取得または設定します。 |
| event [OnLoad](../../com.aspose.html/htmlelement/onload/) | OnLoad イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadedData](../../com.aspose.html/htmlelement/onloadeddata/) | OnLoadedData イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadedMetadata](../../com.aspose.html/htmlelement/onloadedmetadata/) | OnLoadedMetadata イベントのイベントハンドラを取得または設定します。 |
| event [OnLoadStart](../../com.aspose.html/htmlelement/onloadstart/) | OnLoadStart イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseDown](../../com.aspose.html/htmlelement/onmousedown/) | OnMouseDown イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseEnter](../../com.aspose.html/htmlelement/onmouseenter/) | OnMouseEnter イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseLeave](../../com.aspose.html/htmlelement/onmouseleave/) | OnMouseLeave イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseMove](../../com.aspose.html/htmlelement/onmousemove/) | OnMouseMove イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseOut](../../com.aspose.html/htmlelement/onmouseout/) | OnMouseOut イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseOver](../../com.aspose.html/htmlelement/onmouseover/) | OnMouseOver イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseUp](../../com.aspose.html/htmlelement/onmouseup/) | OnMouseUp イベントのイベントハンドラを取得または設定します。 |
| event [OnMouseWheel](../../com.aspose.html/htmlelement/onmousewheel/) | OnMouseWheel イベントのイベントハンドラを取得または設定します。 |
| event [OnPause](../../com.aspose.html/htmlelement/onpause/) | OnPause イベントのイベントハンドラを取得または設定します。 |
| event [OnPlay](../../com.aspose.html/htmlelement/onplay/) | OnPlay イベントのイベントハンドラを取得または設定します。 |
| event [OnPlaying](../../com.aspose.html/htmlelement/onplaying/) | OnPlaying イベントのイベントハンドラを取得または設定します。 |
| event [OnProgress](../../com.aspose.html/htmlelement/onprogress/) | OnProgress イベントのイベントハンドラを取得または設定します。 |
| event [OnRateChange](../../com.aspose.html/htmlelement/onratechange/) | OnRateChange イベントのイベントハンドラを取得または設定します。 |
| event [OnReset](../../com.aspose.html/htmlelement/onreset/) | OnReset イベントのイベントハンドラを取得または設定します。 |
| event [OnResize](../../com.aspose.html/htmlelement/onresize/) | OnResize イベントのイベントハンドラを取得または設定します。 |
| event [OnScroll](../../com.aspose.html/htmlelement/onscroll/) | OnScroll イベントのイベントハンドラを取得または設定します。 |
| event [OnSeeked](../../com.aspose.html/htmlelement/onseeked/) | OnSeeked イベントのハンドラを取得または設定します。 |
| event [OnSeeking](../../com.aspose.html/htmlelement/onseeking/) | OnSeeking イベントのハンドラを取得または設定します。 |
| event [OnSelect](../../com.aspose.html/htmlelement/onselect/) | OnSelect イベントのハンドラを取得または設定します。 |
| event [OnShow](../../com.aspose.html/htmlelement/onshow/) | OnShow イベントのハンドラを取得または設定します。 |
| event [OnStalled](../../com.aspose.html/htmlelement/onstalled/) | OnStalled イベントのハンドラを取得または設定します。 |
| event [OnSubmit](../../com.aspose.html/htmlelement/onsubmit/) | OnSubmit イベントのハンドラを取得または設定します。 |
| event [OnSuspend](../../com.aspose.html/htmlelement/onsuspend/) | OnSuspend イベントのハンドラを取得または設定します。 |
| event [OnTimeUpdate](../../com.aspose.html/htmlelement/ontimeupdate/) | OnTimeUpdate イベントのハンドラを取得または設定します。 |
| event [OnToggle](../../com.aspose.html/htmlelement/ontoggle/) | OnToggle イベントのハンドラを取得または設定します。 |
| event [OnVolumeChange](../../com.aspose.html/htmlelement/onvolumechange/) | OnVolumeChange イベントのハンドラを取得または設定します。 |
| event [OnWaiting](../../com.aspose.html/htmlelement/onwaiting/) | OnWaiting イベントのハンドラを取得または設定します。 |

## 例

```java
import System;
import System.IO;
import Aspose.Html;
import com.aspose.html.forms;
...
import (var document = new HTMLDocument(inputHtmlPath))
{
	HTMLFormElement formElement = (HTMLFormElement) document.CreateElement("form");
	// ラベル要素 - 名
	// <label for=\"fname\">名:</label><br>
	HTMLLabelElement labelFirstName = (HTMLLabelElement)document.CreateElement("label");
	labelFirstName.For = "fname";
	labelFirstName.InnerHTML = "First name:";
	formElement.AppendChild(labelFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// 名の入力要素
	// <input type=\"text\" id=\"fname\" name=\"fname\"><br>
	HTMLInputElement inputFirstName = (HTMLInputElement)document.CreateElement("input");
	inputFirstName.Type = InputElementType.Text.ToString(); // "text";
	inputFirstName.Id = "fname";
	inputFirstName.Name = "fname";
	formElement.AppendChild(inputFirstName);
	formElement.AppendChild(document.CreateElement("br"));

	// ラベル要素 - 姓
	// <label for=\"lname\">姓:</label><br>
	HTMLLabelElement labelLastName = (HTMLLabelElement)document.CreateElement("label");
	labelLastName.For = "lname";
	labelLastName.InnerHTML = "Last name:";
	formElement.AppendChild(labelLastName);
	formElement.AppendChild(document.CreateElement("br"));

	// 姓の入力要素
	// <input type=\"text\" id=\"lname\" name=\"lname\"><br><br>
	HTMLInputElement inputLastName = (HTMLInputElement)document.CreateElement("input");
	inputLastName.Type = InputElementType.Text.ToString(); // "text";
	inputLastName.Id = "lname";
	inputLastName.Name = "lname";
	formElement.AppendChild(inputLastName);
	formElement.AppendChild(document.CreateElement("br"));
	formElement.AppendChild(document.CreateElement("br"));

	// 入力要素 - 送信
	HTMLInputElement inputSubmit = (HTMLInputElement)document.CreateElement("input");
	inputSubmit.Type = InputElementType.Submit.ToString(); // "submit";
	inputSubmit.Value = "Submit";
	formElement.AppendChild(inputSubmit);
         
	document.Body.AppendChild(formElement);
         
	var outputFilePath = Path.Combine(outputHtmlPath, "result.html");
	document.Save(outputFilePath);
}
```

*inputHtmlPath - user input html file path.

*outputHtmlPath - user output folder path.

### 関連項目

* class [HTMLElement](../htmlelement/)
* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
