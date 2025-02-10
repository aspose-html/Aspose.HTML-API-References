---
title: Node.CloneNode
second_title: Aspose.HTML for Java API Reference
description: Node method. The cloneNode method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not
type: docs
weight: 180
url: /java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.

Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/) element, the painted image is not copied.

```java
public Node CloneNode()
```

### Return Value

The new [`Node`](../) cloned. The cloned node has no parent and is not part of the document, until it is added to another node that is part of the document, using [`Node.appendChild()`](../appendchild/) or a similar method.

### See Also

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

The cloneNode() method of the Node interface returns a duplicate of the node on which this method was called. Its parameter controls if the subtree contained in a node is also cloned or not.

Cloning a node copies all of its attributes and their values, including intrinsic (inline) listeners. It does not copy event listeners added using [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) or those assigned to element properties (e.g., node.onclick = someFunction). Additionally, for a [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement) element, the painted image is not copied.

```java
public Node CloneNode(bool deep)
```

| Parameter | Type | Description |
| --- | --- | --- |
| deep | Boolean | If true, then the node and its whole subtree, including text that may be in child [`Text`](../../text/) nodes, is also copied. |

### Return Value

The new [Node](T:com.aspose.html.dom.Node) cloned. The cloned node has no parent and is not part of the document, until it is added to another node that is part of the document, using [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) or a similar method.

### See Also

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
