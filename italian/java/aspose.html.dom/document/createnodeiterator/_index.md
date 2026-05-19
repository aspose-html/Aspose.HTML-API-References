---
title: "Document.CreateNodeIterator"
second_title: "Riferimento API Aspose.HTML per Java"
description: "Metodo Document. Crea un nuovo NodeIterator sul sottoalbero radicato nel nodo specificato"
type: docs

url: /it/java/com.aspose.html.dom/document/createnodeiterator/
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
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
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
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
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
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Generato se la radice specificata è null. |

### Vedi anche

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
