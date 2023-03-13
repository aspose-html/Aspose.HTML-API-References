---
title: INodeFilter.AcceptNode
second_title: Referencia de API de Aspose.HTML para .NET
description: INodeFilter método. Prueba si un nodo específico está visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator normalmente no se llama directamente desde el código de usuario . Aunque podría hacerlo si quisiera usar el mismo filtro para guiar su propia lógica de aplicación.
type: docs
weight: 10
url: /es/net/aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Prueba si un nodo específico está visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código de usuario . (Aunque podría hacerlo si quisiera usar el mismo filtro para guiar su propia lógica de aplicación).

```csharp
public short AcceptNode(Node n)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| n | Node | nodo para comprobar si pasa el filtro o no. |

### Valor_devuelto

una constante para determinar si el nodo es aceptado, rechazado u omitido, como se definió anteriormente.

### Ver también

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../inodefilter/)
* asamblea [Aspose.HTML](../../../)


