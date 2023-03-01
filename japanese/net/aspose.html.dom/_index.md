---
title: Aspose.Html.Dom
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom ドキュメント オブジェクト モデル名前空間は が HTMLXMLまたは SVG ドキュメントを表しそれらと対話する API を提供します DOM はブラウザーにロードされたドキュメント モデルであり はドキュメントをノード ツリーとして表しますここで各 node はドキュメントの一部 要素テキストなど を表します文字列またはコメント.
type: docs
weight: 40
url: /ja/net/aspose.html.dom/
---
**Aspose.Html.Dom (ドキュメント オブジェクト モデル)**名前空間は、 が HTML、XML、または SVG ドキュメントを表し、それらと対話する API を提供します。 DOM は、ブラウザーにロードされたドキュメント モデルであり、 はドキュメントをノード ツリーとして表します。ここで、各 node はドキュメントの一部 (要素、テキストなど) を表します。文字列、またはコメント).

## クラス

| クラス | 説明 |
| --- | --- |
| [Attr](./attr/) | Attr インターフェイスは、Element オブジェクトの属性を表します。通常、属性の許容値は、ドキュメントに関連付けられたスキーマで定義されます. |
| [CDATASection](./cdatasection/) | CDATA セクションは、マークアップと見なされる文字を含むテキストのブロックをエスケープするために使用されます。 |
| [CharacterData](./characterdata/) | CharacterData は、DOM 内の文字データにアクセスするための一連の属性とメソッドで Node を拡張します。 |
| [Comment](./comment/) | CharacterData から継承し、コメントの内容を表します。つまり、先頭の '. |
| [Document](./document/) | ドキュメントは、HTML、XML、または SVG ドキュメント全体を表します。概念的には、ドキュメント ツリーのルートであり、ドキュメントのデータへのプライマリ アクセスを提供します。 |
| [DocumentFragment](./documentfragment/) | DocumentFragment は、「軽量」または「最小限」の Document オブジェクトです。ドキュメントのツリーの一部を抽出したり、ドキュメントの新しいフラグメントを作成したりしたいことは非常に一般的です. |
| [DocumentType](./documenttype/) | DocumentType は、document に対して定義されているエンティティのリストへのインターフェイスを提供します。 |
| [DOMException](./domexception/) | DOMException インターフェイスは、Web API のメソッドの呼び出しまたはプロパティへのアクセスの結果として発生する異常なイベント (例外と呼ばれます) を表します。これは基本的に、Web API でエラー状態を記述する方法です。 |
| [DOMObject](./domobject/) | DOMObject タイプは、Document Object Model 全体のベース オブジェクトを表すために使用されます。 Java および ECMAScript の場合、DOMObject は Object タイプにバインドされます。 |
| [Element](./element/) | Element インターフェイスは、HTML または XML ドキュメント内の要素を表します。 |
| [Entity](./entity/) | XML ドキュメント内の既知のエンティティ (解析済みまたは未解析) を表します。 |
| [EntityReference](./entityreference/) | EntityReference ノードを使用して、ツリー内のエンティティ参照を表すことができます。 |
| [EventTarget](./eventtarget/) | [`EventTarget`](../aspose.html.dom/eventtarget/)インターフェイスは、DOM イベント モデルをサポートする実装ですべてのノードによって実装されます。 したがって、このインターフェイスは、Node インターフェイスのインスタンスでバインディング固有のキャスト メソッドを使用して取得できます。 インターフェイスにより、イベント リスナーの登録と削除が可能になります。を[`EventTarget`](../aspose.html.dom/eventtarget/)それにイベントをディスパッチする[`IEventTarget`](../aspose.html.dom.events/ieventtarget/). |
| [Node](./node/) | Node インターフェイスは、Document オブジェクト モデル全体の主要なデータ型です。ドキュメント ツリー内の単一のノードを表します。 |
| [Notation](./notation/) | DTD で宣言されている表記を表します。 |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction は「処理命令」を表し、ドキュメントのテキストにプロセッサ固有の情報を保持する方法として XML で使用されます。 |
| [ShadowRoot](./shadowroot/) | ShadowRoot は、シャドウ ツリーのルート ノードです。 |
| [Text](./text/) | Text インターフェイスは CharacterData から継承し、Element または Attr. のテキスト コンテンツ (XML では文字データと呼ばれる) を表します。 |
| [TypeInfo](./typeinfo/) | TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。 |
## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | ブラウジング コンテキストとは、[`Document`](../aspose.html.dom/document/)オブジェクトがユーザーに表示されます. |
| [IChildNode](./ichildnode/) | 定義[`IChildNode`](../aspose.html.dom/ichildnode/)によって実装されるべきインターフェース[`Node`](../aspose.html.dom/node/)親を持つことができます. |
| [IDocumentInit](./idocumentinit/) | このインターフェースが提供するもの[`Document`](../aspose.html.dom/document/)初期化情報. |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation インターフェイスは、ドキュメント オブジェクト モデルの特定のインスタンスに依存しない操作を実行するための多数のメソッドを提供します。 |
| [IElementInit](./ielementinit/) | このインターフェースが提供するもの[`Element`](../aspose.html.dom/element/)初期化情報. |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | システム イベント処理がサポートされているすべての要素によって継承される必要があるインターフェイスを表します |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | 定義[`IChildNode`](../aspose.html.dom/ichildnode/)そうではない[`DOCUMENT_TYPE_NODE`](../aspose.html.dom/node/document_type_node/). |
| [INonElementParentNode](./inonelementparentnode/) | 定義[`IParentNode`](../aspose.html.dom/iparentnode/) Element type. ではないもの |
| [IParentNode](./iparentnode/) | は[`IParentNode`](../aspose.html.dom/iparentnode/)可能な親によって実装されるインターフェイス. |
## 列挙

| 列挙 | 説明 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot が動作できるモード. |


