---
title: "INodeFilter.AcceptNode"
second_title: "Aspose.HTML per Java Riferimento API"
description: "Metodo INodeFilter. Verifica se un nodo specificato è visibile nella vista logica di un TreeWalker o NodeIterator. Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; non è normalmente chiamata direttamente dal codice dell'utente. Tuttavia, potresti farlo se desideri utilizzare lo stesso filtro per guidare la logica della tua applicazione."
type: docs

url: /it/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Verifica se un nodo specificato è visibile nella vista logica di un TreeWalker o NodeIterator. Questa funzione sarà chiamata dall'implementazione di TreeWalker e NodeIterator; normalmente non viene chiamata direttamente dal codice dell'utente. (Tuttavia potresti farlo se desideri utilizzare lo stesso filtro per guidare la logica della tua applicazione.)

```java
public short AcceptNode(Node n)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| n | Node | nodo da verificare per vedere se supera o meno il filtro. |

### Valore di ritorno

una costante per determinare se il nodo è accettato, rifiutato o ignorato, come definito sopra.

### Vedi anche

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
