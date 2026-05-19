---
title: "Node.RemoveChild"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの removeChild メソッドは、DOM から子ノードを削除し、削除されたノードを返します"
type: docs

url: /ja/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Node インターフェイスの removeChild() メソッドは、DOM から子ノードを削除し、削除されたノードを返します。

注：削除された子ノードへの参照が保持されている限り、メモリ上に残りますが、DOM の一部ではなくなります。コード内で後から再利用することも可能です。removeChild() の戻り値が保存されず、他に参照が保持されていない場合、短時間後に自動的にメモリから削除されます。

```java
public Node RemoveChild(Node child)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| child | Node | [`Node`](../) は、DOM から削除される子ノードです。 |

### 戻り値

`[`Node.cloneNode()`](../clonenode/)` とは異なり、戻り値はそれに関連付けられた [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) オブジェクトを保持します。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
