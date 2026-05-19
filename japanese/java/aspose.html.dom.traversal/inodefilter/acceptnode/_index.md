---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "INodeFilter メソッド。指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。必要に応じて、同じフィルタを使用して独自のアプリケーションロジックを導くことも可能です。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。）

```java
public short AcceptNode(Node n)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| n | Node | フィルタを通過するかどうかを確認するノード。 |

### 戻り値

上記で定義されたように、ノードが受け入れられるか、拒否されるか、スキップされるかを決定する定数。

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
