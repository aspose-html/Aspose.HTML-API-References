---
title: "NodeFilter クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.filters.NodeFilter クラス。フィルタはノードを除外する方法を知っているオブジェクトです"
type: docs

url: /ja/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

フィルタはノードを "除外" する方法を知っているオブジェクトです。

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | 指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出されますが、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。） |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | このメソッドは ECMAScript オブジェクトの Type を取得するために使用されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | ノードを受け入れる。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返します。 |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | ノードを拒否する。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返しません。TreeWalker の場合、このノードの子ノードも拒否されます。NodeIterators はこれを FILTER_SKIP の同義語として扱います。 |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | この単一ノードをスキップする。NodeIterator または TreeWalker 用に定義されたナビゲーションメソッドはこのノードを返しません。NodeIterator と TreeWalker の両方で、このノードの子ノードは引き続き考慮されます。 |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | すべてのノードを表示する。 |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | 属性ノードを表示する。これは属性ノードをルートとするイテレータまたはツリーワーカーを作成する場合にのみ意味があります。この場合、属性ノードがイテレーションまたはトラバーサルの最初の位置に表示されます。属性は他のノードの子になることがないため、ドキュメントツリーを走査するときに表示されません。 |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | CDATASection ノードを表示する。 |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | コメントノードを表示する。 |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Document ノードを表示する。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | DocumentFragment ノードを表示する。 |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | DocumentType ノードを表示する。 |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Element ノードを表示する。 |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Entity ノードを表示する。これは Entity ノードをルートとするイテレータまたはツリーワーカーを作成する場合にのみ意味があります。この場合、Entity ノードがトラバーサルの最初の位置に表示されます。Entity はドキュメントツリーの一部ではないため、ドキュメントツリーを走査するときに表示されません。 |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | EntityReference ノードを表示します。 |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Notation ノードを表示します。これは、Notation ノードをルートとするイテレータまたはツリーワーカーを作成する場合にのみ意味があります。その場合、Traversal の最初の位置に Notation ノードが現れます。Notation は文書ツリーの一部ではないため、文書ツリーを走査しても表示されません。 |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | ProcessingInstruction ノードを表示します。 |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Text ノードを表示します。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
