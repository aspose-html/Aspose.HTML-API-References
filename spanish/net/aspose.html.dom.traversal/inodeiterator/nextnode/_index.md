---
title: INodeIterator.NextNode
second_title: Referencia de API de Aspose.HTML para .NET
description: INodeIterator método. Devuelve el siguiente nodo del conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator la primera llamada a nextNode devuelve el primer nodo en el conjunto.
type: docs
weight: 40
url: /es/net/aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Devuelve el siguiente nodo del conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator, la primera llamada a nextNode() devuelve el primer nodo en el conjunto.

```csharp
public Node NextNode()
```

### Valor_devuelto

El siguiente nodo del conjunto que se está iterando, o nulo si no hay más miembros en ese conjunto.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_STATE_ERR: se genera si se llama a este método después de que se invocó el método detach. |

### Ver también

* class [Node](../../../aspose.html.dom/node/)
* interface [INodeIterator](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* asamblea [Aspose.HTML](../../../)


