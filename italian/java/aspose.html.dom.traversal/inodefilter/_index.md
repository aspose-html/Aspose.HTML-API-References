---
title: "Interfaccia INodeFilter"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Interfaccia com.aspose.html.dom.traversal.INodeFilter. I filtri sono oggetti che sanno come filtrare i nodi. Se a un NodeIterator o a un TreeWalker viene fornito un NodeFilter, questo applica il filtro prima di restituire il nodo successivo. Se il filtro indica di accettare il nodo, la logica di attraversamento lo restituisce; altrimenti l'attraversamento cerca il nodo successivo e finge che il nodo rifiutato non esista."
type: docs

url: /it/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

I filtri sono oggetti che sanno come "filtrare" i nodi. Se a un NodeIterator o TreeWalker viene fornito un NodeFilter, esso applica il filtro prima di restituire il nodo successivo. Se il filtro indica di accettare il nodo, la logica di attraversamento lo restituisce; altrimenti, l'attraversamento cerca il nodo successivo e finge che il nodo respinto non esista.

Il DOM non fornisce alcun filtro. NodeFilter è semplicemente un'interfaccia che gli utenti possono implementare per fornire i propri filtri.

I NodeFilter non hanno bisogno di sapere come attraversare da nodo a nodo, né devono conoscere nulla della struttura dati che viene attraversata. Questo rende molto semplice scrivere filtri, poiché l'unica cosa che devono fare è valutare un singolo nodo. Un filtro può essere utilizzato con diversi tipi di attraversamenti, favorendo il riutilizzo del codice.

Vedi anche il [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Verifica se un nodo specificato è visibile nella vista logica di un TreeWalker o di un NodeIterator. Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; non viene normalmente chiamata direttamente dal codice dell'utente. (Tuttavia potresti farlo se desideri utilizzare lo stesso filtro per guidare la logica della tua applicazione.) |

### Vedi anche

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
