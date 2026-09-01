---
title: "Document.CreateNodeIterator"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Document メソッド。指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します"
type: docs

url: /ja/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。イテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。イテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ルート | Node | 子ノードと共に反復されるノード。イテレータは最初、このノードの直前に位置付けられます。whatToShow フラグとフィルタ（存在する場合）はこの位置設定時には考慮されません。ルートは null であってはなりません。 |
| whatToShow | Int64 | フラグは、イテレータが提示するツリーの論理ビューに現れる可能性のあるノードタイプを指定します。可能な SHOW_ 値のセットについては NodeFilter の説明を参照してください。これらのフラグは OR 演算子で組み合わせることができます。 |
| フィルタ | INodeFilter | この TreeWalker で使用する NodeFilter、またはフィルタなしを示すための null。 |

### 戻り値

新しく作成された NodeIterator。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: 指定されたルートが null の場合に発生します。 |

### 関連項目

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
