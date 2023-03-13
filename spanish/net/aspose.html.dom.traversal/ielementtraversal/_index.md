---
title: Interface IElementTraversal
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Traversal.IElementTraversal interfaz. La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten al autor navegar fácilmente entre los elementos de un documento. Al cumplir con las implementaciones de Element Traversal todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal.
type: docs
weight: 2480
url: /es/net/aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten al autor navegar fácilmente entre los elementos de un documento. Al cumplir con las implementaciones de Element Traversal, todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal.

```csharp
public interface IElementTraversal
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChildElementCount](../../aspose.html.dom.traversal/ielementtraversal/childelementcount/) { get; } | Devuelve el número actual de nodos de elementos que son hijos de este elemento. 0 si este elemento no tiene nodos secundarios que sean de nodeType 1. |
| [FirstElementChild](../../aspose.html.dom.traversal/ielementtraversal/firstelementchild/) { get; } | Devuelve el primer nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [LastElementChild](../../aspose.html.dom.traversal/ielementtraversal/lastelementchild/) { get; } | Devuelve el último nodo del elemento secundario de este elemento. nulo si este elemento no tiene elementos secundarios. |
| [NextElementSibling](../../aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) { get; } | Devuelve el siguiente nodo de elemento hermano de este elemento. nulo si este elemento no tiene nodos hermanos del elemento que vienen después de este en el árbol del documento. |
| [PreviousElementSibling](../../aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) { get; } | Devuelve el nodo de elemento hermano anterior de este elemento. nulo si este elemento no tiene nodos hermanos que estén antes de este en el árbol del documento. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* asamblea [Aspose.HTML](../../)


