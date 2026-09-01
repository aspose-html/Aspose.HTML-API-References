---
title: "NodeFilter.AcceptNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "NodeFilter メソッド。指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出され、通常はユーザーコードから直接呼び出されません。ただし、同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/
---
## NodeFilter.AcceptNode method

指定されたノードが TreeWalker または NodeIterator の論理ビューで可視かどうかをテストします。この関数は TreeWalker と NodeIterator の実装によって呼び出されますが、通常はユーザーコードから直接呼び出されません。（同じフィルタを使用して独自のアプリケーションロジックを導く場合は、呼び出すことも可能です。）

```java
public abstract short AcceptNode(Node n)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| n | Node | フィルタを通過するかどうかを確認するノード。 |

### 戻り値

上記で定義されたように、ノードが受け入れられるか、拒否されるか、スキップされるかを決定する定数。

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* class [NodeFilter](../)
* package [com.aspose.html.dom.traversal.filters](../../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../../)
