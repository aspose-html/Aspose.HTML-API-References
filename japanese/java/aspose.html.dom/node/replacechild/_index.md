---
title: "Node.ReplaceChild"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。子ノード oldChild を newChild に置き換えて子リストに挿入し、oldChild ノードを返します。newChild が DocumentFragment オブジェクトの場合、oldChild は DocumentFragment のすべての子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、最初に削除されます。"
type: docs

url: /ja/java/com.aspose.html.dom/node/replacechild/
---
## Node.ReplaceChild method

子ノード oldChild を newChild に置き換えて子リストに挿入し、oldChild ノードを返します。newChild が [`DocumentFragment`](../../documentfragment/) オブジェクトの場合、oldChild はすべての [`DocumentFragment`](../../documentfragment/) 子ノードに置き換えられ、同じ順序で挿入されます。newChild がすでにツリー内にある場合は、最初に削除されます。

```java
public Node ReplaceChild(Node node, Node child)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ノード | Node | oldChild を置き換える新しいノード。 |
| 子 | Node | 置き換えられる子ノード。 |

### 戻り値

置き換えられた Node。これは oldChild と同じノードです。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
