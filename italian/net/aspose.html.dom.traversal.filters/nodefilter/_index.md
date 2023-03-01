---
title: Class NodeFilter
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter classe. I filtri sono oggetti che sanno come filtrare i nodi.
type: docs
weight: 2460
url: /it/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

I filtri sono oggetti che sanno come "filtrare" i nodi.

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Verifica se un nodo specificato è visibile nella vista logica di a TreeWalker o NodeIterator. Questa funzione verrà chiamata dall'implementazione di TreeWalker e NodeIterator; normalmente non viene richiamato direttamente dal codice utente . (Anche se potresti farlo se volessi usare lo stesso filtro per guidare la tua logica applicativa.) |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Questo metodo viene utilizzato per recuperare l'oggetto ECMAScriptType . |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Accetta il nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker restituiranno questo node. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Rifiuta il nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker non restituiranno questo nodo. Per TreeWalker, anche i figli di questo nodo verranno rifiutati. I NodeIterator lo trattano come un sinonimo di FILTER_SKIP. |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Salta questo singolo nodo. I metodi di navigazione definiti per NodeIterator o TreeWalker non restituiranno questo nodo. Sia per NodeIterator che per TreeWalker, i figli di questo nodo saranno comunque considerati . |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | Mostra tutti i nodi. |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Mostra i nodi Attr. Questo è significativo solo quando si crea un iteratore o un tree-walker con un nodo attributo come radice ; in questo caso, significa che l'attributo node apparirà nella prima posizione dell'iterazione o dell'attraversamento. Poiché gli attributi non sono mai figli di altri nodi, non vengono visualizzati durante l'attraversamento dell'albero del documento. |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Mostra nodi CDATASection. |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Mostra nodi Commento. |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | Mostra i nodi del documento. |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Mostra nodi DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Mostra nodi DocumentType. |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | Mostra nodi elemento. |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Mostra nodi entità. Ciò è significativo solo quando si crea un iteratore o un tree-walker con un nodo Entità come radice ; in questo caso, significa che il nodo Entity apparirà nella prima posizione dell'attraversamento. Poiché le entità non fanno parte dell'albero del documento, non vengono visualizzate quando attraversa l'albero del documento. |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Mostra nodi EntityReference. |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Mostra i nodi di notazione. Ciò è significativo solo quando si crea un iteratore o un tree-walker con un nodo Notation come radice ; in questo caso, significa che il nodo Notation apparirà nella prima posizione dell'attraversamento . Poiché le notazioni non fanno parte dell'albero del documento, non appaiono quando si attraversa l'albero del documento. |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Mostra nodi ProcessingInstruction. |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | Mostra nodi di testo. |

### Guarda anche

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* spazio dei nomi [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* assemblea [Aspose.HTML](../../)


