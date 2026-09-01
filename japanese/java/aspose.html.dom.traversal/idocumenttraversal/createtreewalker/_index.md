---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IDocumentTraversal メソッド。指定されたノードをルートとするサブツリー上に新しい TreeWalker を作成します。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとなるノード。whatToShow フラグと NodeFilter はこの値を設定する際には考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかは問われません。ルートは parentNode や nextNode など、文書構造を上方向にたどるトラバーサルメソッドの停止点として機能します。ルートは null であってはなりません。 |

### 戻り値

新しく作成された TreeWalker。

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとなるノード。whatToShow フラグと NodeFilter はこの値を設定する際には考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかは問われません。ルートは parentNode や nextNode など、文書構造を上方向にたどるトラバーサルメソッドの停止点として機能します。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |

### 戻り値

新しく作成された TreeWalker。

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとなるノード。whatToShow フラグと NodeFilter はこの値を設定する際には考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかは問われません。ルートは parentNode や nextNode など、文書構造を上方向にたどるトラバーサルメソッドの停止点として機能します。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |
| フィルタ | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタなしを示すための null。 |

### 戻り値

新しく作成された TreeWalker。

### 関連項目

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
