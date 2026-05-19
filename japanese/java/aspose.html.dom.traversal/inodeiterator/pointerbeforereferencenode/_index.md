---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "INodeIterator プロパティ。このフラグの値は、エンティティ参照ノードの子ノードがイテレータに対して可視かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow とフィルタよりも優先されます。また、現在 NodeIterators が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開されたドキュメントビューを作成し、エンティティ参照ノード自体を公開しないようにするには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるがエンティティ展開を行わないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

このフラグの値は、エンティティ参照ノードの子ノードがイテレータに対して可視かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow とフィルタよりも優先されます。また、現在 NodeIterators が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開されたドキュメントビューを作成し、エンティティ参照ノード自体を公開しないようにするには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるがエンティティ展開を行わないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` なら [expand entity references]、それ以外は `false`。

### 関連項目

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
