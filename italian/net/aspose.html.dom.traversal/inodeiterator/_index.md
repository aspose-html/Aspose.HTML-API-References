---
title: Interface INodeIterator
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.INodeIterator interfaccia. Gli iteratori vengono utilizzati per scorrere un insieme di nodi ad esempio linsieme di nodi in una NodeList il sottoalbero del documento governato da un particolare nodo i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dallimplementazione di NodeIterator. DOM Level 2 specifica unimplementazione single NodeIterator per lattraversamento dellordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator.
type: docs
weight: 2500
url: /it/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Gli iteratori vengono utilizzati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare nodo, i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dall'implementazione di NodeIterator. DOM Level 2 specifica un'implementazione single NodeIterator per l'attraversamento dell'ordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator().

Vedi anche il[Document object Model (DOM) Livello 2 Traversal e Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface INodeIterator : ITraversal
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Il valore di questo flag determina se i figli dei nodi di riferimento entity sono visibili all'iteratore. Se false, loro e i loro discendenti saranno respinti. Tieni presente che questo rifiuto ha la precedenza su whatToShow e sul filtro. Si noti inoltre che questa è attualmente l'unica situazione in cui NodeIterator può rifiutare un sottoalbero completo piuttosto che saltare singoli nodi. Per produrre una vista del documento con i riferimenti dell'entità espansi e non esporre il nodo di riferimento dell'entità stesso, utilizzare i flag whatToShow per nascondere il riferimento all'entità node e impostare expandEntityReferences su true durante la creazione dell'iteratore . Per produrre una vista del documento che abbia i nodi di riferimento dell'entità ma nessuna espansione dell'entità, usa whatToShow flags per mostrare il nodo del riferimento all'entità e set expandEntityReferences su false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Il nodo di riferimento corrente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Stacca NodeIterator dal set su cui ha iterato , rilasciando tutte le risorse computazionali e ponendo iterator nello stato INVALID. Dopo che il distacco è stato invocato, le chiamate a nextNode o previousNode solleveranno l'eccezione INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Restituisce il nodo successivo nell'insieme e fa avanzare la posizione dell' iteratore nell'insieme. Dopo la creazione di un NodeIterator, la prima chiamata a nextNode() restituisce il primo nodo in l'insieme. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Restituisce il nodo precedente nel set e sposta la posizione del NodeIterator all'indietro nel set. |

### Guarda anche

* interface [ITraversal](../itraversal/)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assemblea [Aspose.HTML](../../)


