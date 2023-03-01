---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Referencia de API de Aspose.HTML para .NET
description: INodeIterator propiedad. El valor de esta marca determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es falso ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene prioridad sobre whatToShow y el filtro. También tenga en cuenta que esta es actualmente la única situación en la que NodeIterators puede rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento que tiene referencias de entidad expandidas y no expone el nodo de referencia de entidad en sí use las banderas whatToShow para oculte la referencia a la entidad node y establezca expandEntityReferences en verdadero al crear el iterador . Para producir una vista del documento que tiene nodos de referencia de entidad pero sin expansión de entidad use whatToShow flags para mostrar el nodo de referencia de entidad y establezca expandEntityReferences en falso.
type: docs
weight: 10
url: /es/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

El valor de esta marca determina si los hijos de los nodos de referencia de entidad son visibles para el iterador. Si es falso, ellos y sus descendientes serán rechazados. Tenga en cuenta que este rechazo tiene prioridad sobre whatToShow y el filtro. También tenga en cuenta que esta es actualmente la única situación en la que NodeIterators puede rechazar un subárbol completo en lugar de omitir nodos individuales. Para producir una vista del documento que tiene referencias de entidad expandidas y no expone el nodo de referencia de entidad en sí, use las banderas whatToShow para oculte la referencia a la entidad node y establezca expandEntityReferences en verdadero al crear el iterador . Para producir una vista del documento que tiene nodos de referencia de entidad pero sin expansión de entidad, use whatToShow flags para mostrar el nodo de referencia de entidad y establezca expandEntityReferences en falso.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### El valor de la propiedad

`verdadero`if [expandir referencias de entidad]; de lo contrario,`FALSO` .

### Ver también

* interface [INodeIterator](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* asamblea [Aspose.HTML](../../../)


