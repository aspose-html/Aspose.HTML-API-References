---
title: "Node.CloneNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの cloneNode メソッドは、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。

ノードをクローンすると、すべての属性とその値がコピーされ、固有（インライン）のリスナーも含まれます。[`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/)で追加されたイベントリスナーや要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction）はコピーされません。さらに、[`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) 要素の場合、描画された画像はコピーされません。

```java
public Node CloneNode()
```

### 戻り値

新しい [`Node`](../) がクローンされました。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[`Node.appendChild()`](../appendchild/) などのメソッドで追加されるまでです。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもコピーするかどうかを制御します。

ノードをクローンすると、すべての属性とその値がコピーされ、固有（インライン）のリスナーも含まれます。[addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener))で追加されたイベントリスナーや要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction）はコピーされません。さらに、[&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) 要素の場合、描画された画像はコピーされません。

```java
public Node CloneNode(bool deep)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| deep | Boolean | true の場合、ノードとその全サブツリーが、子 [`Text`](../../text/) ノードに含まれる可能性のあるテキストも含めてコピーされます。 |

### 戻り値

新しい [Node](T:com.aspose.html.dom.Node) がクローンされました。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) などのメソッドで追加されるまでです。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
