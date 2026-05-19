---
title: "Document.CreateTreeWalker"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します"
type: docs

url: /ja/java/com.aspose.html.dom/document/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグおよび NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかに関わりません。ルートは parentNode や nextNode など、文書構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null であってはなりません。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグおよび NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかに関わりません。ルートは parentNode や nextNode など、文書構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | TreeWalker のルートとして使用されるノード。この値を設定する際、whatToShow フラグおよび NodeFilter は考慮されず、任意のノードタイプがルートとして受け入れられます。TreeWalker の currentNode はこのノードに初期化され、可視かどうかに関わりません。ルートは parentNode や nextNode など、文書構造を上方向にたどる走査メソッドの停止点として機能します。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、ツリーワーカーが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR を使用して組み合わせることができます。 |
| フィルタ | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタなしを示すための null。 |

### 戻り値

新しく作成された TreeWalker。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
