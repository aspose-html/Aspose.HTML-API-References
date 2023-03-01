---
title: Interface ITraversal
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Traversal.ITraversal interfaz. Los iteradores se utilizan para recorrer un conjunto de nodos por ejemplo el conjunto de nodos en una lista de nodos el subárbol de documentos gobernado por un nodo particular los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator.
type: docs
weight: 2510
url: /es/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Los iteradores se utilizan para recorrer un conjunto de nodos, por ejemplo, el conjunto de nodos en una lista de nodos, el subárbol de documentos gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator().

Véase también el[Modelo de objeto de documento (DOM) Nivel 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @desde DOM Nivel 2

```csharp
public interface ITraversal : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | El NodeFilter utilizado para filtrar nodos. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | El nodo raíz del NodeIterator, como se especificó cuando se creó it . |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Este atributo determina qué tipos de nodos se presentan a través del iterador . El conjunto disponible de constantes se define en la interfaz NodeFilter. Los nodos no aceptados por whatToShow se omitirán, pero sus elementos secundarios aún pueden considerarse . Tenga en cuenta que este salto tiene prioridad sobre el filtro, si lo hay. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* asamblea [Aspose.HTML](../../)


