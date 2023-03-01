---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.HTML for .NET API リファレンス
description: IDocumentTraversal 方法. 指定したノード をルートとするサブツリーに新しい NodeIterator を作成します
type: docs
weight: 10
url: /ja/net/aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

指定したノード をルートとするサブツリーに新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | 子とともに反復されるノード. イテレータは、最初はこのノードの直前に配置されます。この位置を設定するとき、 whatToShow フラグとフィルタ (存在する場合) は考慮されません 。ルートは null であってはなりません。 |

### 戻り値

新しく作成された NodeIterator.

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

指定したノード をルートとするサブツリーに新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | 子とともに反復されるノード. イテレータは、最初はこのノードの直前に配置されます。この位置を設定するとき、 whatToShow フラグとフィルタ (存在する場合) は考慮されません 。ルートは null であってはなりません。 |
| whatToShow | Int64 | flag は、反復子によって提示されるツリーの論理ビューに表示されるノード タイプを指定します。可能な SHOW_ 値のセットについては、NodeFilter の の説明を参照してください。これらのフラグは、 OR を使用して組み合わせることができます。 |

### 戻り値

新しく作成された NodeIterator.

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

指定したノード をルートとするサブツリーに新しい NodeIterator を作成します。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| root | Node | 子とともに反復されるノード. イテレータは、最初はこのノードの直前に配置されます。この位置を設定するとき、 whatToShow フラグとフィルタ (存在する場合) は考慮されません 。ルートは null であってはなりません。 |
| whatToShow | Int64 | flag は、反復子によって提示されるツリーの論理ビューに表示されるノード タイプを指定します。可能な SHOW_ 値のセットについては、NodeFilter の の説明を参照してください。これらのフラグは、 OR を使用して組み合わせることができます。 |
| filter | INodeFilter | this TreeWalker で使用される NodeFilter、またはフィルターがないことを示す null。 |

### 戻り値

新しく作成された NodeIterator.

### 例外

| 例外 | 調子 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* 名前空間 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 組み立て [Aspose.HTML](../../../)


