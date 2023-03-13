---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML for .NET API リファレンス
description: INodeIterator 財産. このフラグの値はentity 参照ノードの子が反復子に表示されるかどうかを決定します false の場合それらとその子孫は拒否されますこの拒否はwhatToShow およびフィルターよりも優先されることに注意してくださいまた これは現在のところ NodeIterators が 個々のノードをスキップするのではなく 完全なサブツリーを拒否する唯一の状況であることにも注意してください.エンティティ参照 node を非表示にし イテレータを作成するときに expandEntityReferences を true に設定しますエンティティ参照 ノードはあるがエンティティ展開がないドキュメントのビューを生成するにはwhatToShow flags を使用してエンティティ参照ノードを表示しset expandEntityReferences を false. に設定します
type: docs
weight: 10
url: /ja/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

このフラグの値は、entity 参照ノードの子が反復子に表示されるかどうかを決定します。 false の場合、それらとその子孫は拒否されます。この拒否は、whatToShow およびフィルターよりも優先されることに注意してください。また、 これは現在のところ、 NodeIterators が 個々のノードをスキップするのではなく、 完全なサブツリーを拒否する唯一の状況であることにも注意してください.エンティティ参照 node を非表示にし、 イテレータを作成するときに expandEntityReferences を true に設定します。エンティティ参照 ノードはあるがエンティティ展開がないドキュメントのビューを生成するには、whatToShow flags を使用してエンティティ参照ノードを表示し、set expandEntityReferences を false. に設定します。

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### プロパティ値

`真実`if [エンティティ参照を展開];さもないと、`間違い`.

### 関連項目

* interface [INodeIterator](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* 組み立て [Aspose.HTML](../../../)


