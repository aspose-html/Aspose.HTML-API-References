---
title: "Interfaccia IDocumentTraversal"
second_title: "Riferimento API Aspose.HTML per Java"
description: "com.aspose.html.dom.traversal.IDocumentTraversal interface. DocumentTraversal contiene metodi che creano iteratori e tree-walker per attraversare un nodo e i suoi figli nell'ordine del documento, traversata in profondità pre-ordine, equivalente all'ordine in cui i tag di apertura compaiono nella rappresentazione testuale del documento. Nei DOM che supportano la funzionalità Traversal, DocumentTraversal sarà implementato dagli stessi oggetti che implementano l'interfaccia Document."
type: docs

url: /it/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contiene metodi che creano iteratori e tree-walker per attraversare un nodo e i suoi figli in ordine di documento (profondità prima, attraversamento pre-ordine, che è equivalente all'ordine in cui i tag di apertura compaiono nella rappresentazione testuale del documento). Nei DOM che supportano la funzionalità Traversal, DocumentTraversal sarà implementato dagli stessi oggetti che implementano l'interfaccia Document.

Vedi anche il [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato. |

### Vedi anche

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
