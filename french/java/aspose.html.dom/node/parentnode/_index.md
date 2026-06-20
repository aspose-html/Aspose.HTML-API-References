---
title: "Node.ParentNode"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Propriété Node. La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM."
type: docs

url: /fr/java/com.aspose.html.dom/node/parentnode/
---
## Node.ParentNode property

La propriété en lecture seule parentNode de l'interface Node renvoie le parent du nœud spécifié dans l'arbre DOM.

[`Document`](../../document/) and [`DocumentFragment`](../../documentfragment/) nodes can never have a parent, so parentNode will always return null. It also returns null if the node has just been created and is not yet attached to the tree.

```java
public Node ParentNode { get; }
```

### Property Value

Un Node qui est le parent du nœud actuel. Le parent d'un élément est un nœud [`Element`](../../element/), un nœud [`Document`](../../document/) ou un nœud [`DocumentFragment`](../../documentfragment/).

## Remarques

Référence :

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-parentnode](https://dom.spec.whatwg.org/#dom-node-parentnode).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Voir aussi

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
