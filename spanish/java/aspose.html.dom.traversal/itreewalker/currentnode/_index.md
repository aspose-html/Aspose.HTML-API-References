---
title: "ITreeWalker.CurrentNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "ITreeWalker property. El nodo en el que el TreeWalker está posicionado actualmente. Las alteraciones al árbol DOM pueden hacer que el nodo actual ya no sea aceptado por el filtro asociado del TreeWalker. currentNode también puede establecerse explícitamente a cualquier nodo, ya sea que esté dentro del subárbol especificado por el nodo raíz o que sería aceptado por el filtro y las banderas whatToShow. Se producirá una mayor navegación relativa a currentNode incluso si no forma parte de la vista actual aplicando los filtros en la dirección solicitada; si no es posible la navegación, currentNode no se cambia."
type: docs

url: /es/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

El nodo en el que el TreeWalker está posicionado actualmente. Las alteraciones al árbol DOM pueden hacer que el nodo actual ya no sea aceptado por el filtro asociado del TreeWalker. currentNode también puede establecerse explícitamente a cualquier nodo, ya sea que esté dentro del subárbol especificado por el nodo raíz o que sería aceptado por el filtro y las banderas whatToShow. Se producirá una mayor navegación relativa a currentNode incluso si no forma parte de la vista actual, aplicando los filtros en la dirección solicitada; si no es posible la navegación, currentNode no se cambia.

```java
public Node CurrentNode { get; set; }
```

### Property Value

El nodo actual.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Generado si se intenta establecer currentNode a null. |

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
