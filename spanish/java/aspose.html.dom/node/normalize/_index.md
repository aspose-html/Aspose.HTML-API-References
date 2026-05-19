---
title: "Node.Normalize"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Node method. Coloca todos los nodos Text en toda la profundidad del subárbol bajo este Node, incluidos los nodos de atributo, en una forma normal donde solo la estructura, por ejemplo, elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias de entidad, separan los nodos Text, es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se hubiera guardado y recargado, y es útil cuando se realizan operaciones como búsquedas XPointer que dependen de una estructura de árbol de documento particular. Si el parámetro normalize-characters del objeto DOMConfiguration adjunto al Node.ownerDocument es verdadero, este método también normalizará completamente los caracteres de los nodos Text."
type: docs

url: /es/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Pone todos los nodos [`Text`](../../text/) en toda la profundidad del subárbol bajo este Node, incluidos los nodos de atributo, en una forma "normal" donde solo la estructura (p. ej., [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), y [`entity references`](../../entityreference/)) separa los nodos [`Text`](../../text/), es decir, no hay nodos Text adyacentes ni nodos Text vacíos. Esto puede usarse para asegurar que la vista DOM de un documento sea la misma que si se hubiera guardado y recargado, y es útil cuando se realizan operaciones (como búsquedas XPointer [XPointer]) que dependen de una estructura de árbol de documento particular. Si el parámetro "normalize-characters" del objeto [`DOMConfiguration`](../../../com.aspose.html/configuration/) adjunto al [`Node.ownerDocument`](../ownerdocument/) es verdadero, este método también normalizará completamente los caracteres de los nodos Text.

```java
public void Normalize()
```

### Ver también

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
