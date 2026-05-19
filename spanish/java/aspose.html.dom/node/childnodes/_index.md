---
title: "Node.ChildNodes"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad Node. La propiedad de solo lectura childNodes de la interfaz Node devuelve una NodeList en vivo de los nodos hijos del elemento dado, donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios."
type: docs

url: /es/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

La propiedad de solo lectura childNodes de la interfaz Node devuelve una [`NodeList`](../../../com.aspose.html.collections/nodelist/) en vivo de los nodos hijos del elemento dado, donde el primer nodo hijo tiene el índice 0. Los nodos hijos incluyen elementos, texto y comentarios.

Nota: Que la [`NodeList`](../../../com.aspose.html.collections/nodelist/) sea en vivo significa que su contenido se modifica cada vez que se añaden o eliminan nuevos hijos.

```java
public NodeList ChildNodes { get; }
```

### Property Value

Una [`NodeList`](../../../com.aspose.html.collections/nodelist/) en vivo que contiene los hijos del nodo.

Nota: Varias llamadas a childNodes devuelven la misma [`NodeList`](../../../com.aspose.html.collections/nodelist/).

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Ver también

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
