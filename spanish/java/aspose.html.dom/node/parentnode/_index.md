---
title: "Node.ParentNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad de Node. La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM"
type: docs

url: /es/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

La propiedad de solo lectura parentNode de la interfaz Node devuelve el padre del nodo especificado en el árbol DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Un Node que es el padre del nodo actual. El padre de un elemento es un nodo [`Element`](../../element/), un nodo [`Document`](../../document/) o un nodo [`DocumentFragment`](../../documentfragment/).

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
