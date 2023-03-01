---
title: ITreeWalker.CurrentNode
second_title: Referencia de API de Aspose.HTML para .NET
description: ITreeWalker propiedad. El nodo en el que TreeWalker está posicionado actualmente. Las alteraciones en el árbol DOM pueden hacer que el nodo actual ya no sea aceptado por el filtro asociado de TreeWalker. currentNode también se puede establecer explícitamente en cualquier nodo ya sea dentro del subárbol especificado por el nodo raíz o sería aceptado por las banderas filter y whatToShow. Se produce un recorrido adicional relativo a currentNode incluso si no es parte de la vista actual aplicando los filtros en la dirección solicitada si no es posible atravesar  el nodo actual no cambia.
type: docs
weight: 10
url: /es/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

El nodo en el que TreeWalker está posicionado actualmente. Las alteraciones en el árbol DOM pueden hacer que el nodo actual ya no sea aceptado por el filtro asociado de TreeWalker. currentNode también se puede establecer explícitamente en cualquier nodo, ya sea dentro del subárbol especificado por el nodo raíz o sería aceptado por las banderas filter y whatToShow. Se produce un recorrido adicional relativo a currentNode incluso si no es parte de la vista actual, aplicando los filtros en la dirección solicitada; si no es posible atravesar , el nodo actual no cambia.

```csharp
public Node CurrentNode { get; set; }
```

### El valor de la propiedad

El nodo actual.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: se genera si se intenta establecer currentNode en nulo. |

### Ver también

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../itreewalker/)
* asamblea [Aspose.HTML](../../../)


