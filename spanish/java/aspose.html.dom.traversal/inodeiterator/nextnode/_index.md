---
title: "INodeIterator.NextNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método INodeIterator. Devuelve el siguiente nodo en el conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator, la primera llamada a nextNode devuelve el primer nodo del conjunto."
type: docs

url: /es/java/com.aspose.html.dom.traversal/inodeiterator/nextnode/
---
## INodeIterator.NextNode method

Devuelve el siguiente nodo del conjunto y avanza la posición del iterador en el conjunto. Después de crear un NodeIterator, la primera llamada a nextNode() devuelve el primer nodo del conjunto.

```java
public Node NextNode()
```

### Valor devuelto

El siguiente Nodo en el conjunto que se está iterando, o null si no hay más miembros en ese conjunto.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: Generado si se llama a este método después de que se haya invocado el método detach. |

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
