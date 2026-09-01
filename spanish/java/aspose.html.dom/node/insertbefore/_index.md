---
title: "Node.InsertBefore"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Node. El método insertBefore de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado."
type: docs

url: /es/java/com.aspose.html.dom/node/insertbefore/
---
## Node.InsertBefore method

El método insertBefore() de la interfaz Node inserta un nodo antes de un nodo de referencia como hijo de un nodo padre especificado.

Si el nodo dado ya existe en el documento, insertBefore() lo mueve de su posición actual a la nueva posición. (Es decir, será eliminado automáticamente de su padre existente antes de añadirlo al nuevo padre especificado.)

Esto significa que un nodo no puede estar en dos ubicaciones del documento simultáneamente.

```java
public Node InsertBefore(Node node, Node child)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Node | El nodo a insertar. |
| hijo | Node | El nodo antes del cual se inserta newNode. Si es null, entonces newNode se inserta al final de los nodos hijos del nodo. |

### Valor devuelto

Devuelve el hijo añadido (a menos que newNode sea un [`DocumentFragment`](../../documentfragment/), en cuyo caso se devuelve el [`DocumentFragment`](../../documentfragment/) vacío).

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
