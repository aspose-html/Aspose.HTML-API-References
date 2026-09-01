---
title: "Node.TextContent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Propiedad de Node. La propiedad textContent de la interfaz Node representa el contenido de texto del nodo y sus descendientes"
type: docs

url: /es/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

La propiedad textContent de la [`Node`](../) interfaz representa el contenido de texto del nodo y sus descendientes.

```java
public String TextContent { get; set; }
```

### Property Value

Una cadena, o null. Su valor depende de la situación:

Si el nodo es un documento o un doctype, textContent devuelve null. Nota: Para obtener todo el texto y los datos CDATA de todo el documento, use document.documentElement.textContent. Si el nodo es una sección CDATA, un comentario, una instrucción de procesamiento o un nodo de texto, textContent devuelve, o establece, el texto dentro del nodo, es decir, el [`Node.nodeValue`](../nodevalue/). Para otros tipos de nodo, textContent devuelve la concatenación del textContent de cada nodo hijo, excluyendo comentarios e instrucciones de procesamiento.

## Observaciones

Referencia:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
