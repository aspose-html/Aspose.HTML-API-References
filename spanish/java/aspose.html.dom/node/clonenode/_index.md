---
title: "Node.CloneNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de Node. El método cloneNode de la interfaz Node devuelve un duplicado del nodo sobre el que se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no."
type: docs

url: /es/java/com.aspose.html.dom/node/clonenode/
---
## CloneNode() {#clonenode}

El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no.

Clonar un nodo copia todos sus atributos y sus valores, incluidos los listeners intrínsecos (inline). No copia los listeners de eventos añadidos mediante [`addEventListener()`](../../../com.aspose.html.dom.events/ieventtarget/addeventlistener/) o los asignados a propiedades del elemento (p. ej., node.onclick = someFunction). Además, para un elemento [`&lt;canvas&gt;`](../../../com.aspose.html/htmlcanvaselement/), la imagen pintada no se copia.

```java
public Node CloneNode()
```

### Valor de retorno

El nuevo [`Node`](../) clonado. El nodo clonado no tiene padre y no forma parte del documento, hasta que se agrega a otro nodo que sí forma parte del documento, usando [`Node.appendChild()`](../appendchild/) o un método similar.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CloneNode(bool) {#clonenode_1}

El método cloneNode() de la interfaz Node devuelve un duplicado del nodo sobre el cual se llamó este método. Su parámetro controla si el subárbol contenido en un nodo también se clona o no.

Clonar un nodo copia todos sus atributos y sus valores, incluidos los listeners intrínsecos (inline). No copia los listeners de eventos añadidos mediante [addEventListener()](M:com.aspose.html.dom.events.IEventTarget.AddEventListener(System.String,com.aspose.html.dom.events.IEventListener)) o los asignados a propiedades del elemento (p. ej., node.onclick = someFunction). Además, para un elemento [&lt;canvas&gt;](T:Aspose.Html.HTMLCanvasElement), la imagen pintada no se copia.

```java
public Node CloneNode(bool deep)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deep | Boolean | Si es true, entonces el nodo y todo su subárbol, incluido el texto que pueda estar en nodos hijos de [`Text`](../../text/), también se copian. |

### Valor de retorno

El nuevo [Node](T:com.aspose.html.dom.Node) clonado. El nodo clonado no tiene padre y no forma parte del documento, hasta que se agrega a otro nodo que sí forma parte del documento, usando [Node.appendChild()](M:com.aspose.html.dom.Node.AppendChild(com.aspose.html.dom.Node)) o un método similar.

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
