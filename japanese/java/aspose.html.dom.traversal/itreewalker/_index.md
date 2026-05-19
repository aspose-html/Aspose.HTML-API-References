---
title: "ITreeWalker インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.ITreeWalker インターフェイス。TreeWalker オブジェクトは、whatToShow フラグと（存在する場合の）フィルタで定義された文書ビューを使用して、文書ツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker オブジェクトは、whatToShow フラグとフィルタ（存在する場合）で定義された文書のビューを使用して、文書ツリーまたはサブツリーをナビゲートするために使用されます。TreeWalker を使用してナビゲーションを行うすべての関数は、TreeWalker が定義する任意のビューを自動的にサポートします。

サブツリーの論理ビューからノードを除外すると、完全でフィルタなしの文書における同じサブツリーとは大きく異なる構造になることがあります。TreeWalker ビューで兄弟関係にあるノードが、元のビューでは異なる、離れた位置にあるノードの子になることがあります。例えば、テキストノードと文書のルートノード以外のすべてのノードをスキップする NodeFilter を考えてみましょう。その結果得られる論理ビューでは、すべてのテキストノードが兄弟となり、元の文書の構造がどれだけ深く入れ子になっていても、ルートノードの直接子として表示されます。

こちらも参照してください: [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker を現在のノードの最初の可視子ノードに移動し、新しいノードを返します。現在のノードに可視子ノードがない場合は null を返し、現在のノードを保持します。 |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker を現在のノードの最後の可視子ノードに移動し、新しいノードを返します。現在のノードに可視子ノードがない場合は null を返し、現在のノードを保持します。 |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | TreeWalker を現在のノードに対して文書順の次の可視ノードに移動し、新しいノードを返します。現在のノードに次のノードがない場合、または nextNode の検索が TreeWalker のルートノードから上方に遡ろうとした場合は null を返し、現在のノードを保持します。 |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker を現在のノードの次の兄弟ノードに移動し、新しいノードを返します。現在のノードに可視な次の兄弟ノードがない場合は null を返し、現在のノードを保持します。 |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | 現在のノードの最も近い可視祖先ノードに移動し、そのノードを返します。parentNode の検索が TreeWalker のルートノードから上方に遡ろうとした場合、または可視な祖先ノードが見つからなかった場合は、現在の位置を保持し null を返します。 |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | TreeWalker を現在のノードに対して文書順で前の可視ノードへ移動させ、新しいノードを返します。現在のノードに前のノードが存在しない場合、または previousNode の検索が TreeWalker のルートノードから上方へ移動しようとした場合は null を返し、現在のノードは保持されます。 |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker を現在のノードの前の兄弟ノードへ移動させ、新しいノードを返します。現在のノードに可視な前の兄弟ノードがない場合は null を返し、現在のノードは保持されます。 |

### 関連項目

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
