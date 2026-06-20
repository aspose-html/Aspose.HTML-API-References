---
title: "Node.ParentNode"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Eigenschaft. Die schreibgeschützte parentNode‑Eigenschaft des Node-Interfaces gibt das übergeordnete Element des angegebenen Knotens im DOM‑Baum zurück."
type: docs

url: /de/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Die schreibgeschützte parentNode‑Eigenschaft des Node-Interfaces gibt das übergeordnete Element des angegebenen Knotens im DOM‑Baum zurück.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Ein Node, der das übergeordnete Element des aktuellen Knotens ist. Das übergeordnete Element eines Elements ist ein [`Element`](../../element/)-Knoten, ein [`Document`](../../document/)-Knoten oder ein [`DocumentFragment`](../../documentfragment/)-Knoten.

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
