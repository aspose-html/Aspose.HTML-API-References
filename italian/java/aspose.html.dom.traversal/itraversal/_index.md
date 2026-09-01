---
title: "Interfaccia ITraversal"
second_title: "Aspose.HTML per Java Riferimento API"
description: "interfaccia com.aspose.html.dom.traversal.ITraversal. Gli iteratori sono usati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un determinato Node, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per l'attraversamento in ordine documentale di un sottoalbero del documento. Le istanze di questi iteratori sono create chiamando DocumentTraversal .createNodeIterator"
type: docs

url: /it/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Gli iteratori sono usati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare Node, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per l'attraversamento in ordine di documento di un sottoalbero del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator().

Vedi anche il [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) Il NodeFilter usato per filtrare i nodi. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Il nodo radice del NodeIterator, come specificato al momento della creazione. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Questo attributo determina quali tipi di nodo sono presentati tramite l'iterator. L'insieme disponibile di costanti è definito nell'interfaccia NodeFilter. I nodi non accettati da whatToShow saranno ignorati, ma i loro figli potranno comunque essere considerati. Nota che questa esclusione ha precedenza sul filtro, se presente. |

### Vedi anche

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
