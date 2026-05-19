---
title: "INodeIterator.NextNode"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo INodeIterator. Restituisce il nodo successivo nell'insieme e avanza la posizione dell'iteratore nell'insieme. Dopo che un NodeIterator è stato creato, la prima chiamata a nextNode restituisce il primo nodo nell'insieme."
type: docs

url: /it/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Restituisce il nodo successivo nel set e avanza la posizione dell'iteratore nel set. Dopo la creazione di un NodeIterator, la prima chiamata a nextNode() restituisce il primo nodo del set.

```java
public Node NextNode()
```

### Valore di ritorno

Il nodo successivo nell'insieme in fase di iterazione, oppure null se non ci sono più membri in quell'insieme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Generato se questo metodo viene chiamato dopo che è stato invocato il metodo detach. |

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
