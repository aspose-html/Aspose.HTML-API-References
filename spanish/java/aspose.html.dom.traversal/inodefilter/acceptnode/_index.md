---
title: "INodeFilter.AcceptNode"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método INodeFilter. Prueba si un nodo especificado es visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código del usuario. Aunque podrías hacerlo si deseas usar el mismo filtro para guiar la lógica de tu propia aplicación."
type: docs

url: /es/java/com.aspose.html.dom.traversal/inodefilter/acceptnode/
---
## INodeFilter.AcceptNode method

Comprueba si un nodo especificado es visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código del usuario. (Aunque podrías hacerlo si quisieras usar el mismo filtro para guiar la lógica de tu propia aplicación.)

```java
public short AcceptNode(Node n)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| n | Node | nodo a comprobar para ver si pasa el filtro o no. |

### Valor de retorno

una constante para determinar si el nodo es aceptado, rechazado o omitido, según lo definido arriba.

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
