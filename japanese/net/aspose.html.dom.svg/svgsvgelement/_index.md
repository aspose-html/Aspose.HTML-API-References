---
title: Class SVGSVGElement
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Svg.SVGSVGElement クラス. 重要なインターフェイス定義は SVGSVGElement インターフェイスですこれはsvg要素に対応するインターフェイスですこのインターフェイスには行列演算やビジュアル レンダリング デバイスでの再描画時間を制御する機能など一般的に使用されるさまざまなユーティリティ メソッドが含まれています
type: docs
weight: 2260
url: /ja/net/aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

重要なインターフェイス定義は SVGSVGElement インターフェイスです。これは、「svg」要素に対応するインターフェイスです。このインターフェイスには、行列演算やビジュアル レンダリング デバイスでの再描画時間を制御する機能など、一般的に使用されるさまざまなユーティリティ メソッドが含まれています。

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [Attributes](../../aspose.html.dom/element/attributes/) { get; } | このノードの属性を含む NamedNodeMap (要素の場合)、またはそれ以外の場合は null. |
| virtual [BaseURI](../../aspose.html.dom/node/baseuri/) { get; } | このノードの絶対ベース URI、または実装が絶対 URI を取得できなかった場合は null。 |
| [ChildElementCount](../../aspose.html.dom/element/childelementcount/) { get; } | この要素の子である要素ノードの現在の数を返します。この要素に nodeType 1. の子ノードがない場合は 0 |
| [ChildNodes](../../aspose.html.dom/node/childnodes/) { get; } | このノードのすべての子を含む NodeList。子がない場合、これはノードを含まない NodeList です.. |
| [Children](../../aspose.html.dom/element/children/) { get; } | 現在の要素の子要素を返します. |
| [ClassList](../../aspose.html.dom/element/classlist/) { get; } | 「クラス」属性の解析から受け取ったトークンを含むライブ DOMTokenList を返します。 |
| [ClassName](../../aspose.html.dom.svg/svgelement/classname/) { get; } | 指定された要素の属性「クラス」に対応します。 |
| [ClassName](../../aspose.html.dom/element/classname/) { get; set; } | 要素のクラス属性。この属性は、多くの言語で公開されている「class」キーワードと競合するため、名前が due に変更されました。 HTML 4.01. のクラス属性定義を参照してください。 |
| [CurrentScale](../../aspose.html.dom.svg/svgsvgelement/currentscale/) { get; set; } | 最も外側の svg 要素では、この属性は、拡大とパンで説明されているように、ユーザーの拡大とパン操作を考慮して、初期ビューに対する現在の倍率を示します。 DOM 属性 currentScale および currentTranslate は、2x3 マトリックス [abcdef] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y] と同等です。 「拡大」が有効な場合 (つまり、zoomAndPan="magnify")、追加の変換が SVG ドキュメント フラグメントの最も外側のレベル (つまり、最も外側の SVG 要素の外側) に配置されたかのような効果があります。最も外側の svg 要素ではない 'svg' 要素。この属性の動作は定義されていません。 |
| [CurrentTranslate](../../aspose.html.dom.svg/svgsvgelement/currenttranslate/) { get; } | 最も外側の svg 要素では、ユーザーの「倍率」を考慮した対応する変換係数。 最も外側の svg 要素ではない「svg」要素でアクセスした場合、この属性がどのような動作をするかは未定義です。 |
| [FarthestViewportElement](../../aspose.html.dom.svg/svggraphicselement/farthestviewportelement/) { get; } | 最も遠い祖先の 'svg' 要素。現在の要素が最も外側の svg 要素である場合は null. |
| [FirstChild](../../aspose.html.dom/node/firstchild/) { get; } | このノードの最初の子。そのようなノードがない場合、これは null. を返します。 |
| [FirstElementChild](../../aspose.html.dom/element/firstelementchild/) { get; } | この要素の最初の子要素ノードを返します。この要素に子要素がない場合は null. |
| [Height](../../aspose.html.dom.svg/svgsvgelement/height/) { get; } | 指定された「svg」要素の属性「高さ」に対応します。 |
| [Id](../../aspose.html.dom.svg/svgelement/id/) { get; set; } | 指定された要素の 'id' 属性の値、または 'id' が存在しない場合は空の文字列. |
| [InnerHTML](../../aspose.html.dom/element/innerhtml/) { get; set; } | 要素のコンテンツを表す HTML または XML のフラグメントを返します。 設定して、要素のコンテンツを指定された文字列から解析されたノードに置き換えることができます。 |
| [LastChild](../../aspose.html.dom/node/lastchild/) { get; } | このノードの最後の子。そのようなノードがない場合、これは null. を返します。 |
| [LastElementChild](../../aspose.html.dom/element/lastelementchild/) { get; } | この要素の最後の子要素ノードを返します。この要素に子要素がない場合は null. |
| override [LocalName](../../aspose.html.dom/element/localname/) { get; } | このノードの修飾名のローカル部分を返します。 ELEMENT_NODE および ATTRIBUTE_NODE 以外のタイプのノード、および Document.createElement() などの DOM レベル 1 メソッドで作成されたノードの場合、これは常に null です。 |
| override [NamespaceURI](../../aspose.html.dom/element/namespaceuri/) { get; } | このノードの名前空間 URI、または指定されていない場合は null. |
| [NearestViewportElement](../../aspose.html.dom.svg/svggraphicselement/nearestviewportelement/) { get; } | 現在のビューポートを確立した要素。多くの場合、最も近い祖先の 'svg' 要素です。現在の要素が最も外側の svg 要素である場合は null. |
| [NextElementSibling](../../aspose.html.dom/element/nextelementsibling/) { get; } | この要素の次の兄弟要素ノードを返します。この要素に、ドキュメント ツリーでこの要素の後に続く要素兄弟ノードがない場合は null. |
| [NextSibling](../../aspose.html.dom/node/nextsibling/) { get; } | このノードの直後のノード。そのようなノードがない場合、これは null. を返します。 |
| override [NodeName](../../aspose.html.dom/element/nodename/) { get; } | タイプに応じたこのノードの名前. |
| override [NodeType](../../aspose.html.dom/element/nodetype/) { get; } | 基礎となるオブジェクトのタイプを表すコード. |
| virtual [NodeValue](../../aspose.html.dom/node/nodevalue/) { get; set; } | タイプに応じたこのノードの値. |
| [OuterHTML](../../aspose.html.dom/element/outerhtml/) { get; set; } | 要素とそのコンテンツを表す HTML または XML のフラグメントを返します。 設定して、指定された文字列から解析されたノードで要素を置き換えることができます。 |
| virtual [OwnerDocument](../../aspose.html.dom/node/ownerdocument/) { get; } | このノードに関連付けられたドキュメント オブジェクト。これは、新しいノードを作成するために使用される Document オブジェクトでもあります。このノードがドキュメントまたはドキュメントでまだ使用されていない DocumentType である場合、これは null. です。 |
| [OwnerSVGElement](../../aspose.html.dom.svg/svgelement/ownersvgelement/) { get; } | 最も近い先祖「svg」要素。指定された要素が最も外側の SVG 要素である場合は null. |
| [ParentElement](../../aspose.html.dom/node/parentelement/) { get; } | 親を取得します[`Element`](../../aspose.html.dom/element/)このノードの. |
| [ParentNode](../../aspose.html.dom/node/parentnode/) { get; } | このノードの親。 Attr、Document、DocumentFragment、Entity、および Notation を除くすべてのノードは、親を持つことができます。ただし、ノードが作成されたばかりでまだツリーに追加されていない場合、またはツリーから削除されている場合、これは null. です。 |
| override [Prefix](../../aspose.html.dom/element/prefix/) { get; } | このノードの名前空間プレフィックス、または指定されていない場合は null。 null と定義されている場合、設定しても効果はありません |
| [PreserveAspectRatio](../../aspose.html.dom.svg/svgsvgelement/preserveaspectratio/) { get; } | 指定された要素の属性「preserveAspectRatio」に対応します。 |
| [PreviousElementSibling](../../aspose.html.dom/element/previouselementsibling/) { get; } | この要素の前の兄弟要素ノードを返します。この要素に、ドキュメント ツリー内でこの要素の前にある要素の兄弟ノードがない場合は null. |
| [PreviousSibling](../../aspose.html.dom/node/previoussibling/) { get; } | このノードの直前のノード。そのようなノードがない場合、これは null. を返します。 |
| [RequiredExtensions](../../aspose.html.dom.svg/svggraphicselement/requiredextensions/) { get; } | 指定された要素の属性「requiredExtensions」に対応します。 |
| [RequiredFeatures](../../aspose.html.dom.svg/svggraphicselement/requiredfeatures/) { get; } | 指定された要素の属性「requiredFeatures」に対応します。 |
| [SchemaTypeInfo](../../aspose.html.dom/element/schematypeinfo/) { get; } | この要素に関連付けられた型情報。 |
| [ShadowRoot](../../aspose.html.dom/element/shadowroot/) { get; } | この要素に格納されている shadowRoot を返すか、閉じている場合は null を返します。 |
| [Style](../../aspose.html.dom.svg/svgelement/style/) { get; } | 指定された要素の属性「スタイル」に対応します。ユーザー エージェントが CSS によるスタイリングをサポートしていない場合、この属性は常に null. の値を持つ必要があります。 |
| [SystemLanguage](../../aspose.html.dom.svg/svggraphicselement/systemlanguage/) { get; } | 指定された要素の属性「systemLanguage」に対応します。 |
| [TagName](../../aspose.html.dom/element/tagname/) { get; } | 要素の名前。 |
| override [TextContent](../../aspose.html.dom/element/textcontent/) { get; set; } | この属性は、このノードとその子孫のテキスト コンテンツを返します。 null として定義されている場合、設定しても効果はありません。設定時に、このノードが持つ可能性のある子はすべて削除され、新しい文字列が空または null でない場合は、この属性が設定されている文字列を含む単一の Text ノードに置き換えられます。 |
| [Transform](../../aspose.html.dom.svg/svggraphicselement/transform/) { get; } | 指定された要素の属性「変換」に対応します。 |
| [ViewBox](../../aspose.html.dom.svg/svgsvgelement/viewbox/) { get; } | 指定された要素の属性「viewBox」に対応します。 |
| [ViewportElement](../../aspose.html.dom.svg/svgelement/viewportelement/) { get; } | 現在のビューポートを確立した要素。多くの場合、最も近い祖先の 'svg' 要素です。指定された要素が最も外側の SVG 要素である場合は null. |
| [Width](../../aspose.html.dom.svg/svgsvgelement/width/) { get; } | 指定された「svg」要素の属性「幅」に対応します。 |
| [X](../../aspose.html.dom.svg/svgsvgelement/x/) { get; } | 指定された「svg」要素の属性「x」に対応します。 |
| [Y](../../aspose.html.dom.svg/svgsvgelement/y/) { get; } | 指定された「svg」要素の属性「y」に対応します。 |
| [ZoomAndPan](../../aspose.html.dom.svg/svgsvgelement/zoomandpan/) { get; set; } | 指定された要素の属性「zoomAndPan」に対応します。値は、このインターフェイスで定義された SVG_ZOOMANDPAN_* 定数のいずれかでなければなりません. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, DOMEventHandler, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/)(string, IEventListener, bool) | このメソッドを使用すると、イベント ターゲットにイベント リスナーを登録できます。 |
| [AnimationsPaused](../../aspose.html.dom.svg/svgsvgelement/animationspaused/)() | この SVG ドキュメント フラグメントが一時停止状態にある場合は true を返します。 |
| [AppendChild](../../aspose.html.dom/node/appendchild/)(Node) | ノード newChild をこのノードの子のリストの最後に追加します。 newChild がすでにツリーにある場合は、最初に削除されます. |
| [AttachShadow](../../aspose.html.dom/element/attachshadow/)(ShadowRootMode) | シャドウ ルートを作成し、現在の要素にアタッチします。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)() | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [CloneNode](../../aspose.html.dom/node/clonenode/)(bool) | このノードの複製を返します。つまり、ノードの汎用コピー コンストラクタとして機能します。複製ノードには親がなく (parentNode が null)、ユーザー データもありません。 |
| [CreateEvent](../../aspose.html.dom.svg/svgsvgelement/createevent/)(string) | を作成します[`Event`](../../aspose.html.dom.events/event/)実装でサポートされているタイプの. |
| [CreateSVGAngle](../../aspose.html.dom.svg/svgsvgelement/createsvgangle/)() | ドキュメント ツリーの外側に SVGAngle オブジェクトを作成します。オブジェクトは値 0 度 (単位なし) に初期化されます。 |
| [CreateSVGLength](../../aspose.html.dom.svg/svgsvgelement/createsvglength/)() | ドキュメント ツリーの外部に SVGLength オブジェクトを作成します。オブジェクトは 0 ユーザー単位の値に初期化されます。 |
| [CreateSVGMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgmatrix/)() | ドキュメント ツリーの外部に SVGMatrix オブジェクトを作成します。オブジェクトは単位行列に初期化されます. |
| [CreateSVGNumber](../../aspose.html.dom.svg/svgsvgelement/createsvgnumber/)() | 文書ツリーの外側に SVGNumber オブジェクトを作成します。オブジェクトはゼロの値に初期化されます. |
| [CreateSVGPoint](../../aspose.html.dom.svg/svgsvgelement/createsvgpoint/)() | ドキュメント ツリーの外部に SVGPoint オブジェクトを作成します。オブジェクトは、ユーザー座標系の点 (0,0) に初期化されます. |
| [CreateSVGRect](../../aspose.html.dom.svg/svgsvgelement/createsvgrect/)() | ドキュメント ツリーの外部に SVGRect オブジェクトを作成します。オブジェクトは、すべての値が 0 ユーザー単位に設定されるように初期化されます。 |
| [CreateSVGTransform](../../aspose.html.dom.svg/svgsvgelement/createsvgtransform/)() | ドキュメント ツリーの外部に SVGTransform オブジェクトを作成します。オブジェクトは単位行列変換 (SVG_TRANSFORM_MATRIX). に初期化されます。 |
| [CreateSVGTransformFromMatrix](../../aspose.html.dom.svg/svgsvgelement/createsvgtransformfrommatrix/)(SVGMatrix) | ドキュメント ツリーの外部に SVGTransform オブジェクトを作成します。オブジェクトは、指定された行列変換 (つまり、SVG_TRANSFORM_MATRIX) に初期化されます。パラメーター マトリックスの値がコピーされ、マトリックス パラメーターは SVGTransform::matrix. として採用されません |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | このメソッドにより、イベントを実装イベント モデルにディスパッチできます。 |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | アンマネージ リソースの解放、解放、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [GetAttribute](../../aspose.html.dom/element/getattribute/)(string) | 名前で属性値を取得します。 |
| [GetAttributeNode](../../aspose.html.dom/element/getattributenode/)(string) | 名前で属性ノードを取得します。 |
| [GetAttributeNodeNS](../../aspose.html.dom/element/getattributenodens/)(string, string) | ローカル名と名前空間 URI で Attr ノードを取得します。 |
| [GetAttributeNS](../../aspose.html.dom/element/getattributens/)(string, string) | ローカル名と名前空間 URI によって属性値を取得します。 |
| [GetBBox](../../aspose.html.dom.svg/svggraphicselement/getbbox/)() | ストローク、クリッピング、マスキング、フィルター効果を除く、含まれるすべてのグラフィックス要素のジオメトリで、現在のユーザー空間 (つまり、「変換」属性があれば適用後) のタイトなバウンディング ボックスを返します。 getBBox は、要素がまだレンダリングされていない場合でも、メソッドが呼び出された時点で実際の境界ボックスを返さなければならないことに注意してください. |
| [GetCTM](../../aspose.html.dom.svg/svggraphicselement/getctm/)() | 現在のユーザー単位 (つまり、「transform」属性があれば適用後) から、nearestViewportElement のビューポート座標系への変換マトリックスを返します。 |
| [GetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/getcurrenttime/)() | 現在の SVG ドキュメント フラグメントの開始時刻を基準とした現在の時刻を秒単位で返します。ドキュメントのタイムラインが開始される前に getCurrentTime が呼び出された場合 (たとえば、ドキュメントの SVGLoad イベントが送出される前に 'script' 要素で実行されているスクリプトによって)、0 が返されます。 |
| [GetElementById](../../aspose.html.dom.svg/svgsvgelement/getelementbyid/)(string) | この SVG ドキュメント フラグメントを検索します (つまり、検索はドキュメント ツリーのサブセットに制限されます)。 Element が見つかった場合、その Element が返されます。そのような要素が存在しない場合は、null を返します。複数の要素がこの id. を持つ場合、動作は定義されません。 |
| [GetElementsByClassName](../../aspose.html.dom/element/getelementsbyclassname/)(string) | 引数で指定されたすべてのクラスを持つドキュメント内のすべての要素を含むライブ NodeList オブジェクトを返します。 http://www.w3.org/TR/dom/ |
| [GetElementsByTagName](../../aspose.html.dom/element/getelementsbytagname/)(string) | 指定されたタグ名を持つすべての子孫要素の NodeList をドキュメント順に返します。 |
| [GetElementsByTagNameNS](../../aspose.html.dom/element/getelementsbytagnamens/)(string, string) | 指定されたローカル名と名前空間 URI を持つすべての子孫要素の NodeList をドキュメント順に返します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [GetScreenCTM](../../aspose.html.dom.svg/svggraphicselement/getscreenctm/)() | 現在のユーザー単位 (つまり、「変換」属性があれば適用後) から親ユーザー エージェントの「ピクセル」通知までの変換行列を返します。ディスプレイ デバイスの場合、理想的には、これは物理的なスクリーン ピクセルを表します。物理的なピクセル サイズが不明な他のデバイスまたは環境では、代わりに CSS2 定義の「ピクセル」に類似したアルゴリズムを使用できます。この要素がドキュメント ツリーにフックされていない場合は、null が返されることに注意してください。このメソッドは、getClientCTM という名前の方が適切ですが、歴史的な理由から getScreenCTM という名前が残されています。 |
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
| [PauseAnimations](../../aspose.html.dom.svg/svgsvgelement/pauseanimations/)() | この 'svg' 要素に対応する SVG ドキュメント フラグメント内で定義されている、現在実行中のすべてのアニメーションを一時停止 (一時停止) し、このドキュメント フラグメントに対応するアニメーション クロックを、一時停止が解除されるまで静止させます。 |
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
| [SetCurrentTime](../../aspose.html.dom.svg/svgsvgelement/setcurrenttime/)(float) | この SVG ドキュメント フラグメントの時計を調整し、新しい現在時刻を確立します。ドキュメントのタイムラインが開始される前に setCurrentTime が呼び出された場合 (たとえば、ドキュメントの SVGLoad イベントが送出される前に 'script' 要素で実行されているスクリプトによって)、メソッドの最後の呼び出しでの秒の値は、ドキュメントがドキュメントのタイムラインが開始されると、シークします. |
| [SetIdAttribute](../../aspose.html.dom/element/setidattribute/)(string, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| [SetIdAttributeNode](../../aspose.html.dom/element/setidattributenode/)(Attr, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| [SetIdAttributeNS](../../aspose.html.dom/element/setidattributens/)(string, string, bool) | パラメータ isId が true の場合、このメソッドは、指定された属性がユーザー定義の ID 属性であることを宣言します。 |
| override [ToString](../../aspose.html.dom/node/tostring/)() | を返しますStringこのインスタンスを表す. |
| [UnpauseAnimations](../../aspose.html.dom.svg/svgsvgelement/unpauseanimations/)() | SVG ドキュメント フラグメント内で定義されている現在実行中のアニメーションの一時停止を解除 (つまり、一時停止解除) し、一時停止された時点からアニメーション クロックを継続させます。 |

### 関連項目

* class [SVGGraphicsElement](../svggraphicselement/)
* interface [ISVGFitToViewBox](../isvgfittoviewbox/)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent/)
* interface [IViewCSS](../../aspose.html.dom.css/iviewcss/)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss/)
* interface [ISVGZoomAndPan](../isvgzoomandpan/)
* 名前空間 [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg/)
* 組み立て [Aspose.HTML](../../)


