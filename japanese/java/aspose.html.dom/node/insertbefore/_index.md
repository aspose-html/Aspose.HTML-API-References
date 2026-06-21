---
title: "Node.InsertBefore"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの insertBefore メソッドは、指定された親ノードの子として、参照ノードの前にノードを挿入します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

insertBefore() メソッドは、Node インターフェイスのもので、指定された親ノードの子として、参照ノードの前にノードを挿入します。

指定されたノードがすでに文書内に存在する場合、insertBefore() はそのノードを現在の位置から新しい位置へ移動します。（つまり、指定された新しい親ノードに追加する前に、既存の親から自動的に削除されます。）

これは、ノードが文書内の二つの場所に同時に存在できないことを意味します。

```java
public Node InsertBefore(Node node, Node child)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ノード | Node | 挿入されるノード。 |
| 子 | Node | newNode が挿入される前のノード。これが null の場合、newNode はノードの子ノードの末尾に挿入されます。 |

### 戻り値

追加された子ノードを返します（newNode が [`DocumentFragment`](../../documentfragment/) の場合は、空の [`DocumentFragment`](../../documentfragment/) が返されます）。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
