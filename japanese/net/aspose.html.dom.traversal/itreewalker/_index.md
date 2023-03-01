---
title: Interface ITreeWalker
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Traversal.ITreeWalker インターフェース. TreeWalker オブジェクトは whatToShow フラグとフィルター 存在する場合 によって定義されたドキュメントのビューを使用してドキュメント ツリーまたは サブツリーをナビゲートするために使用されます が TreeWalker を使用してナビゲーションを実行する関数は自動的に TreeWalker. によって定義されたビューをサポートします
type: docs
weight: 2520
url: /ja/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker オブジェクトは、 whatToShow フラグとフィルター (存在する場合) によって定義されたドキュメントのビューを使用して、ドキュメント ツリーまたは サブツリーをナビゲートするために使用されます。 が TreeWalker を使用してナビゲーションを実行する関数は、自動的に TreeWalker. によって定義されたビューをサポートします。

サブツリーの論理ビューからノードを省略すると、 完全でフィルター処理されていないドキュメント内の同じサブツリーとは大幅に異なる 構造になる可能性があります。 TreeWalker ビューで兄弟であるノードは、元のビューでは大きく 離れた異なるノードの子である可能性があります。たとえば、テキスト ノードとドキュメントのルート ノード を除くすべてのノードをスキップする NodeFilter を考えてみましょう。結果として得られる論理ビューでは、すべてのテキスト ノードは兄弟になり、ルート ノードの直接の子として表示されます。

も参照してください。[ドキュメント オブジェクト モデル (DOM) レベル 2 トラバーサルおよび範囲指定](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM レベル 2

```csharp
public interface ITreeWalker : ITraversal
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | TreeWalker が現在配置されているノード。 DOM ツリーの変更により、現在のノードが TreeWalker の関連フィルターによって受け入れられなくなる可能性があります。 currentNode は、任意のノードに明示的に設定することもできます。 ルート ノードによって指定されたサブツリー内にあるか、フィルターおよび whatToShow フラグによって受け入れられます。要求された方向にフィルタを適用することにより、現在のビュー の一部でなくても、 currentNode に対して相対的にさらにトラバーサルが発生します。 traversal が不可能な場合、currentNode は変更されません。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | TreeWalker を the 現在のノードの最初に表示されている子に移動し、新しいノードを返します。現在のノードに no 可視の子がない場合は、null を返し、current ノードを保持します。 |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | TreeWalker を the 現在のノードの最後の可視の子に移動し、新しいノードを返します。現在のノードに no 可視の子がない場合は、null を返し、current ノードを保持します。 |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | TreeWalker を、現在のノードに対して document の順序で次の可視ノードに移動し、新しいノードを返します。 現在のノードに次のノードがない場合、または nextNode の検索で が TreeWalker の root ノードから上にステップアップしようとする場合、null を返し、現在のノードを保持します。 |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | TreeWalker を current ノードの次の兄弟に移動し、新しいノードを返します。現在のノードに visible 次の兄弟がない場合は、null を返し、現在のノードを保持します。 |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | current ノードの最も近い可視祖先ノードに移動して返します。 parentNode の検索が TreeWalker のルート ノードから上方向に step しようとする場合、または 表示されている祖先ノードが見つからない場合、このメソッドは 現在の位置を保持し、null. を返します。 |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | TreeWalker を、現在のノードに対して ドキュメント順で前の可視ノードに移動し、new ノードを返します。現在のノードに前のノードがない場合、または previousNode の検索で TreeWalker のルート ノードから上に移動しようとした場合、 null を返し、現在のノードを保持します。 |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | TreeWalker を the 現在のノードの前の兄弟に移動し、新しいノードを返します。現在のノードに前の兄弟が表示されていない場合は、null を返し、 現在のノードを保持します。 |

### 関連項目

* interface [ITraversal](../itraversal/)
* 名前空間 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 組み立て [Aspose.HTML](../../)


