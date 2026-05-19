---
title: "Node.ParentNode"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà di Node. La proprietà di sola lettura parentNode dell'interfaccia Node restituisce il genitore del nodo specificato nell'albero DOM"
type: docs

url: /it/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

La proprietà di sola lettura parentNode dell'interfaccia Node restituisce il genitore del nodo specificato nell'albero DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Un Node che è il genitore del nodo corrente. Il genitore di un elemento è un nodo [`Element`](../../element/), un nodo [`Document`](../../document/) o un nodo [`DocumentFragment`](../../documentfragment/).

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Vedi anche

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
