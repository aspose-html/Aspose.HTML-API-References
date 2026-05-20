---
title: "Node.ParentNode"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑egenskap. Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar föräldern till den angivna noden i DOM‑trädet."
type: docs

url: /sv/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Den skrivskyddade parentNode‑egenskapen i Node‑gränssnittet returnerar föräldern till den angivna noden i DOM‑trädet.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

En Node som är föräldern till den aktuella noden. Föräldern till ett element är en [`Element`](../../element/)‑nod, en [`Document`](../../document/)‑nod eller en [`DocumentFragment`](../../documentfragment/)‑nod.

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
