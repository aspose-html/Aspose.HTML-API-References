---
title: Aspose.Html.Dom.Traversal
second_title: Aspose.HTML per riferimento API .NET
description: Il Aspose.Html.Dom.Traversalnamespace contiene metodi che creano iteratori e treewalker per navigare tra gli elementi e attraversare un nodo e i suoi figli nellordine del documento.
type: docs
weight: 170
url: /it/net/aspose.html.dom.traversal/
---
Il **Aspose.Html.Dom.Traversal**namespace contiene metodi che creano iteratori e tree-walker per navigare tra gli elementi e attraversare un nodo e i suoi figli nell'ordine del documento.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contiene metodi che creano iteratori e tree-walker per attraversare un nodo e i suoi figli nell'ordine del documento (profondità prima, attraversamento preordinato, che è equivalente all'ordine in cui i tag di inizio si verificano nella rappresentazione testuale di il documento). Nei DOM che supportano la funzione Traversal, DocumentTraversal sarà implementato dagli stessi oggetti che implementano l'interfaccia Document. |
| [IElementTraversal](./ielementtraversal/) | L'interfaccia ElementTraversal è un insieme di attributi di sola lettura che consentono a un autore di navigare facilmente tra gli elementi in un documento. Nelle implementazioni conformi di Element Traversal, tutti gli oggetti che implementano Element devono implementare anche l'interfaccia ElementTraversal. |
| [INodeFilter](./inodefilter/) | I filtri sono oggetti che sanno come "filtrare" i nodi. Se un NodeIterator o TreeWalker riceve un NodeFilter, applica il filtro prima di restituire il successivo nodo. Se il filtro dice di accettare il nodo, la logica di attraversamento restituisce it; in caso contrario, l'attraversamento cerca il nodo successivo e finge che il nodo rifiutato non fosse presente. |
| [INodeIterator](./inodeiterator/) | Gli iteratori vengono utilizzati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare nodo, i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dall'implementazione di NodeIterator. DOM Level 2 specifica un'implementazione single NodeIterator per l'attraversamento dell'ordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Gli iteratori vengono utilizzati per scorrere un insieme di nodi, ad esempio l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un particolare nodo, i risultati di una query o qualsiasi altro insieme di nodi. Il set di nodi da iterare è determinato dall'implementazione di NodeIterator. DOM Level 2 specifica un'implementazione single NodeIterator per l'attraversamento dell'ordine dei documenti di una sottostruttura del documento. Le istanze di questi iteratori vengono create chiamando DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Gli oggetti TreeWalker vengono utilizzati per navigare in un albero del documento o in un sottoalbero utilizzando la vista del documento definita dai flag e filtri whatToShow (se presenti). Qualsiasi funzione che esegue la navigazione utilizzando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker. |


