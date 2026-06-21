---
title: "INodeIterator.NextNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "INodeIterator メソッド。セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初の nextNode 呼び出しはセット内の最初のノードを返します。"
type: docs

url: /ja/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

セット内の次のノードを返し、イテレータの位置をセット内で進めます。NodeIterator が作成された後、最初の nextNode() 呼び出しはセット内の最初のノードを返します。

```java
public Node NextNode()
```

### 戻り値

反復中のセット内の次のノード、またはそのセットにメンバーがもう無い場合は null。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: detach メソッドが呼び出された後にこのメソッドが呼び出された場合に発生します。 |

### 関連項目

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
