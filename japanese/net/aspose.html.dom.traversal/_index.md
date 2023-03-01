---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal名前空間には 要素間を移動するためのイテレータとツリー ウォーカーを作成し ノードとその子をドキュメント順にトラバースするメソッドが含まれています.
type: docs
weight: 170
url: /ja/net/aspose.html.dom.traversal/
---
**Aspose.Html.Dom.Traversal**名前空間には、 要素間を移動するためのイテレータとツリー ウォーカーを作成し、 ノードとその子をドキュメント順にトラバースするメソッドが含まれています.

## インターフェース

| インターフェース | 説明 |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal には、イテレータと ツリー ウォーカーを作成して、ノードとその子をドキュメントの順序でトラバースするメソッドが含まれています (深さ が最初、プレオーダー トラバーサル。ドキュメント）。 Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装する同じオブジェクトによって 実装されます. |
| [IElementTraversal](./ielementtraversal/) | ElementTraversal インターフェイスは、作成者がドキュメント内の要素間を簡単にナビゲートできるようにする読み取り専用属性のセットです。 Element Traversal の適合する実装では、Element を実装するすべてのオブジェクトは ElementTraversal インターフェイスも実装する必要があります。 |
| [INodeFilter](./inodefilter/) | フィルターは、ノードを「フィルターで除外」する方法を知っているオブジェクトです。 NodeIterator または TreeWalker に NodeFilter が指定されている場合、次の ノードを返す前にフィルターを適用します。フィルターがノードを受け入れるように指示する場合、トラバーサル ロジックは it を返します。それ以外の場合、トラバーサルは次のノードを探し、拒否された ノードが存在しないふりをします. |
| [INodeIterator](./inodeiterator/) | イテレータは、NodeList 内のノードの セット、特定のノードの によって管理されるドキュメント サブツリー、クエリの結果、またはその他のノードの セットなど、一連のノードをステップスルーするために使用されます。反復されるノードのセットは、NodeIterator の 実装によって決定されます。 DOM レベル 2 は、ドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定します。これらの反復子のインスタンスは、DocumentTraversal .createNodeIterator(). を呼び出すことによって 作成されます。 |
| [ITraversal](./itraversal/) | イテレータは、NodeList 内のノードの セット、特定のノードの によって管理されるドキュメント サブツリー、クエリの結果、またはその他のノードの セットなど、一連のノードをステップスルーするために使用されます。反復されるノードのセットは、NodeIterator の 実装によって決定されます。 DOM レベル 2 は、ドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定します。これらの反復子のインスタンスは、DocumentTraversal .createNodeIterator(). を呼び出すことによって 作成されます。 |
| [ITreeWalker](./itreewalker/) | TreeWalker オブジェクトは、 whatToShow フラグとフィルター (存在する場合) によって定義されたドキュメントのビューを使用して、ドキュメント ツリーまたは サブツリーをナビゲートするために使用されます。 が TreeWalker を使用してナビゲーションを実行する関数は、自動的に TreeWalker. によって定義されたビューをサポートします。 |


