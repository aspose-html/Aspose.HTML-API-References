---
title: "com.aspose.html.dom.traversal"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Il pacchetto com.aspose.html.dom.traversal contiene metodi che creano iteratori e tree-walker per navigare tra gli elementi e attraversare un nodo e i suoi figli in ordine di documento."
type: docs

url: /it/java/com.aspose.html.dom.traversal/
---
Il pacchetto **com.aspose.html.dom.traversal** contiene metodi che creano iteratori e tree-walker per navigare tra gli elementi e attraversare un nodo e i suoi figli in ordine documentale.

## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contiene metodi che creano iteratori e tree-walker per attraversare un nodo e i suoi figli in ordine di documento (profondità prima, attraversamento pre-ordine, che è equivalente all'ordine in cui i tag di apertura compaiono nella rappresentazione testuale del documento). Nei DOM che supportano la funzionalità Traversal, DocumentTraversal sarà implementato dagli stessi oggetti che implementano l'interfaccia Document. |
| [IElementTraversal](./ielementtraversal/) | L'interfaccia ElementTraversal è un insieme di attributi di sola lettura che consentono a un autore di navigare facilmente tra gli elementi in un documento. Nelle implementazioni conformi di Element Traversal, tutti gli oggetti che implementano Element devono anche implementare l'interfaccia ElementTraversal. |
| [INodeFilter](./inodefilter/) | I filtri sono oggetti che sanno come "filtrare" i nodi. Se a un NodeIterator o TreeWalker viene fornito un NodeFilter, esso applica il filtro prima di restituire il nodo successivo. Se il filtro indica di accettare il nodo, la logica di attraversamento lo restituisce; altrimenti, l'attraversamento cerca il nodo successivo e finge che il nodo respinto non esista. |
| [INodeIterator](./inodeiterator/) | Gli iteratori sono usati per scorrere un insieme di nodi, ad es. l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un nodo particolare, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per l'attraversamento in ordine di documento di un sottoalbero del documento. Le istanze di questi iteratori sono create chiamando DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Gli iteratori sono usati per scorrere un insieme di nodi, ad es. l'insieme di nodi in una NodeList, il sottoalbero del documento governato da un nodo particolare, i risultati di una query o qualsiasi altro insieme di nodi. L'insieme di nodi da iterare è determinato dall'implementazione del NodeIterator. DOM Level 2 specifica una singola implementazione di NodeIterator per l'attraversamento in ordine di documento di un sottoalbero del documento. Le istanze di questi iteratori sono create chiamando DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Gli oggetti TreeWalker sono usati per navigare un albero o sottoalbero del documento utilizzando la vista del documento definita dalle loro flag whatToShow e dal filtro (se presente). Qualsiasi funzione che esegue la navigazione usando un TreeWalker supporterà automaticamente qualsiasi vista definita da un TreeWalker. |
