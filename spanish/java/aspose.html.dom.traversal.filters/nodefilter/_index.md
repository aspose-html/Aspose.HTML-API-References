---
title: "Clase NodeFilter"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.traversal.filters.NodeFilter. Los filtros son objetos que saben cómo filtrar nodos"
type: docs

url: /es/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

Los filtros son objetos que saben cómo "filtrar" nodos.

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | Comprueba si un nodo especificado es visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código del usuario. (Aunque podrías hacerlo si quisieras usar el mismo filtro para guiar la lógica de tu propia aplicación.) |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | Este método se usa para recuperar el Tipo de objeto ECMAScript. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | Aceptar el nodo. Los métodos de navegación definidos para NodeIterator o TreeWalker devolverán este nodo. |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | Rechazar el nodo. Los métodos de navegación definidos para NodeIterator o TreeWalker no devolverán este nodo. Para TreeWalker, los hijos de este nodo también serán rechazados. Los NodeIterators tratan esto como sinónimo de FILTER_SKIP. |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | Omitir este nodo único. Los métodos de navegación definidos para NodeIterator o TreeWalker no devolverán este nodo. Tanto para NodeIterator como para TreeWalker, los hijos de este nodo seguirán siendo considerados. |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | Mostrar todos los nodos. |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | Mostrar nodos Attr. Esto solo tiene sentido al crear un iterador o tree-walker con un nodo de atributo como raíz; en este caso, significa que el nodo de atributo aparecerá en la primera posición de la iteración o recorrido. Dado que los atributos nunca son hijos de otros nodos, no aparecen al recorrer el árbol del documento. |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | Mostrar nodos CDATASection. |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | Mostrar nodos Comment. |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | Mostrar nodos Document. |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | Mostrar nodos DocumentFragment. |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | Mostrar nodos DocumentType. |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | Mostrar nodos Element. |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | Mostrar nodos Entity. Esto solo tiene sentido al crear un iterador o tree-walker con un nodo Entity como raíz; en este caso, significa que el nodo Entity aparecerá en la primera posición del recorrido. Dado que las entidades no forman parte del árbol del documento, no aparecen al recorrer el árbol del documento. |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | Mostrar nodos EntityReference. |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | Mostrar nodos Notation. Esto solo tiene sentido al crear un iterador o tree-walker con un nodo Notation como raíz; en este caso, significa que el nodo Notation aparecerá en la primera posición del recorrido. Dado que las notaciones no forman parte del árbol del documento, no aparecen al recorrer el árbol del documento. |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | Mostrar nodos ProcessingInstruction. |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | Mostrar nodos Text. |

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
