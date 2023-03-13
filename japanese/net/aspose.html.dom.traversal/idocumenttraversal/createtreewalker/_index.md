---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML for .NET API リファレンス
description: IDocumentTraversal 方法. 指定したノード をルートとするサブツリーに新しい TreeWalker を作成します
type: docs
weight: 20
url: /ja/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

指定したノード をルートとするサブツリーに新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | TreeWalker のルートとして機能するノード。この値を設定する場合、whatToShow フラグと NodeFilter は考慮されません。 任意のノード タイプがルートとして受け入れられます。 TreeWalker の currentNode は、可視かどうかに関係なく、このノードに初期化されます。 ルートは、 parentNode や nextNode など、ドキュメント構造を上方向に参照する traversal メソッドの停止点として機能します。ルートは null であってはなりません 。 |

### 戻り値

新しく作成された TreeWalker.

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

指定したノード をルートとするサブツリーに新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | TreeWalker のルートとして機能するノード。この値を設定する場合、whatToShow フラグと NodeFilter は考慮されません。 任意のノード タイプがルートとして受け入れられます。 TreeWalker の currentNode は、可視かどうかに関係なく、このノードに初期化されます。 ルートは、 parentNode や nextNode など、ドキュメント構造を上方向に参照する traversal メソッドの停止点として機能します。ルートは null であってはなりません 。 |
| whatToShow | Int64 | flag は、ツリー ウォーカーによって提示されるツリーの論理ビューに表示されるノード タイプを指定します。可能な SHOW_ 値のセットについては、NodeFilter の の説明を参照してください。これらのフラグは、OR を使用して組み合わせることができます。 |

### 戻り値

新しく作成された TreeWalker.

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

指定したノード をルートとするサブツリーに新しい TreeWalker を作成します。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | TreeWalker のルートとして機能するノード。この値を設定する場合、whatToShow フラグと NodeFilter は考慮されません。 任意のノード タイプがルートとして受け入れられます。 TreeWalker の currentNode は、可視かどうかに関係なく、このノードに初期化されます。 ルートは、 parentNode や nextNode など、ドキュメント構造を上方向に参照する traversal メソッドの停止点として機能します。ルートは null であってはなりません 。 |
| whatToShow | Int64 | flag は、ツリー ウォーカーによって提示されるツリーの論理ビューに表示されるノード タイプを指定します。可能な SHOW_ 値のセットについては、NodeFilter の の説明を参照してください。これらのフラグは、OR を使用して組み合わせることができます。 |
| filter | INodeFilter | this TreeWalker で使用される NodeFilter、またはフィルターがないことを示す null。 |

### 戻り値

新しく作成された TreeWalker.

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)


