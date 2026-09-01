---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad INodeIterator. El valor de esta bandera determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es false, ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene prioridad sobre whatToShow y el filtro. También observe que actualmente es la única situación en la que los NodeIterators pueden rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento con referencias de entidad expandidas y que no exponga el propio nodo de referencia de entidad, use las banderas whatToShow para ocultar el nodo de referencia de entidad y establezca expandEntityReferences en true al crear el iterador. Para producir una vista del documento que tenga nodos de referencia de entidad pero sin expansión de entidad, use las banderas whatToShow para mostrar el nodo de referencia de entidad y establezca expandEntityReferences en false."
type: docs

url: /es/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

El valor de esta bandera determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es false, ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene prioridad sobre whatToShow y el filtro. También observe que actualmente es la única situación en la que los NodeIterators pueden rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento con referencias de entidad expandidas y que no exponga el nodo de referencia de entidad, use las banderas whatToShow para ocultar el nodo de referencia de entidad y establezca expandEntityReferences en true al crear el iterador. Para producir una vista del documento con nodos de referencia de entidad pero sin expansión de entidad, use las banderas whatToShow para mostrar el nodo de referencia de entidad y establezca expandEntityReferences en false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` si [expand entity references]; de lo contrario, `false`.

### Ver también

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
