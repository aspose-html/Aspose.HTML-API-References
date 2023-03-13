---
title: Interface ITraversal
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal.ITraversal インターフェース. イテレータはNodeList 内のノードの セット特定のノードの によって管理されるドキュメント サブツリークエリの結果またはその他のノードの セットなど一連のノードをステップスルーするために使用されます反復されるノードのセットはNodeIterator の 実装によって決定されます DOM レベル 2 はドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定しますこれらの反復子のインスタンスはDocumentTraversal .createNodeIterator. を呼び出すことによって 作成されます
type: docs
weight: 2510
url: /ja/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

イテレータは、NodeList 内のノードの セット、特定のノードの によって管理されるドキュメント サブツリー、クエリの結果、またはその他のノードの セットなど、一連のノードをステップスルーするために使用されます。反復されるノードのセットは、NodeIterator の 実装によって決定されます。 DOM レベル 2 は、ドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定します。これらの反復子のインスタンスは、DocumentTraversal .createNodeIterator(). を呼び出すことによって 作成されます。

も参照してください。[ドキュメント オブジェクト モデル (DOM) レベル 2 トラバーサルおよび範囲指定](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM レベル 2

```csharp
public interface ITraversal : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | ノードのスクリーニングに使用される NodeFilter。 |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | it の作成時に指定された NodeIterator のルート ノード。 |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | この属性は、 イテレーターを介して提示されるノード タイプを決定します。使用可能な定数のセットは、 NodeFilter インターフェイスで定義されています。 whatToShow によって 受け入れられないノードはスキップされますが、それらの子はまだ 考慮される場合があります。このスキップは、フィルタ (存在する場合) よりも優先されることに注意してください. |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 組み立て [Aspose.HTML](../../)


