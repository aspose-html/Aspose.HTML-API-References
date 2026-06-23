---
title: "Node.AppendChild"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Node. El método appendChild de la interfaz Node añade un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild lo mueve de su posición actual a la nueva posición; no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo."
type: docs

url: /es/java/com.aspose.html.dom/node/appendchild/
---
## Node.AppendChild method

El método appendChild() de la interfaz Node agrega un nodo al final de la lista de hijos de un nodo padre especificado. Si el hijo dado es una referencia a un nodo existente en el documento, appendChild() lo mueve de su posición actual a la nueva posición (no es necesario eliminar el nodo de su nodo padre antes de añadirlo a otro nodo).

Esto significa que un nodo no puede estar en dos puntos del documento simultáneamente. Por lo tanto, si el nodo ya tiene un padre, el nodo se elimina primero y luego se añade en la nueva posición. El método [`Node.cloneNode()`](../clonenode/) puede usarse para crear una copia del nodo antes de añadirlo bajo el nuevo padre. Las copias hechas con [`cloneNode`](../clonenode/) no se mantienen automáticamente sincronizadas.

```java
public Node AppendChild(Node node)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Node | El nodo que se añadirá al nodo padre dado (normalmente un elemento). |

### Valor devuelto

Un Node que es el hijo añadido (aChild), excepto cuando aChild es un [`DocumentFragment`](../../documentfragment/), en cuyo caso se devuelve el [`DocumentFragment`](../../documentfragment/) vacío.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | Lanzado cuando se violan las restricciones del árbol DOM. |

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
