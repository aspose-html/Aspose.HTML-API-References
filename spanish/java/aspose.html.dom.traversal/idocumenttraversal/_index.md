---
title: "Interfaz IDocumentTraversal"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.traversal.IDocumentTraversal. DocumentTraversal contiene métodos que crean iteradores y tree-walkers para recorrer un nodo y sus hijos en orden de documento, recorrido en profundidad primero preorden, que es equivalente al orden en que aparecen las etiquetas de inicio en la representación textual del documento. En los DOM que soportan la característica Traversal, DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document."
type: docs

url: /es/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contiene métodos que crean iteradores y recorridos de árbol para recorrer un nodo y sus hijos en orden de documento (profundidad primero, recorrido preorden, que es equivalente al orden en que aparecen las etiquetas de inicio en la representación textual del documento). En los DOM que admiten la característica de Traversal, DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document.

Véase también la [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado. |

### Ver también

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
