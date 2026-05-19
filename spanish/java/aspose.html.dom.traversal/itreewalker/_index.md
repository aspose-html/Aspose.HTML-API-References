---
title: "Interfaz ITreeWalker"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Interfaz com.aspose.html.dom.traversal.ITreeWalker. Los objetos TreeWalker se utilizan para navegar un árbol o subárbol de documento usando la vista del documento definida por sus banderas whatToShow y filtro, si lo hay. Cualquier función que realice navegación usando un TreeWalker soportará automáticamente cualquier vista definida por un TreeWalker."
type: docs

url: /es/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

Los objetos TreeWalker se utilizan para navegar un árbol o subárbol de documento usando la vista del documento definida por sus banderas whatToShow y filtro (si lo hay). Cualquier función que realice navegación usando un TreeWalker admitirá automáticamente cualquier vista definida por un TreeWalker.

Omitir nodos de la vista lógica de un subárbol puede resultar en una estructura sustancialmente diferente de la del mismo subárbol en el documento completo y sin filtrar. Los nodos que son hermanos en la vista del TreeWalker pueden ser hijos de diferentes nodos, muy separados, en la vista original. Por ejemplo, considera un NodeFilter que omite todos los nodos excepto los nodos de texto y el nodo raíz de un documento. En la vista lógica resultante, todos los nodos de texto serán hermanos y aparecerán como hijos directos del nodo raíz, sin importar cuán profundamente anidada esté la estructura del documento original.

Véase también la [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Mueve el TreeWalker al primer hijo visible del nodo actual y devuelve el nuevo nodo. Si el nodo actual no tiene hijos visibles, devuelve null y conserva el nodo actual. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Mueve el TreeWalker al último hijo visible del nodo actual y devuelve el nuevo nodo. Si el nodo actual no tiene hijos visibles, devuelve null y conserva el nodo actual. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Mueve el TreeWalker al siguiente nodo visible en orden de documento relativo al nodo actual y devuelve el nuevo nodo. Si el nodo actual no tiene nodo siguiente, o si la búsqueda de nextNode intenta avanzar hacia arriba desde el nodo raíz del TreeWalker, devuelve null y conserva el nodo actual. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Mueve el TreeWalker al siguiente hermano visible del nodo actual y devuelve el nuevo nodo. Si el nodo actual no tiene hermano siguiente visible, devuelve null y conserva el nodo actual. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Se mueve y devuelve el nodo ancestro visible más cercano del nodo actual. Si la búsqueda de parentNode intenta avanzar hacia arriba desde el nodo raíz del TreeWalker, o si no logra encontrar un ancestro visible, este método conserva la posición actual y devuelve null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Mueve el TreeWalker al nodo visible anterior en orden de documento relativo al nodo actual, y devuelve el nuevo nodo. Si el nodo actual no tiene nodo anterior, o si la búsqueda de previousNode intenta subir desde el nodo raíz del TreeWalker, devuelve null y conserva el nodo actual. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Mueve el TreeWalker al hermano anterior del nodo actual, y devuelve el nuevo nodo. Si el nodo actual no tiene hermano visible anterior, devuelve null y conserva el nodo actual. |

### Ver también

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
