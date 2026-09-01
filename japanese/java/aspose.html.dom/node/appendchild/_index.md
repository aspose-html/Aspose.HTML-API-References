---
title: "Node.AppendChild"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの appendChild メソッドは、指定された親ノードの子リストの末尾にノードを追加します。与えられた子が文書内の既存ノードへの参照である場合、appendChild はそのノードを現在の位置から新しい位置へ移動します。別のノードに追加する前に親ノードから削除する必要はありません。"
type: docs

url: /ja/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

appendChild() メソッドは、Node インターフェイスのもので、指定された親ノードの子リストの末尾にノードを追加します。与えられた子がドキュメント内の既存ノードへの参照である場合、appendChild() はそれを現在の位置から新しい位置へ移動します（他のノードに追加する前に親ノードから削除する必要はありません）。

これは、ノードが文書内の二つの場所に同時に存在できないことを意味します。そのため、ノードに既に親がある場合、まずそのノードは削除され、次に新しい位置に追加されます。[`Node.cloneNode()`](../clonenode/) メソッドを使用すれば、ノードを新しい親の下に追加する前にコピーを作成できます。[`cloneNode`](../clonenode/) で作成されたコピーは自動的に同期されません。

```java
public Node AppendChild(Node node)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ノード | Node | 指定された親ノード（通常は要素）に追加するノード。 |

### 戻り値

追加された子ノード（aChild）となる Node。ただし、aChild が [`DocumentFragment`](../../documentfragment/) の場合は、空の [`DocumentFragment`](../../documentfragment/) が返されます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | DOM ツリーの制約が違反されたときにスローされます。 |

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
