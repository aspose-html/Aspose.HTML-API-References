---
title: Node.Normalize
second_title: Referencia de API de Aspose.HTML para .NET
description: Node método. Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo incluidos los nodos de atributos en una forma normal donde solo la estructura p. ej. elementos comentarios instrucciones de procesamiento secciones CDATA y referencias a entidades separa el texto nodos es decir no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar y es útil cuando las operaciones como las búsquedas de XPointer XPointer que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro normalizecharacters del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero este método también normalizará por completo los caracteres de Text nodes.
type: docs
weight: 280
url: /es/net/aspose.html.dom/node/normalize/
---
## Node.Normalize method

Coloca todos los nodos de texto en toda la profundidad del subárbol debajo de este nodo, incluidos los nodos de atributos, en una forma "normal" donde solo la estructura (p. ej., elementos, comentarios, instrucciones de procesamiento, secciones CDATA y referencias a entidades) separa el texto nodos, es decir, no hay nodos de Texto adyacentes ni nodos de Texto vacíos. Esto se puede usar para garantizar que la vista DOM de un documento sea la misma que si se hubiera guardado y vuelto a cargar, y es útil cuando las operaciones (como las búsquedas de XPointer [XPointer]) que dependen de una estructura de árbol de documento en particular deben realizarse. ser usado. Si el parámetro "normalize-characters" del objeto DOMConfiguration adjunto a Node.ownerDocument es verdadero, este método también normalizará por completo los caracteres de Text nodes.

```csharp
public void Normalize()
```

### Ver también

* class [Node](../)
* espacio de nombres [Aspose.Html.Dom](../../node/)
* asamblea [Aspose.HTML](../../../)


