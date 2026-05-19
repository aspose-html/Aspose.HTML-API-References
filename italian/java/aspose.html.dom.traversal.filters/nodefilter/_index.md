---
title: "Classe NodeFilter"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.dom.traversal.filters.NodeFilter. I filtri sono oggetti che sanno come filtrare i nodi"
type: docs

url: /it/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

I filtri sono oggetti che sanno come "filtrare" i nodi.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Verifica se un nodo specificato è visibile nella vista logica di un TreeWalker o di un NodeIterator. Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; non viene normalmente chiamata direttamente dal codice dell'utente. (Tuttavia potresti farlo se desideri utilizzare lo stesso filtro per guidare la logica della tua applicazione.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Questo metodo è usato per recuperare il Tipo di oggetto ECMAScript. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accetta il nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker restituiranno questo nodo. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Rifiuta il nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker non restituiranno questo nodo. Per TreeWalker, anche i figli di questo nodo saranno rifiutati. I NodeIterators considerano questo come sinonimo di FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Salta questo singolo nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker non restituiranno questo nodo. Per entrambi NodeIterator e TreeWalker, i figli di questo nodo saranno comunque considerati. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Mostra tutti i Nodi. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Mostra i nodi Attr. Questo ha senso solo quando si crea un iteratore o un tree-walker con un nodo attributo come radice; in tal caso, significa che il nodo attributo apparirà nella prima posizione dell'iterazione o della traversata. Poiché gli attributi non sono mai figli di altri nodi, non compaiono durante la traversata dell'albero del documento. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Mostra i nodi CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Mostra i nodi Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Mostra i nodi Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Mostra i nodi DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Mostra i nodi DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Mostra i nodi Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Mostra i nodi Entity. Questo ha senso solo quando si crea un iteratore o un tree-walker con un nodo Entity come radice; in tal caso, significa che il nodo Entity apparirà nella prima posizione della traversata. Poiché le entità non fanno parte dell'albero del documento, non compaiono durante la traversata dell'albero del documento. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Mostra i nodi EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Mostra i nodi Notation. Questo è significativo solo quando si crea un iteratore o un tree-walker con un nodo Notation come radice; in questo caso, significa che il nodo Notation apparirà nella prima posizione del percorso. Poiché le notazioni non fanno parte dell'albero del documento, non compaiono durante l'attraversamento dell'albero del documento. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Mostra i nodi ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Mostra i nodi Text. |

### Vedi anche

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
