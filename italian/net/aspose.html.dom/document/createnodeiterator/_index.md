---
title: Document.CreateNodeIterator
second_title: Aspose.HTML per riferimento API .NET
description: Document metodo. Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato.
type: docs
weight: 900
url: /it/net/aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato.

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. I flag whatToShow e il filtro, se presenti, non vengono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: sollevato se la radice specificata è null. |

### Guarda anche

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* spazio dei nomi [Aspose.Html.Dom](../../document/)
* assemblea [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. I flag whatToShow e il filtro, se presenti, non vengono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire in la vista logica dell'albero presentato dall'iteratore. Vedere la descrizione di NodeFilter per l'insieme di possibili SHOW_ valori. Questi flag possono essere combinati utilizzando OR. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: sollevato se la radice specificata è null. |

### Guarda anche

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* spazio dei nomi [Aspose.Html.Dom](../../document/)
* assemblea [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Crea un nuovo NodeIterator sulla sottostruttura radicata nel nodo specificato.

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| root | Node | nodo che verrà iterato insieme ai suoi figli. L'iteratore è inizialmente posizionato appena prima di questo nodo. I flag whatToShow e il filtro, se presenti, non vengono considerati durante l'impostazione di questa posizione. La radice non deve essere null. |
| whatToShow | Int64 | flag specifica quali tipi di nodo possono apparire in la vista logica dell'albero presentato dall'iteratore. Vedere la descrizione di NodeFilter per l'insieme di possibili SHOW_ valori. Questi flag possono essere combinati utilizzando OR. |
| filter | INodeFilter | NodeFilter da utilizzare con this TreeWalker o null per indicare nessun filtro. |

### Valore di ritorno

Il NodeIterator appena creato.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR: sollevato se la radice specificata è null. |

### Guarda anche

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* spazio dei nomi [Aspose.Html.Dom](../../document/)
* assemblea [Aspose.HTML](../../../)


