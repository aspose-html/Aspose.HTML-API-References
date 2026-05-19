---
title: "INodeIterator インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.INodeIterator インターフェイス。イテレータは、NodeList 内のノード集合、特定の Node が支配する文書サブツリー、クエリの結果、またはその他任意のノード集合など、一連のノードを順に処理するために使用されます。反復対象となるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 では、文書順でサブツリーを走査するための単一の NodeIterator 実装が規定されています。これらのイテレータのインスタンスは、DocumentTraversal の createNodeIterator を呼び出すことで作成されます。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

イテレータはノードの集合を順に処理するために使用されます。例えば、NodeList のノード集合、特定のノードが支配する文書サブツリー、クエリの結果、またはその他の任意のノード集合です。イテレートされるノード集合は NodeIterator の実装によって決定されます。DOM Level 2 は、文書順にサブツリーを走査するための単一の NodeIterator 実装を規定しています。これらのイテレータのインスタンスは DocumentTraversal の createNodeIterator() を呼び出すことで作成されます。

こちらも参照してください: [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) このフラグの値は、エンティティ参照ノードの子ノードがイテレータに対して可視かどうかを決定します。false の場合、これらとその子孫は除外されます。この除外は whatToShow およびフィルタよりも優先されることに注意してください。また、現在のところ NodeIterator が個々のノードをスキップするのではなく、完全なサブツリーを除外できる唯一の状況です。エンティティ参照が展開された状態で、エンティティ参照ノード自体を表示しない文書ビューを作成するには、whatToShow フラグでエンティティ参照ノードを非表示にし、イテレータ作成時に expandEntityReferences を true に設定します。エンティティ参照ノードはあるが展開しないビューを作成するには、whatToShow フラグでエンティティ参照ノードを表示し、expandEntityReferences を false に設定します。 |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) 現在の参照ノードです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | NodeIterator を反復していたセットから切り離し、計算リソースを解放してイテレータを INVALID 状態にします。detach が呼び出された後は、nextNode または previousNode の呼び出しは例外 INVALID_STATE_ERR を送出します。 |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初の nextNode() 呼び出しはセット内の最初のノードを返します。 |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | セット内の前のノードを返し、NodeIterator の位置をセット内で後方に移動させます。 |

### 関連項目

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
