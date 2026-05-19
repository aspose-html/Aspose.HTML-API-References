---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Aspose.HTML for Java API リファレンス"
description: "IDocumentTraversal メソッド。指定されたノードをルートとするサブツリー上に新しい NodeIterator を作成します。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。このイテレータは最初、対象ノードの直前に位置付けられます。whatToShow フラグおよびフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。このイテレータは最初、対象ノードの直前に位置付けられます。whatToShow フラグおよびフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。このイテレータは最初、対象ノードの直前に位置付けられます。whatToShow フラグおよびフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに表示できるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |
| フィルタ | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタなしを示すための null。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
