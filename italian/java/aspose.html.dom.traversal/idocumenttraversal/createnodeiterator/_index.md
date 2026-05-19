---
title: "IDocumentTraversal.CreateNodeIterator"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo IDocumentTraversal. Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato."
type: docs

url: /it/java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. Le flag whatToShow e il filtro, se presenti, non sono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. Le flag whatToShow e il filtro, se presenti, non sono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |
| whatToShow | Int64 | flag che specifica quali tipi di nodo possono apparire nella vista logica dell'albero presentata dall'iteratore. Vedi la descrizione di NodeFilter per l'insieme dei possibili valori SHOW_. Queste flag possono essere combinate usando OR. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radice | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. Le flag whatToShow e il filtro, se presenti, non sono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |
| whatToShow | Int64 | flag che specifica quali tipi di nodo possono apparire nella vista logica dell'albero presentata dall'iteratore. Vedi la descrizione di NodeFilter per l'insieme dei possibili valori SHOW_. Queste flag possono essere combinate usando OR. |
| filtro | INodeFilter | NodeFilter da utilizzare con questo TreeWalker, oppure null per indicare nessun filtro. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
