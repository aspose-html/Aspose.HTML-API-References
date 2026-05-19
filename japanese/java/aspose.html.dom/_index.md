---
title: "com.aspose.html.dom"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom Document Object Model パッケージは、任意の HTML、XML、または SVG ドキュメントを表現し操作するための API を提供します。DOM はブラウザーに読み込まれるドキュメントモデルで、ドキュメントをノードツリーとして表現し、各ノードは要素、テキスト、文字列、コメントなどドキュメントの一部を表します。"
type: docs

url: /ja/java/com.aspose.html.dom/
---
The **com.aspose.html.dom (Document Object Model)** パッケージは、任意の HTML、XML、SVG ドキュメントを表現し、操作する API を提供します。DOM はブラウザで読み込まれるドキュメントモデルで、ドキュメントをノードツリーとして表現し、各ノードはドキュメントの一部（例：要素、テキスト文字列、コメント）を表します。

## クラス

| クラス | 説明 |
| --- | --- |
| [Attr](./attr/) | Attr インターフェイスは Element オブジェクト内の属性を表します。通常、属性の許容値はドキュメントに関連付けられたスキーマで定義されます。 |
| [CDATASection](./cdatasection/) | CDATA セクションは、マークアップと見なされる文字を含むテキストブロックをエスケープするために使用されます。 |
| [CharacterData](./characterdata/) | CharacterData は Node を拡張し、DOM 内の文字データにアクセスするための属性とメソッドのセットを提供します。 |
| [Comment](./comment/) | CharacterData を継承し、コメントの内容、すなわち開始 '' と終了 '' の間のすべての文字を表します。 |
| [Document](./document/) | Document は HTML、XML、または SVG ドキュメント全体を表します。概念的にはドキュメントツリーのルートであり、ドキュメントデータへの主要なアクセス手段を提供します。 |
| [DocumentFragment](./documentfragment/) | DocumentFragment は「軽量」または「最小」な Document オブジェクトです。ドキュメントのツリーの一部を抽出したり、新しいフラグメントを作成したりしたいケースは非常に一般的です。 |
| [DocumentType](./documenttype/) | DocumentType は、ドキュメントに定義されたエンティティのリストへのインターフェイスを提供します。 |
| [DOMException](./domexception/) | DOMException インターフェイスは、Web API のメソッド呼び出しやプロパティアクセスの結果として発生する異常事象（例外と呼ばれる）を表します。これは、Web API におけるエラー状態の記述方法そのものです。 |
| [DOMObject](./domobject/) | DOMObject 型は、Document Object Model 全体の基底オブジェクトを表すために使用されます。Java および ECMAScript では、DOMObject は Object 型にバインドされています。 |
| [Element](./element/) | Element インターフェイスは、HTML または XML ドキュメント内の要素を表します。 |
| [Entity](./entity/) | XML ドキュメント内の、解析済みまたは未解析の既知のエンティティを表します。 |
| [EntityReference](./entityreference/) | EntityReference ノードは、ツリー内のエンティティ参照を表すために使用できます。 |
| [EventTarget](./eventtarget/) | EventTarget インターフェイスは、イベントを受け取ることができ、リスナーを持つ可能性のあるオブジェクトによって実装されます。言い換えれば、イベントの対象となるすべてのオブジェクトは、このインターフェイスに関連付けられた 3 つのメソッドを実装します。 |
| [Node](./node/) | Node インターフェイスは、ドキュメントオブジェクトモデル全体の主要なデータ型です。ドキュメントツリー内の単一ノードを表します。Node インターフェイスを実装するすべてのオブジェクトは子ノードを扱うメソッドを公開しますが、すべてのオブジェクトが子ノードを持つわけではありません。例えば、[`Text`](../com.aspose.html.dom/text/) ノードは子ノードを持たない場合があり、そのようなノードに子ノードを追加しようとすると、[`DOMException`](../com.aspose.html.dom/domexception/) が発生します。 |
| [Notation](./notation/) | DTD で宣言された表記（notation）を表します。 |
| [ProcessingInstruction](./processinginstruction/) | ProcessingInstruction は「処理指示」を表し、XML でドキュメントのテキスト内にプロセッサ固有の情報を保持するために使用されます。 |
| [QualifiedName](./qualifiedname/) | HTML の修飾名を表します。 |
| [ShadowRoot](./shadowroot/) | ShadowRoot はシャドウツリーのルートノードです。 |
| [Text](./text/) | Text インターフェイスは CharacterData から継承し、Element または Attr のテキストコンテンツ（XML では文字データと呼ばれる）を表します。 |
| [TypeInfo](./typeinfo/) | TypeInfo は、ドキュメントに関連付けられたスキーマで指定された、Element または Attr ノードから参照される型を表します。 |
## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IBrowsingContext](./ibrowsingcontext/) | ブラウジングコンテキストは、[`Document`](../com.aspose.html.dom/document/) オブジェクトがユーザーに提示される環境です。 |
| [IChildNode](./ichildnode/) | `[`IChildNode`](../com.aspose.html.dom/ichildnode/)` インターフェイスを定義し、親を持つことができる [`Node`](../com.aspose.html.dom/node/) に実装すべきです。 |
| [IDOMImplementation](./idomimplementation/) | DOMImplementation インターフェイスは、特定のドキュメントオブジェクトモデルのインスタンスに依存しない操作を実行するための多数のメソッドを提供します。 |
| [IGlobalEventHandlers](./iglobaleventhandlers/) | システムイベントハンドリングをサポートするすべての要素が継承しなければならないインターフェイスを表します。 |
| [INonDocumentTypeChildNode](./inondocumenttypechildnode/) | `[`IChildNode`](../com.aspose.html.dom/ichildnode/)` を定義し、[`DOCUMENT_TYPE_NODE`](../com.aspose.html.dom/node/document_type_node/) ではないものです。 |
| [INonElementParentNode](./inonelementparentnode/) | `[`IParentNode`](../com.aspose.html.dom/iparentnode/)` を定義し、Element 型ではないものです。 |
| [IParentNode](./iparentnode/) | `[`IParentNode`](../com.aspose.html.dom/iparentnode/)` インターフェイスを定義し、あらゆる可能な親によって実装されます。 |
| [IStorage](./istorage/) | Web Storage API のこのインターフェイスは、特定ドメインのセッションまたはローカルストレージへのアクセスを提供します。Web Storage 仕様をご覧ください: [https://html.spec.whatwg.org/multipage/webstorage.html#webstorage](https://html.spec.whatwg.org/multipage/webstorage.html#webstorage) |
## 列挙型

| 列挙型 | 説明 |
| --- | --- |
| [ShadowRootMode](./shadowrootmode/) | ShadowRoot が動作できるモードです。 |
