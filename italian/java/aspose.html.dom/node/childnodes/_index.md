---
title: "Node.ChildNodes"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Proprietà Node. La proprietà read-only childNodes dell'interfaccia Node restituisce una NodeList live dei nodi figlio dell'elemento specificato, dove il primo nodo figlio ha indice 0. I nodi figlio includono elementi, testo e commenti"
type: docs

url: /it/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

La proprietà read-only childNodes dell'interfaccia Node restituisce una live [`NodeList`](../../../com.aspose.html.collections/nodelist/) dei nodi figlio dell'elemento specificato, dove il primo nodo figlio ha indice 0. I nodi figlio includono elementi, testo e commenti.

Nota: Il fatto che la [`NodeList`](../../../com.aspose.html.collections/nodelist/) sia live significa che il suo contenuto viene modificato ogni volta che nuovi figli vengono aggiunti o rimossi.

```java
public NodeList ChildNodes { get; }
```

### Property Value

Una live [`NodeList`](../../../com.aspose.html.collections/nodelist/) contenente i figli del nodo.

Nota: Diverse chiamate a childNodes restituiscono la stessa [`NodeList`](../../../com.aspose.html.collections/nodelist/).

## Osservazioni

Riferimento:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Vedi anche

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
