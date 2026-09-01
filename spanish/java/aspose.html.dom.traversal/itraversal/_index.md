---
title: "Interfaz ITraversal"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.traversal.ITraversal. Los iteradores se utilizan para recorrer un conjunto de nodos, por ejemplo, el conjunto de nodos en una NodeList, el subárbol del documento gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar lo determina la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal.createNodeIterator"
type: docs

url: /es/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Los iteradores se utilizan para recorrer un conjunto de nodos, p. ej., el conjunto de nodos en una NodeList, el subárbol del documento gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar lo determina la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator().

Vea también la [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) El NodeFilter usado para filtrar nodos. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) El nodo raíz del NodeIterator, según se especificó al crearlo. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Este atributo determina qué tipos de nodo se presentan mediante el iterador. El conjunto disponible de constantes está definido en la interfaz NodeFilter. Los nodos no aceptados por whatToShow se omitirán, pero sus hijos aún pueden ser considerados. Tenga en cuenta que esta omisión tiene precedencia sobre el filtro, si lo hay. |

### Ver también

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
