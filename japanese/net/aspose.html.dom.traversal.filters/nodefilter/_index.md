---
title: Class NodeFilter
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter クラス. フィルターはノードをフィルターで除外する方法を知っているオブジェクトです
type: docs
weight: 2460
url: /ja/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

フィルターは、ノードを「フィルターで除外」する方法を知っているオブジェクトです。

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | 指定されたノードが a TreeWalker または NodeIterator の論理ビューに表示されるかどうかをテストします。この function は、TreeWalker および NodeIterator の実装によって呼び出されます。通常、 ユーザー コードから直接呼び出されることはありません。 (ただし、same フィルターを使用して独自のアプリケーション ロジックをガイドする場合は、そうすることができます。) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | ノードを受け入れます。 NodeIterator または TreeWalker に定義されたナビゲーション メソッドは、この node. を返します。 |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | ノードを拒否します。 NodeIterator または TreeWalker に定義されたナビゲーション メソッドは、 このノードを返しません。 TreeWalker の場合、このノード の子も拒否されます。 NodeIterators は、これを FILTER_SKIP. の シノニムとして扱います。 |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | この単一ノードをスキップします。 NodeIterator または TreeWalker に定義されたナビゲーション メソッドは、 このノードを返しません。 NodeIterator と TreeWalker の両方で、このノードの子は引き続き と見なされます。 |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | すべてのノードを表示します。 |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Attr ノードを表示します。これは、 ルートとして属性ノードを持つ イテレーターまたはツリー ウォーカーを作成する場合にのみ意味があります。この場合、属性ノード が反復またはトラバーサルの最初の位置に表示されることを意味します。 属性は決して他のノードの子ではないため、ドキュメント ツリーをトラバースしても 表示されません. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection ノードを表示します。 |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | コメント ノードを表示します。 |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | ドキュメント ノードを表示します。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment ノードを表示します。 |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType ノードを表示します。 |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | 要素ノードを表示します。 |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | エンティティ ノードを表示します。これは、 ルートとしてエンティティ ノードを使用して イテレータまたはツリー ウォーカーを作成する場合にのみ意味があります。この場合、Entity ノードがトラバーサルの最初の位置に表示されることを意味します。 エンティティはドキュメント ツリーの一部ではないため、 がドキュメント ツリーをトラバースしても表示されません. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference ノードを表示します。 |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | 表記ノードを表示します。これは、Notation ノードを ルートとして持つイテレーターまたはツリー ウォーカーを 作成する場合にのみ意味があります。この場合、 Notation ノードが トラバーサルの最初の位置に表示されることを意味します。表記はドキュメント ツリーの一部ではないため、ドキュメント ツリーをトラバースしても 表示されません. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction ノードを表示します。 |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | テキスト ノードを表示します。 |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* 名前空間 [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* 組み立て [Aspose.HTML](../../)


