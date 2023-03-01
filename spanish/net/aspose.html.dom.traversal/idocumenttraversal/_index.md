---
title: Interface IDocumentTraversal
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Traversal.IDocumentTraversal interfaz. DocumentTraversal contiene métodos que crean iteradores y treewalkers para recorrer un nodo y sus elementos secundarios en el orden del documento profundidad primero recorrido previo al pedido que es equivalente al orden en que aparecen las etiquetas de inicio en la representación de texto de el documento. En los DOM que admiten la función Traversal DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document.
type: docs
weight: 2470
url: /es/net/aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal contiene métodos que crean iteradores y tree-walkers para recorrer un nodo y sus elementos secundarios en el orden del documento (profundidad primero, recorrido previo al pedido, que es equivalente al orden en que aparecen las etiquetas de inicio en la representación de texto de el documento). En los DOM que admiten la función Traversal, DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document.

Véase también el[Modelo de objeto de documento (DOM) Nivel 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @desde DOM Nivel 2

```csharp
public interface IDocumentTraversal
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Crear un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* asamblea [Aspose.HTML](../../)


