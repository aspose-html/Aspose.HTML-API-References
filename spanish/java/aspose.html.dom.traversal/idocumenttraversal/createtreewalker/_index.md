---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IDocumentTraversal. Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado."
type: docs

url: /es/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado.

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que servirá como raíz para el TreeWalker. Las banderas whatToShow y el NodeFilter no se consideran al establecer este valor; cualquier tipo de nodo será aceptado como raíz. El currentNode del TreeWalker se inicializa a este nodo, sea visible o no. La raíz funciona como punto de detención para los métodos de recorrido que buscan hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz no debe ser null. |

### Valor devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que servirá como raíz para el TreeWalker. Las banderas whatToShow y el NodeFilter no se consideran al establecer este valor; cualquier tipo de nodo será aceptado como raíz. El currentNode del TreeWalker se inicializa a este nodo, sea visible o no. La raíz funciona como punto de detención para los métodos de recorrido que buscan hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz no debe ser null. |
| whatToShow | Int64 | La bandera especifica qué tipos de nodo pueden aparecer en la vista lógica del árbol presentado por el tree-walker. Consulte la descripción de NodeFilter para el conjunto de valores SHOW_ posibles. Estas banderas pueden combinarse usando OR. |

### Valor devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Crea un nuevo TreeWalker sobre el subárbol cuya raíz es el nodo especificado.

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que servirá como raíz para el TreeWalker. Las banderas whatToShow y el NodeFilter no se consideran al establecer este valor; cualquier tipo de nodo será aceptado como raíz. El currentNode del TreeWalker se inicializa a este nodo, sea visible o no. La raíz funciona como punto de detención para los métodos de recorrido que buscan hacia arriba en la estructura del documento, como parentNode y nextNode. La raíz no debe ser null. |
| whatToShow | Int64 | La bandera especifica qué tipos de nodo pueden aparecer en la vista lógica del árbol presentado por el tree-walker. Consulte la descripción de NodeFilter para el conjunto de valores SHOW_ posibles. Estas banderas pueden combinarse usando OR. |
| filtro | INodeFilter | NodeFilter a usar con este TreeWalker, o null para indicar que no hay filtro. |

### Valor devuelto

El TreeWalker recién creado.

### Ver también

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
