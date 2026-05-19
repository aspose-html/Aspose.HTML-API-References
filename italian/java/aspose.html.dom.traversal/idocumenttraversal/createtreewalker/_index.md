---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IDocumentTraversal. Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato."
type: docs

url: /it/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che servirà da radice per il TreeWalker. Le flag whatToShow e il NodeFilter non sono considerati durante l'impostazione di questo valore; qualsiasi tipo di nodo sarà accettato come radice. Il currentNode del TreeWalker è inizializzato a questo nodo, sia che sia visibile o meno. La radice funge da punto di arresto per i metodi di attraversamento che risalgono nella struttura del documento, come parentNode e nextNode. La radice non deve essere null. |

### Valore di ritorno

Il TreeWalker appena creato.

### Vedi anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che servirà da radice per il TreeWalker. Le flag whatToShow e il NodeFilter non sono considerati durante l'impostazione di questo valore; qualsiasi tipo di nodo sarà accettato come radice. Il currentNode del TreeWalker è inizializzato a questo nodo, sia che sia visibile o meno. La radice funge da punto di arresto per i metodi di attraversamento che risalgono nella struttura del documento, come parentNode e nextNode. La radice non deve essere null. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire nella vista logica dell'albero presentata dal tree-walker. Vedi la descrizione di NodeFilter per l'insieme dei possibili valori SHOW_. Questi flag possono essere combinati usando OR. |

### Valore di ritorno

Il TreeWalker appena creato.

### Vedi anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che servirà da radice per il TreeWalker. Le flag whatToShow e il NodeFilter non sono considerati durante l'impostazione di questo valore; qualsiasi tipo di nodo sarà accettato come radice. Il currentNode del TreeWalker è inizializzato a questo nodo, sia che sia visibile o meno. La radice funge da punto di arresto per i metodi di attraversamento che risalgono nella struttura del documento, come parentNode e nextNode. La radice non deve essere null. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire nella vista logica dell'albero presentata dal tree-walker. Vedi la descrizione di NodeFilter per l'insieme dei possibili valori SHOW_. Questi flag possono essere combinati usando OR. |
| filtro | INodeFilter | NodeFilter da utilizzare con questo TreeWalker, oppure null per indicare nessun filtro. |

### Valore di ritorno

Il TreeWalker appena creato.

### Vedi anche

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
