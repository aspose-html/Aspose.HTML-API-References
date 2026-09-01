---
title: "IDocumentTraversal インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.traversal.IDocumentTraversal インターフェイス。DocumentTraversal には、ノードとその子を文書順（深さ優先の先行順）で走査するイテレータやツリーワーカーを作成するメソッドが含まれます。これは、文書のテキスト表現において開始タグが出現する順序と同等です。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトによって実装されます。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal には、ノードとその子を文書順（深さ優先、先行順走査で、文書のテキスト表現における開始タグの出現順と同等）に走査するイテレータやツリーワーカーを作成するメソッドが含まれています。Traversal 機能をサポートする DOM では、DocumentTraversal は Document インターフェイスを実装するオブジェクトと同じオブジェクトによって実装されます。

こちらも参照してください: [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface IDocumentTraversal
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい NodeIterator を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 指定されたノードを根とするサブツリー上に新しい TreeWalker を作成します。 |

### 関連項目

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
