---
title: "Node.ParentNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node eigenschap. De alleen-lezen parentNode‑eigenschap van de Node-interface retourneert de ouder van de opgegeven node in de DOM-boom"
type: docs

url: /nl/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

De alleen-lezen parentNode‑eigenschap van de Node-interface retourneert de ouder van de opgegeven node in de DOM-boom.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Een Node die de ouder is van de huidige node. De ouder van een element is een [`Element`](../../element/) node, een [`Document`](../../document/) node, of een [`DocumentFragment`](../../documentfragment/) node.

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
