---
title: Interface ITraversal
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.ITraversal interfaccia. Gli iteratori vengono utilizzati per scorrere un insieme di nodi ad esempio linsieme di nodi in una NodeList il sottoalbero del documento governato da un particolare nodo i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dallimplementazione di NodeIterator. DOM Level 2 specifica unimplementazione single NodeIterator per lattraversamento dellordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator.
type: docs
weight: 2510
url: /it/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Gli iteratori vengono utilizzati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare nodo, i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dall'implementazione di NodeIterator. DOM Level 2 specifica un'implementazione single NodeIterator per l'attraversamento dell'ordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator().

Vedi anche il[Document object Model (DOM) Livello 2 Traversal e Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```csharp
public interface ITraversal : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | Il NodeFilter utilizzato per schermare i nodi. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | Il nodo radice di NodeIterator, come specificato quando è stato creato . |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Questo attributo determina quali tipi di nodo vengono presentati tramite l' iteratore. Il set di costanti disponibile è definito nell'interfaccia NodeFilter. I nodi non accettati da whatToShow verranno saltati, ma i loro figli potrebbero comunque essere presi in considerazione. Tieni presente che questo salto ha la precedenza sul filtro, se presente. |

### Guarda anche

* spazio dei nomi [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* assemblea [Aspose.HTML](../../)


