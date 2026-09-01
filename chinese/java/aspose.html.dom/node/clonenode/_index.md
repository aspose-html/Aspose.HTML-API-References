---
title: "Node.CloneNode"
second_title: "Aspose.HTML for Java API 参考"
description: "Node 方法。Node 接口的 cloneNode 方法返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。"
type: docs

url: /zh/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。

克隆节点会复制其所有属性及其值，包括固有（内联）监听器。它不会复制通过 [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) 添加的事件监听器，也不会复制分配给元素属性的监听器（例如，node.onclick = someFunction）。此外，对于 [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) 元素，绘制的图像不会被复制。

```java
public Node CloneNode()
```

### 返回值

新克隆的 [`Node`](../)。克隆的节点没有父节点，也不属于文档，直到使用 [`Node.appendChild()`](../appendchild/) 或类似方法将其添加到文档中的另一个节点。

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

cloneNode() 方法属于 Node 接口，返回调用该方法的节点的副本。其参数决定是否同时克隆节点中包含的子树。

克隆节点会复制其所有属性及其值，包括固有（内联）监听器。它不会复制通过 [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) 添加的事件监听器，也不会复制分配给元素属性的监听器（例如，node.onclick = someFunction）。此外，对于 [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) 元素，绘制的图像不会被复制。

```java
public Node CloneNode(bool deep)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| deep | Boolean | 如果为 true，则节点及其整个子树，包括子 [`Text`](../../text/) 节点中的文本，也会被复制。 |

### 返回值

新克隆的 [Node](T:com.aspose.html.dom.Node)。克隆的节点没有父节点，也不属于文档，直到使用 [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) 或类似方法将其添加到文档中的另一个节点。

### 另请参见

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
