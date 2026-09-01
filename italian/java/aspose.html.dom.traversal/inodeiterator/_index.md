---
title: "Interfaccia INodeIterator"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.traversal.INodeIterator. Gli iteratori sono usati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare Node, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per la traversata nell'ordine del documento di un sottoalbero. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator"
type: docs

url: /it/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Gli iteratori sono usati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare Node, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per l'attraversamento in ordine di documento di un sottoalbero del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator().

Vedi anche il [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Il valore di questo flag determina se i figli dei nodi di riferimento entità sono visibili all'iteratore. Se false, essi e i loro discendenti verranno rifiutati. Nota che questo rifiuto ha precedenza su whatToShow e sul filtro. Inoltre, nota che attualmente è l'unica situazione in cui i NodeIterators possono rifiutare un intero sottoalbero anziché saltare nodi individuali. Per produrre una vista del documento con i riferimenti entità espansi e che non espone il nodo di riferimento entità stesso, usa i flag whatToShow per nascondere il nodo di riferimento entità e imposta expandEntityReferences a true quando crei l'iteratore. Per produrre una vista del documento con nodi di riferimento entità ma senza espansione dell'entità, usa i flag whatToShow per mostrare il nodo di riferimento entità e imposta expandEntityReferences a false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Il nodo di riferimento corrente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Stacca il NodeIterator dal set su cui ha iterato, rilasciando tutte le risorse computazionali e ponendo l'iteratore nello stato INVALID. Dopo che detach è stato invocato, le chiamate a nextNode o previousNode genereranno l'eccezione INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Restituisce il nodo successivo nel set e avanza la posizione dell'iteratore nel set. Dopo che un NodeIterator è stato creato, la prima chiamata a nextNode() restituisce il primo nodo del set. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Restituisce il nodo precedente nel set e sposta la posizione del NodeIterator all'indietro nel set. |

### Vedi anche

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
