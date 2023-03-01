---
title: Interface INodeFilter
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.INodeFilter interfaccia. I filtri sono oggetti che sanno come filtrare i nodi. Se un NodeIterator o TreeWalker riceve un NodeFilter applica il filtro prima di restituire il successivo nodo. Se il filtro dice di accettare il nodo la logica di attraversamento restituisce it in caso contrario lattraversamento cerca il nodo successivo e finge che il nodo rifiutato non fosse presente.
type: docs
weight: 2490
url: /it/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

I filtri sono oggetti che sanno come "filtrare" i nodi. Se un NodeIterator o TreeWalker riceve un NodeFilter, applica il filtro prima di restituire il successivo nodo. Se il filtro dice di accettare il nodo, la logica di attraversamento restituisce it; in caso contrario, l'attraversamento cerca il nodo successivo e finge che il nodo rifiutato non fosse presente.

Il DOM non fornisce alcun filtro. NodeFilter è solo un'interfaccia che gli utenti possono implementare per fornire i propri filtri.

I NodeFilter non hanno bisogno di sapere come attraversare dal nodo al nodo, né hanno bisogno di sapere nulla sulla struttura dei dati che viene attraversata. Questo rende molto facile scrivere filtri, poiché l'unica cosa che devono sapere come fare è valutare un singolo nodo. Un filtro può essere utilizzato con diversi tipi di attraversamento, incoraggiando il riutilizzo del codice.

Vedi anche il[Document object Model (DOM) Livello 2 Traversal e Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeFilter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Verifica se un nodo specificato è visibile nella vista logica di TreeWalker o NodeIterator. Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; normalmente non viene richiamato direttamente dal codice utente . (Anche se potresti farlo se volessi utilizzare lo stesso filtro per guidare la tua logica applicativa.) |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assemblea [Aspose.HTML](../../)


