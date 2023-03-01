---
title: Interface INodeIterator
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal.INodeIterator インターフェース. イテレータはNodeList 内のノードの セット特定のノードの によって管理されるドキュメント サブツリークエリの結果またはその他のノードの セットなど一連のノードをステップスルーするために使用されます反復されるノードのセットはNodeIterator の 実装によって決定されます DOM レベル 2 はドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定しますこれらの反復子のインスタンスはDocumentTraversal .createNodeIterator. を呼び出すことによって 作成されます
type: docs
weight: 2500
url: /ja/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

イテレータは、NodeList 内のノードの セット、特定のノードの によって管理されるドキュメント サブツリー、クエリの結果、またはその他のノードの セットなど、一連のノードをステップスルーするために使用されます。反復されるノードのセットは、NodeIterator の 実装によって決定されます。 DOM レベル 2 は、ドキュメント サブツリーのドキュメント順 走査のための 単一 NodeIterator 実装を指定します。これらの反復子のインスタンスは、DocumentTraversal .createNodeIterator(). を呼び出すことによって 作成されます。

も参照してください。[ドキュメント オブジェクト モデル (DOM) レベル 2 トラバーサルおよび範囲指定](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM レベル 2

```csharp
public interface INodeIterator : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | このフラグの値は、entity 参照ノードの子が反復子に表示されるかどうかを決定します。 false の場合、それらとその子孫は拒否されます。この拒否は、whatToShow およびフィルターよりも優先されることに注意してください。また、 これは現在のところ、 NodeIterators が 個々のノードをスキップするのではなく、 完全なサブツリーを拒否する唯一の状況であることにも注意してください.エンティティ参照 node を非表示にし、 イテレータを作成するときに expandEntityReferences を true に設定します。エンティティ参照 ノードはあるがエンティティ展開がないドキュメントのビューを生成するには、whatToShow flags を使用してエンティティ参照ノードを表示し、set expandEntityReferences を false. に設定します。 |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | 現在の参照ノード。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | 反復した セットから NodeIterator を切り離し、すべての計算リソースを解放し、 iterator を INVALID 状態にします。 detach が呼び出された後、 nextNode または previousNode を呼び出すと、 例外 INVALID_STATE_ERR. が発生します |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | セット内の次のノードを返し、セット内の 反復子の位置を進めます。 NodeIterator が作成された後、 nextNode() への最初の呼び出しは セット内の最初のノードを返します. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | セット内の前のノードを返し、 NodeIterator の位置をセット内で後方に移動します。 |

### 関連項目

* interface [ITraversal](../itraversal/)
* 名前空間 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 組み立て [Aspose.HTML](../../)


