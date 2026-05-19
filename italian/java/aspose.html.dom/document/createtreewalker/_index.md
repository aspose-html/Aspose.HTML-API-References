---
title: "Document.CreateTreeWalker"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Crea un nuovo TreeWalker sul sottoalbero radicato nel nodo specificato"
type: docs

url: /it/java/com.aspose.html.dom/document/createtreewalker/
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

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
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

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
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

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [ITreeWalker](../../../com.aspose.html.dom.traversal/itreewalker/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
