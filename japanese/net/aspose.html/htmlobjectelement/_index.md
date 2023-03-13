---
title: Class HTMLObjectElement
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.HTMLObjectElement クラス. 汎用埋め込みオブジェクト原則としてオブジェクト要素 のすべてのプロパティは読み書き可能ですが一部の環境では基になるオブジェクトがインスタンス化されると一部のプロパティが読み取り専用 になる場合があります  の OBJECT 要素 定義を参照してくださいHTML4.01 .
type: docs
weight: 3440
url: /ja/net/aspose.html/htmlobjectelement/
---
## HTMLObjectElement class

汎用埋め込みオブジェクト。原則として、オブジェクト要素 のすべてのプロパティは読み書き可能ですが、一部の環境では、基になるオブジェクトがインスタンス化されると、一部のプロパティが読み取り専用 になる場合があります。 [ の OBJECT 要素 定義を参照してください。[HTML4.01](http://www.w3.org/TR/1999/REC-html401-19991224) ].

も参照してください。[ドキュメント オブジェクト モデル (DOM) レベル 2 HTML 仕様](http://www.w3.org/TR/2003/REC-DOM-Level-2-HTML-20030109).

```csharp
public class HTMLObjectElement : HTMLElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Align](../../aspose.html/htmlobjectelement/align/) { get; set; } | このオブジェクトを周囲のテキストに対して (垂直または水平に) 配置します。 HTML 4.01 の align 属性の定義を参照してください。この属性は、HTML 4.01. で廃止されました。 |
| [Archive](../../aspose.html/htmlobjectelement/archive/) { get; set; } | スペースで区切られたアーカイブのリスト。 HTML 4.01. のアーカイブ属性の定義を参照してください。 |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | このノードの属性を含む NamedNodeMap (要素の場合)、またはそれ以外の場合は null. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | このノードの絶対ベース URI、または実装が絶対 URI を取得できなかった場合は null。 |
| [Border](../../aspose.html/htmlobjectelement/border/) { get; set; } | オブジェクトの境界線の幅。 HTML 4.01 の border 属性の定義を参照してください。この属性は、HTML 4.01. で廃止されました。 |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。この要素に nodeType 1. の子ノードがない場合は 0 |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | このノードのすべての子を含む NodeList。子がない場合、これはノードを含まない NodeList です.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | 現在の要素の子要素を返します. |
| [ClassId](../../aspose.html/htmlobjectelement/classid/) { get; set; } | Windows レジストリまたは URL に設定されているクラス ID 値を定義します。 |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | 「クラス」属性の解析から受け取ったトークンを含むライブ DOMTokenList を返します。 |
| [ClassName](../../aspose.html/htmlelement/classname/) { get; set; } | 要素のクラス属性。この属性は、多くの言語で公開されている「class」キーワードと競合するため、 のために名前が変更されました。 HTML 4.01. のクラス属性定義を参照してください。 |
| [Code](../../aspose.html/htmlobjectelement/code/) { get; set; } | アプレット クラス ファイル。を参照してください`コード`HTMLAppletElement の属性。 |
| [CodeBase](../../aspose.html/htmlobjectelement/codebase/) { get; set; } | ベース URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt) ] ために`クラスID`、`データ`、および `アーカイブ`属性。 HTML 4.01. の codebase 属性 definition を参照してください。 |
| [CodeType](../../aspose.html/htmlobjectelement/codetype/) { get; set; } | 経由でダウンロードされたデータのコンテンツ タイプ`クラスID`属性。 HTML 4.01 の codetype 属性の定義を参照してください。 |
| [Data](../../aspose.html/htmlobjectelement/data/) { get; set; } | URI [[IETF RFC 2396](http://www.ietf.org/rfc/rfc2396.txt) ] オブジェクトのデータの場所を指定します。 HTML 4.01. の data 属性の定義を参照してください。 |
| [Declare](../../aspose.html/htmlobjectelement/declare/) { get; set; } | このオブジェクトを (後で参照するために) 宣言しますが、インスタンス化はしません。 HTML 4.01. の declare 属性の定義を参照してください。 |
| [Dir](../../aspose.html/htmlelement/dir/) { get; set; } | 方向的にニュートラルなテキストのベース方向とテーブルの 方向性を指定します。 HTML 4.01. の dir 属性の定義を参照してください。 |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | このノードの最初の子。そのようなノードがない場合、これは null. を返します。 |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。この要素に子要素がない場合は null. |
| [Form](../../aspose.html/htmlobjectelement/form/) { get; set; } | を返します`形状`このコントロールを含む要素。戻り値`ヌル`このコントロールがフォームのコンテキスト内にない場合。 |
| [Height](../../aspose.html/htmlobjectelement/height/) { get; set; } | 高さをオーバーライドします。 HTML 4.01. の高さ属性の定義を参照してください。 |
| [Hspace](../../aspose.html/htmlobjectelement/hspace/) { get; set; } | このイメージ、 アプレット、またはオブジェクトの左右の水平方向のスペース (ピクセル単位)。 HTML 4.01 の hspace 属性の定義を参照してください。 この属性は、HTML 4.01. で廃止されました。 |
| [Id](../../aspose.html/htmlelement/id/) { get; set; } | 要素の識別子。 HTML 4.01. の id 属性の定義を参照してください。 |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | 要素のコンテンツを表す HTML または XML のフラグメントを返します。 設定して、要素のコンテンツを指定された文字列から解析されたノードに置き換えることができます。 |
| [Lang](../../aspose.html/htmlelement/lang/) { get; set; } | RFC 1766 で定義された言語コード。 HTML 4.01. の lang 属性の定義を参照してください。 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | このノードの最後の子。そのようなノードがない場合、これは null. を返します。 |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。この要素に子要素がない場合は null. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | このノードの修飾名のローカル部分を返します。 ELEMENT_NODE および ATTRIBUTE_NODE 以外のタイプのノード、および Document.createElement() などの DOM レベル 1 メソッドで作成されたノードの場合、これは常に null です。 |
| [Name](../../aspose.html/htmlobjectelement/name/) { get; set; } | フォームで送信された場合のフォーム コントロールまたはオブジェクト名。 HTML 4.01. の name 属性の定義を参照してください。 |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | このノードの名前空間 URI、または指定されていない場合は null. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。この要素に、ドキュメント ツリーでこの要素の後に続く要素兄弟ノードがない場合は null. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | このノードの直後のノード。そのようなノードがない場合、これは null. を返します。 |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | タイプに応じたこのノードの名前. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | 基礎となるオブジェクトのタイプを表すコード. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | タイプに応じたこのノードの値. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | 要素とそのコンテンツを表す HTML または XML のフラグメントを返します。 設定して、指定された文字列から解析されたノードで要素を置き換えることができます。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | このノードに関連付けられたドキュメント オブジェクト。これは、新しいノードを作成するために使用される Document オブジェクトでもあります。このノードがドキュメントまたはドキュメントでまだ使用されていない DocumentType である場合、これは null. です。 |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 親を取得します[`Element`](../../aspose.html.dom/element/)このノードの. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | このノードの親。 Attr、Document、DocumentFragment、Entity、および Notation を除くすべてのノードは、親を持つことができます。ただし、ノードが作成されたばかりでまだツリーに追加されていない場合、またはツリーから削除されている場合、これは null. です。 |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | このノードの名前空間プレフィックス、または指定されていない場合は null。 null と定義されている場合、設定しても効果はありません |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。この要素に、ドキュメント ツリー内でこの要素の前にある要素の兄弟ノードがない場合は null. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | このノードの直前のノード。そのようなノードがない場合、これは null. を返します。 |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | この要素に関連付けられた型情報。 |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | この要素に格納されている shadowRoot を返すか、閉じている場合は null を返します。 |
| [Standby](../../aspose.html/htmlobjectelement/standby/) { get; set; } | オブジェクトのロード中にレンダリングするメッセージ。 HTML 4.01. のスタンバイ属性 定義を参照してください。 |
| [Style](../../aspose.html/htmlelement/style/) { get; } | 作成者がスタイル情報を特定の要素に直接適用できるようにするスタイル属性を表します. |
| [TabIndex](../../aspose.html/htmlobjectelement/tabindex/) { get; set; } | タブ順序での要素の位置を表すインデックス。 HTML 4.01 の tabindex 属性定義を参照してください。 |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | 要素の名前。 |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキスト コンテンツを返します。 null として定義されている場合、設定しても効果はありません。設定時に、このノードが持つ可能性のある子はすべて削除され、新しい文字列が空または null でない場合は、この属性が設定されている文字列を含む単一の Text ノードに置き換えられます。 |
| [Title](../../aspose.html/htmlelement/title/) { get; set; } | 要素の勧告のタイトル。 HTML 4.01. の title 属性の定義を参照してください。 |
| [Type](../../aspose.html/htmlobjectelement/type/) { get; set; } | 経由でダウンロードされたデータのコンテンツ タイプ`データ`属性。 HTML 4.01 の type 属性定義を参照してください。 |
| [UseMap](../../aspose.html/htmlobjectelement/usemap/) { get; set; } | クライアント側のイメージ マップを使用します。 HTML 4.01. の usemap 属性の定義を参照してください。 |
| [Vspace](../../aspose.html/htmlobjectelement/vspace/) { get; set; } | このイメージ、アプレット、またはオブジェクトの上下の垂直スペース (ピクセル単位)。 HTML 4.01 の vspace 属性の定義を参照してください。この属性は、HTML 4.01. で廃止されました。 |
| [Width](../../aspose.html/htmlobjectelement/width/) { get; set; } | 幅をオーバーライドします。 HTML 4.01. の width 属性の定義を参照してください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | ノード newChild をこのノードの子のリストの最後に追加します。 newChild がすでにツリーにある場合は、最初に削除されます. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | シャドウ ルートを作成し、現在の要素にアタッチします。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | このメソッドにより、イベントを実装イベント モデルにディスパッチできます。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | アンマネージ リソースの解放、解放、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | 名前で属性値を取得します。 |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | 名前で属性ノードを取得します。 |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | ローカル名と名前空間 URI で Attr ノードを取得します。 |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | ローカル名と名前空間 URI によって属性値を取得します。 |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | 引数で指定されたすべてのクラスを持つドキュメント内のすべての要素を含むライブ NodeList オブジェクトを返します。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | 指定されたタグ名を持つすべての子孫要素の NodeList をドキュメント順に返します。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | 指定されたローカル名と名前空間 URI を持つすべての子孫要素の NodeList をドキュメント順に返します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [HasAttribute](../../aspose.html.dom/element/hasattribute/)(string) | 指定された名前の属性がこの要素で指定されている場合、またはデフォルト値がある場合は true、それ以外の場合は false を返します。 |
| [HasAttributeNS](../../aspose.html.dom/element/hasattributens/)(string, string) | 特定のローカル名と名前空間 URI を持つ属性がこの要素で指定されている場合、またはデフォルト値がある場合は true、それ以外の場合は false を返します。 |
| override [HasAttributes](../../aspose.html.dom/element/hasattributes/)() | このノード (エレメントの場合) が属性を持つかどうかを返します |
| [HasChildNodes](../../aspose.html.dom/node/haschildnodes/)() | このノードに子があるかどうかを返します. |
| [InsertBefore](../../aspose.html.dom/node/insertbefore/)(Node, Node) | 既存の子ノード child の前にノードを挿入します。 child が null の場合、child のリストの最後に node を挿入します。 child が DocumentFragment オブジェクトの場合、すべての子が同じ順序で child の前に挿入されます。子がすでにツリーにある場合は、最初に削除されます. |
| [IsDefaultNamespace](../../aspose.html.dom/node/isdefaultnamespace/)(string) | このメソッドは、指定された namespaceURI がデフォルトの名前空間であるかどうかをチェックします。 |
| [IsEqualNode](../../aspose.html.dom/node/isequalnode/)(Node) | 2 つのノードが等しいかどうかをテストします。 このメソッドは、Node.isSameNode() でテストできる同一性 (つまり、2 つのノードが同じオブジェクトへの参照であるかどうか) ではなく、ノードの等しいかどうかをテストします。逆は真ではないかもしれませんが、同じであるすべてのノードも等しくなります. |
| [IsSameNode](../../aspose.html.dom/node/issamenode/)(Node) | このノードが指定されたノードと同じかどうかを返します。 このメソッドは、実装によって返された 2 つの Node 参照が同じオブジェクトを参照しているかどうかを判断する方法を提供します。 2 つの Node 参照が同じオブジェクトへの参照である場合、たとえプロキシ経由であっても、すべての属性が同じ値を持ち、いずれかの参照で同じ DOM メソッドを呼び出すと、常にまったく同じ効果が得られるように、参照を完全に交換可能に使用できます. |
| [LookupNamespaceURI](../../aspose.html.dom/node/lookupnamespaceuri/)(string) | このノードから開始して、指定されたプレフィックスに関連付けられた名前空間 URI を検索します。 |
| [LookupPrefix](../../aspose.html.dom/node/lookupprefix/)(string) | このノードから開始して、指定された名前空間 URI に関連付けられたプレフィックスを検索します。デフォルトの名前空間宣言は、このメソッドによって無視されます。 このメソッドで使用されるアルゴリズムの詳細については、ネームスペース プレフィックス ルックアップを参照してください。 |
| [Normalize](../../aspose.html.dom/node/normalize/)() | 属性ノードを含む、このノードの下のサブツリーの深さ全体にあるすべてのテキスト ノードを、構造 (要素、コメント、処理命令、CDATA セクション、およびエンティティ参照など) のみがテキストを分離する「通常の」形式にします。つまり、隣接する Text ノードも空の Text ノードもありません。これは、ドキュメントの DOM ビューが、保存されて再ロードされた場合と同じであることを保証するために使用でき、特定のドキュメント ツリー構造に依存する操作 (XPointer [XPointer] ルックアップなど) が必要な場合に役立ちます。利用される。 Node.ownerDocument に添付された DOMConfiguration オブジェクトのパラメーター「normalize-characters」が true の場合、このメソッドは Text ノードの文字も完全に正規化します。 |
| [QuerySelector](../../aspose.html.dom/element/queryselector/)(string) | セレクター に一致する、ドキュメント内の最初の要素を返します |
| [QuerySelectorAll](../../aspose.html.dom/element/queryselectorall/)(string) | ドキュメント内のすべての要素の NodeList を返します。これは、selector に一致します。 |
| [Remove](../../aspose.html.dom/element/remove/)() | このインスタンスを削除します。 |
| [RemoveAttribute](../../aspose.html.dom/element/removeattribute/)(string) | 名前で属性を削除します。 |
| [RemoveAttributeNode](../../aspose.html.dom/element/removeattributenode/)(Attr) | 指定した属性ノードを削除します。 |
| [RemoveAttributeNS](../../aspose.html.dom/element/removeattributens/)(string, string) | ローカル名と名前空間 URI によって属性を削除します。 |
| [RemoveChild](../../aspose.html.dom/node/removechild/)(Node) | oldChild で示される子ノードを子のリストから削除し、それを返します。 |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)から削除されます[`EventTarget`](../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, DOMEventHandler, bool) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)から削除されます[`EventTarget`](../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットからイベント リスナーを削除できます。[`IEventListener`](../../aspose.html.dom.events/ieventlistener/)から削除されます[`EventTarget`](../../aspose.html.dom/eventtarget/)イベントの処理中は、現在のアクションによってトリガーされません. イベントリスナーは、削除された後は呼び出されません. |
| [ReplaceChild](../../aspose.html.dom/node/replacechild/)(Node, Node) | 子のリストで子ノード oldChild を newChild に置き換え、oldChild ノードを返します。 newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子に置き換えられ、同じ順序で挿入されます。 newChild がすでにツリーにある場合は、最初に削除されます. |
| [SetAttribute](../../aspose.html.dom/element/setattribute/)(string, string) | 新しい属性を追加します。その名前の属性が要素にすでに存在する場合、その値は値 parameter の値に変更されます。 |
| [SetAttributeNode](../../aspose.html.dom/element/setattributenode/)(Attr) | 新しい属性ノードを追加します。その名前 (nodeName) を持つ属性が要素に既に存在する場合、新しい属性に置き換えられます。 |
| [SetAttributeNodeNS](../../aspose.html.dom/element/setattributenodens/)(Attr) | 新しい属性を追加します。そのローカル名とその名前空間 URI を持つ属性が要素に既に存在する場合、それは新しいものに置き換えられます. |
| [SetAttributeNS](../../aspose.html.dom/element/setattributens/)(string, string, string) | 新しい属性を追加します。同じローカル名と名前空間 URI を持つ属性が要素に既に存在する場合、そのプレフィックスは修飾された名前のプレフィックス部分に変更され、その値は値パラメーターに変更されます. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| override [ToString](../../aspose.html.dom/node/tostring/)() | を返しますStringこのインスタンスを表す. |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [OnAbort](../../aspose.html/htmlelement/onabort/) | OnAbort イベントのイベント ハンドラーを取得または設定します。 |
| event [OnBlur](../../aspose.html/htmlelement/onblur/) | OnBlur イベントのイベント ハンドラーを取得または設定します。 |
| event [OnCancel](../../aspose.html/htmlelement/oncancel/) | OnCancel イベントのイベント ハンドラーを取得または設定します。 |
| event [OnCanplay](../../aspose.html/htmlelement/oncanplay/) | OnCanplay イベントのイベント ハンドラーを取得または設定します。 |
| event [OnCanPlayThrough](../../aspose.html/htmlelement/oncanplaythrough/) | OnCanPlayThrough イベントのイベント ハンドラーを取得または設定します。 |
| event [OnChange](../../aspose.html/htmlelement/onchange/) | OnChange イベントのイベント ハンドラーを取得または設定します。 |
| event [OnClick](../../aspose.html/htmlelement/onclick/) | OnClick イベントのイベント ハンドラーを取得または設定します。 |
| event [OnCueChange](../../aspose.html/htmlelement/oncuechange/) | OnCueChange イベントのイベント ハンドラーを取得または設定します。 |
| event [OnDblClick](../../aspose.html/htmlelement/ondblclick/) | OnDblClick イベントのイベント ハンドラーを取得または設定します。 |
| event [OnDurationChange](../../aspose.html/htmlelement/ondurationchange/) | OnDurationChange イベントのイベント ハンドラーを取得または設定します。 |
| event [OnEmptied](../../aspose.html/htmlelement/onemptied/) | OnEmptied イベントのイベント ハンドラーを取得または設定します。 |
| event [OnEnded](../../aspose.html/htmlelement/onended/) | OnEnded イベントのイベント ハンドラーを取得または設定します。 |
| event [OnError](../../aspose.html/htmlelement/onerror/) | OnError イベントのイベント ハンドラーを取得または設定します。 |
| event [OnFocus](../../aspose.html/htmlelement/onfocus/) | OnFocus イベントのイベント ハンドラーを取得または設定します。 |
| event [OnInput](../../aspose.html/htmlelement/oninput/) | OnInput イベントのイベント ハンドラーを取得または設定します。 |
| event [OnInvalid](../../aspose.html/htmlelement/oninvalid/) | OnInvalid イベントのイベント ハンドラーを取得または設定します。 |
| event [OnKeyDown](../../aspose.html/htmlelement/onkeydown/) | OnKeyDown イベントのイベント ハンドラーを取得または設定します。 |
| event [OnKeyPress](../../aspose.html/htmlelement/onkeypress/) | OnKeyPress イベントのイベント ハンドラーを取得または設定します。 |
| event [OnKeyUp](../../aspose.html/htmlelement/onkeyup/) | OnKeyUp イベントのイベント ハンドラーを取得または設定します。 |
| event [OnLoad](../../aspose.html/htmlelement/onload/) | OnLoad イベントのイベント ハンドラーを取得または設定します。 |
| event [OnLoadedData](../../aspose.html/htmlelement/onloadeddata/) | OnLoadedData イベントのイベント ハンドラーを取得または設定します。 |
| event [OnLoadedMetadata](../../aspose.html/htmlelement/onloadedmetadata/) | OnLoadedMetadata イベントのイベント ハンドラーを取得または設定します。 |
| event [OnLoadStart](../../aspose.html/htmlelement/onloadstart/) | OnLoadStart イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseDown](../../aspose.html/htmlelement/onmousedown/) | OnMouseDown イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseEnter](../../aspose.html/htmlelement/onmouseenter/) | OnMouseEnter イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseLeave](../../aspose.html/htmlelement/onmouseleave/) | OnMouseLeave イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseMove](../../aspose.html/htmlelement/onmousemove/) | OnMouseMove イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseOut](../../aspose.html/htmlelement/onmouseout/) | OnMouseOut イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseOver](../../aspose.html/htmlelement/onmouseover/) | OnMouseOver イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseUp](../../aspose.html/htmlelement/onmouseup/) | OnMouseUp イベントのイベント ハンドラーを取得または設定します。 |
| event [OnMouseWheel](../../aspose.html/htmlelement/onmousewheel/) | OnMouseWheel イベントのイベント ハンドラーを取得または設定します。 |
| event [OnPause](../../aspose.html/htmlelement/onpause/) | OnPause イベントのイベント ハンドラーを取得または設定します。 |
| event [OnPlay](../../aspose.html/htmlelement/onplay/) | OnPlay イベントのイベント ハンドラーを取得または設定します。 |
| event [OnPlaying](../../aspose.html/htmlelement/onplaying/) | OnPlaying イベントのイベント ハンドラーを取得または設定します。 |
| event [OnProgress](../../aspose.html/htmlelement/onprogress/) | OnProgress イベントのイベント ハンドラーを取得または設定します。 |
| event [OnRateChange](../../aspose.html/htmlelement/onratechange/) | OnRateChange イベントのイベント ハンドラーを取得または設定します。 |
| event [OnReset](../../aspose.html/htmlelement/onreset/) | OnReset イベントのイベント ハンドラーを取得または設定します。 |
| event [OnResize](../../aspose.html/htmlelement/onresize/) | OnResize イベントのイベント ハンドラーを取得または設定します。 |
| event [OnScroll](../../aspose.html/htmlelement/onscroll/) | OnScroll イベントのイベント ハンドラーを取得または設定します。 |
| event [OnSeeked](../../aspose.html/htmlelement/onseeked/) | OnSeeked イベントのイベント ハンドラーを取得または設定します。 |
| event [OnSeeking](../../aspose.html/htmlelement/onseeking/) | OnSeeking イベントのイベント ハンドラーを取得または設定します。 |
| event [OnSelect](../../aspose.html/htmlelement/onselect/) | OnSelect イベントのイベント ハンドラーを取得または設定します。 |
| event [OnShow](../../aspose.html/htmlelement/onshow/) | OnShow イベントのイベント ハンドラーを取得または設定します。 |
| event [OnStalled](../../aspose.html/htmlelement/onstalled/) | OnStalled イベントのイベント ハンドラーを取得または設定します。 |
| event [OnSubmit](../../aspose.html/htmlelement/onsubmit/) | OnSubmit イベントのイベント ハンドラーを取得または設定します。 |
| event [OnSuspend](../../aspose.html/htmlelement/onsuspend/) | OnSuspend イベントのイベント ハンドラーを取得または設定します。 |
| event [OnTimeUpdate](../../aspose.html/htmlelement/ontimeupdate/) | OnTimeUpdate イベントのイベント ハンドラーを取得または設定します。 |
| event [OnToggle](../../aspose.html/htmlelement/ontoggle/) | OnToggle イベントのイベント ハンドラーを取得または設定します。 |
| event [OnVolumeChange](../../aspose.html/htmlelement/onvolumechange/) | OnVolumeChange イベントのイベント ハンドラーを取得または設定します。 |
| event [OnWaiting](../../aspose.html/htmlelement/onwaiting/) | OnWaiting イベントのイベント ハンドラーを取得または設定します。 |

### 関連項目

* class [HTMLElement](../htmlelement/)
* 名前空間 [Aspose.Html](../../aspose.html/)
* 組み立て [Aspose.HTML](../../)


