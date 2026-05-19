---
title: "Node.CloneNode"
second_title: "Aspose.HTML for Java API リファレンス"
description: "Node メソッド。Node インターフェイスの cloneNode メソッドは、このメソッドが呼び出されたノードの複製を返します。そのパラメーターは、ノードに含まれるサブツリーもコピーするかどうかを制御します。"
type: docs

url: /ja/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。

ノードのクローンは、属性とその値をすべてコピーします（固有（インライン）リスナーを含む）。[`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) を使用して追加されたイベントリスナーや、要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction）はコピーされません。さらに、[`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) 要素の場合、描画された画像はコピーされません。

```java
public Node CloneNode()
```

### 戻り値

新しい[`Node`](../) がクローンされました。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[`Node.appendChild()`](../appendchild/) などのメソッドで追加されるまでです。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode() メソッドは、Node インターフェイスのもので、このメソッドが呼び出されたノードの複製を返します。そのパラメータは、ノードに含まれるサブツリーもクローンするかどうかを制御します。

ノードのクローンは、属性とその値をすべてコピーします（固有（インライン）リスナーを含む）。[addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) を使用して追加されたイベントリスナーや、要素プロパティに割り当てられたリスナー（例: node.onclick = someFunction）はコピーされません。さらに、[&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) 要素の場合、描画された画像はコピーされません。

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | 説明 |
| --- | --- | --- |
| deep | Boolean | true の場合、ノードとその全サブツリーが、子[`Text`](../../text/) ノードに含まれるテキストも含めてコピーされます。 |

### 戻り値

新しい[Node](T:com.aspose.html.dom.Node) がクローンされました。クローンされたノードは親を持たず、ドキュメントの一部ではありません。ドキュメントの一部である別のノードに、[Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) などのメソッドで追加されるまでです。

### 関連項目

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
