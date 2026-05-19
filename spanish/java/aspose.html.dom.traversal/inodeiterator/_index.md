---
title: "Interfaz INodeIterator"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.traversal.INodeIterator. Los iteradores se usan para avanzar a través de un conjunto de nodos, por ejemplo el conjunto de nodos en una NodeList, el subárbol del documento gobernado por un Node particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar se determina por la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator"
type: docs

url: /es/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Los iteradores se utilizan para recorrer un conjunto de nodos, p. ej., el conjunto de nodos en un NodeList, el subárbol del documento gobernado por un Node particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar lo determina la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator().

Véase también la [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) El valor de esta bandera determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es false, ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene precedencia sobre whatToShow y el filtro. También observe que actualmente es la única situación en la que los NodeIterators pueden rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento que tenga referencias de entidad expandidas y no exponga el nodo de referencia de entidad en sí, use las banderas whatToShow para ocultar el nodo de referencia de entidad y establezca expandEntityReferences a true al crear el iterador. Para producir una vista del documento que tenga nodos de referencia de entidad pero sin expansión de entidad, use las banderas whatToShow para mostrar el nodo de referencia de entidad y establezca expandEntityReferences a false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) El nodo de referencia actual. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Desacopla el NodeIterator del conjunto que iteró, liberando cualquier recurso computacional y colocando el iterador en el estado INVALID. Después de que se haya invocado detach, las llamadas a nextNode o previousNode lanzarán la excepción INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Devuelve el siguiente nodo del conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator, la primera llamada a nextNode() devuelve el primer nodo del conjunto. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Devuelve el nodo anterior del conjunto y mueve la posición del NodeIterator hacia atrás en el conjunto. |

### Ver también

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
