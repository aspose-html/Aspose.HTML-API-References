---
title: "Node.ParentNode"
second_title: "Αναφορά API του Aspose.HTML για Java"
description: "Ιδιότητα Node. Η μόνο για ανάγνωση ιδιότητα parentNode της διεπαφής Node επιστρέφει τον γονέα του συγκεκριμένου κόμβου στο δέντρο DOM."
type: docs

url: /el/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

Η μόνο για ανάγνωση ιδιότητα parentNode της διεπαφής Node επιστρέφει τον γονέα του συγκεκριμένου κόμβου στο δέντρο DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Ένας Node που είναι ο γονέας του τρέχοντος κόμβου. Ο γονέας ενός στοιχείου είναι ένας κόμβος [`Element`](../../element/), ένας κόμβος [`Document`](../../document/), ή ένας κόμβος [`DocumentFragment`](../../documentfragment/).

## Παρατηρήσεις

Αναφορά:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Δείτε επίσης

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
