---
title: "Node.ParentNode"
second_title: "Referensi API Aspose.HTML untuk Java"
description: "Properti Node. Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM"
type: docs

url: /id/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Properti read-only parentNode dari antarmuka Node mengembalikan induk dari node yang ditentukan dalam pohon DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Sebuah Node yang merupakan induk dari node saat ini. Induk dari sebuah elemen adalah node [`Element`](../../element/), node [`Document`](../../document/), atau node [`DocumentFragment`](../../documentfragment/).

## Catatan

Referensi:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Lihat Juga

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
