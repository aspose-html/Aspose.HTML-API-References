---
title: "Node.CloneNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Methode. Die cloneNode‑Methode des Node‑Interfaces gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter steuert, ob der in einem Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht."
type: docs

url: /de/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht.

Das Klonen eines Knotens kopiert alle seine Attribute und deren Werte, einschließlich intrinsischer (inline) Listener. Es kopiert keine Event‑Listener, die mit [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) hinzugefügt wurden, oder solche, die Element‑Eigenschaften zugewiesen sind (z. B. node.onclick = someFunction). Zusätzlich wird für ein [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/)‑Element das gemalte Bild nicht kopiert.

```java
public Node CloneNode()
```

### Rückgabewert

Der neue [`Node`](../) wurde geklont. Der geklonte Knoten hat keinen Elternknoten und ist nicht Teil des Dokuments, bis er mithilfe von [`Node.appendChild()`](../appendchild/) oder einer ähnlichen Methode zu einem anderen Knoten hinzugefügt wird, der Teil des Dokuments ist.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

Die cloneNode()-Methode des Node-Interface gibt ein Duplikat des Knotens zurück, auf dem diese Methode aufgerufen wurde. Ihr Parameter bestimmt, ob der im Knoten enthaltene Teilbaum ebenfalls geklont wird oder nicht.

Das Klonen eines Knotens kopiert alle seine Attribute und deren Werte, einschließlich intrinsischer (inline) Listener. Es kopiert keine Event‑Listener, die mit [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) hinzugefügt wurden, oder solche, die Element‑Eigenschaften zugewiesen sind (z. B. node.onclick = someFunction). Zusätzlich wird für ein [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement)‑Element das gemalte Bild nicht kopiert.

```java
public Node CloneNode(bool deep)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| deep | Boolean | Wenn true, wird der Knoten und sein gesamter Teilbaum, einschließlich Text, der in untergeordneten [`Text`](../../text/)‑Knoten vorkommen kann, ebenfalls kopiert. |

### Rückgabewert

Der neue [Node](T:com.aspose.html.dom.Node) wurde geklont. Der geklonte Knoten hat keinen Elternknoten und ist nicht Teil des Dokuments, bis er mithilfe von [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) oder einer ähnlichen Methode zu einem anderen Knoten hinzugefügt wird, der Teil des Dokuments ist.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
