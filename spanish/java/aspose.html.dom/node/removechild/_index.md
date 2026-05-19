---
title: "Node.RemoveChild"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de Node. El método removeChild de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado"
type: docs

url: /es/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

El método removeChild() de la interfaz Node elimina un nodo hijo del DOM y devuelve el nodo eliminado.

Nota: Mientras se mantenga una referencia al hijo eliminado, éste sigue existiendo en memoria, pero ya no forma parte del DOM. Puede volver a usarse más adelante en el código. Si el valor de retorno de removeChild() no se almacena y no se mantiene otra referencia, se eliminará automáticamente de la memoria después de un corto período.

```java
public Node RemoveChild(Node child)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| child | Node | Un [`Node`](../) que es el nodo hijo a eliminar del DOM. |

### Valor de retorno

A diferencia de [`Node.cloneNode()`](../clonenode/) el valor de retorno conserva los objetos [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) asociados.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
