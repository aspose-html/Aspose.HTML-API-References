---
title: "Document.CreateNodeIterator"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. Crea un nuevo NodeIterator sobre el subárbol enraizado en el nodo especificado"
type: docs

url: /es/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que será iterado junto con sus hijos. El iterador se posiciona inicialmente justo antes de este nodo. Las banderas whatToShow y el filtro, si los hay, no se consideran al establecer esta posición. La raíz no debe ser null. |

### Valor devuelto

El NodeIterator recién creado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Se genera si la raíz especificada es null. |

### Ver también

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que será iterado junto con sus hijos. El iterador se posiciona inicialmente justo antes de este nodo. Las banderas whatToShow y el filtro, si los hay, no se consideran al establecer esta posición. La raíz no debe ser null. |
| whatToShow | Int64 | bandera que especifica qué tipos de nodo pueden aparecer en la vista lógica del árbol presentado por el iterador. Consulte la descripción de NodeFilter para el conjunto de valores SHOW_ posibles. Estas banderas pueden combinarse usando OR. |

### Valor devuelto

El NodeIterator recién creado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Se genera si la raíz especificada es null. |

### Ver también

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Crea un nuevo NodeIterator sobre el subárbol cuya raíz es el nodo especificado.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| raíz | Node | nodo que será iterado junto con sus hijos. El iterador se posiciona inicialmente justo antes de este nodo. Las banderas whatToShow y el filtro, si los hay, no se consideran al establecer esta posición. La raíz no debe ser null. |
| whatToShow | Int64 | bandera que especifica qué tipos de nodo pueden aparecer en la vista lógica del árbol presentado por el iterador. Consulte la descripción de NodeFilter para el conjunto de valores SHOW_ posibles. Estas banderas pueden combinarse usando OR. |
| filtro | INodeFilter | NodeFilter a usar con este TreeWalker, o null para indicar que no hay filtro. |

### Valor devuelto

El NodeIterator recién creado.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Se genera si la raíz especificada es null. |

### Ver también

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
