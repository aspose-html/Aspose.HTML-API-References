---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "INodeIterator メソッド。セット内の次のノードを返し、イテレータの位置をセット内で前方に進めます。NodeIterator が作成された後、最初の nextNode 呼び出しはセット内の最初のノードを返します。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初の nextNode() 呼び出しはセット内の最初のノードを返します。

```java
public Node NextNode()
```

### 戻り値

セット内で反復中の次のノード、またはそれ以上メンバーがない場合は null です。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: デタッチ メソッドが呼び出された後にこのメソッドが呼び出された場合に発生します。 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
