---
title: IDocumentTraversal.CreateTreeWalker
second_title: Referencia de API de Aspose.HTML para .NET
description: IDocumentTraversal método. Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado.
type: docs
weight: 20
url: /es/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| root | Node | nodo que servirá como raíz para the TreeWalker. Los indicadores whatToShow y NodeFilter no se tienen en cuenta al establecer este valor; se aceptará cualquier tipo de nodo como raíz. El currentNode del TreeWalker se inicializa en este nodo, ya sea que esté visible o no. La raíz funciona como un punto de parada para los métodos transversales que miran hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz debe no ser nula. |

### Valor_devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* asamblea [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| root | Node | nodo que servirá como raíz para the TreeWalker. Los indicadores whatToShow y NodeFilter no se tienen en cuenta al establecer este valor; se aceptará cualquier tipo de nodo como raíz. El currentNode del TreeWalker se inicializa en este nodo, ya sea que esté visible o no. La raíz funciona como un punto de parada para los métodos transversales que miran hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz debe no ser nula. |
| whatToShow | Int64 | bandera especifica qué tipos de nodos pueden aparecer en la vista lógica del árbol presentado por el caminante de árboles. Consulte la descripción de de NodeFilter para conocer el conjunto de valores posibles SHOW_. Estos indicadores se pueden combinar mediante OR. |

### Valor_devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* asamblea [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Crear un nuevo TreeWalker sobre el subárbol enraizado en el nodo especificado.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| root | Node | nodo que servirá como raíz para the TreeWalker. Los indicadores whatToShow y NodeFilter no se tienen en cuenta al establecer este valor; se aceptará cualquier tipo de nodo como raíz. El currentNode del TreeWalker se inicializa en este nodo, ya sea que esté visible o no. La raíz funciona como un punto de parada para los métodos transversales que miran hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz debe no ser nula. |
| whatToShow | Int64 | bandera especifica qué tipos de nodos pueden aparecer en la vista lógica del árbol presentado por el caminante de árboles. Consulte la descripción de de NodeFilter para conocer el conjunto de valores posibles SHOW_. Estos indicadores se pueden combinar mediante OR. |
| filter | INodeFilter | NodeFilter para usar con this TreeWalker, o nulo para indicar que no hay filtro. |

### Valor_devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* espacio de nombres [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* asamblea [Aspose.HTML](../../../)


