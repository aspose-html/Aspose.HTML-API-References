---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML per riferimento API .NET
description: IDocumentTraversal metodo. Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.
type: docs
weight: 20
url: /it/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che fungerà da radice per the TreeWalker. I flag whatToShow e the NodeFilter non vengono considerati quando si imposta questo valore; qualsiasi tipo di nodo verrà accettato come root. Il currentNode del TreeWalker è inizializzato su questo nodo, indipendentemente dal fatto che sia visibile o meno. La radice funge da punto di arresto per i metodi traversal che guardano verso l'alto nella struttura del documento, come parentNode e nextNode. La radice deve non essere nulla. |

### Valore di ritorno

Il TreeWalker appena creato.

### Guarda anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assemblea [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che fungerà da radice per the TreeWalker. I flag whatToShow e the NodeFilter non vengono considerati quando si imposta questo valore; qualsiasi tipo di nodo verrà accettato come root. Il currentNode del TreeWalker è inizializzato su questo nodo, indipendentemente dal fatto che sia visibile o meno. La radice funge da punto di arresto per i metodi traversal che guardano verso l'alto nella struttura del documento, come parentNode e nextNode. La radice deve non essere nulla. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire in la vista logica dell'albero presentata dal tree-walker. Vedere la descrizione di NodeFilter per l'insieme di possibili SHOW_ valori. Questi flag possono essere combinati utilizzando OR. |

### Valore di ritorno

Il TreeWalker appena creato.

### Guarda anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assemblea [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che fungerà da radice per the TreeWalker. I flag whatToShow e the NodeFilter non vengono considerati quando si imposta questo valore; qualsiasi tipo di nodo verrà accettato come root. Il currentNode del TreeWalker è inizializzato su questo nodo, indipendentemente dal fatto che sia visibile o meno. La radice funge da punto di arresto per i metodi traversal che guardano verso l'alto nella struttura del documento, come parentNode e nextNode. La radice deve non essere nulla. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire in la vista logica dell'albero presentata dal tree-walker. Vedere la descrizione di NodeFilter per l'insieme di possibili SHOW_ valori. Questi flag possono essere combinati utilizzando OR. |
| filter | INodeFilter | NodeFilter da utilizzare con this TreeWalker o null per indicare nessun filtro. |

### Valore di ritorno

Il TreeWalker appena creato.

### Guarda anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* spazio dei nomi [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assemblea [Aspose.HTML](../../../)


