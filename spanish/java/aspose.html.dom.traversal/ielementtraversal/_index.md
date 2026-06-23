---
title: "Interfaz IElementTraversal"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.traversal.IElementTraversal. La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten a un autor navegar fácilmente entre los elementos de un documento. En implementaciones conformes de Element Traversal, todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal."
type: docs

url: /es/java/com.aspose.html.dom.traversal/ielementtraversal/
---
## IElementTraversal interface

La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten al autor navegar fácilmente entre elementos en un documento. En implementaciones conformes de Element Traversal, todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal.

```java
public interface IElementTraversal
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getChildElementCount](../../com.aspose.html.dom.traversal/ielementtraversal/childelementcount/) Devuelve el número actual de nodos elemento que son hijos de este elemento. 0 si este elemento no tiene nodos hijos de tipo nodeType 1. |
| [getFirstElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/firstelementchild/) Devuelve el primer nodo elemento hijo de este elemento. null si este elemento no tiene hijos. |
| [getLastElementChild](../../com.aspose.html.dom.traversal/ielementtraversal/lastelementchild/) Devuelve el último nodo elemento hijo de este elemento. null si este elemento no tiene hijos. |
| [getNextElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/nextelementsibling/) Devuelve el siguiente nodo elemento hermano de este elemento. null si este elemento no tiene nodos hermanos de elemento que sigan a este en el árbol del documento. |
| [getPreviousElementSibling](../../com.aspose.html.dom.traversal/ielementtraversal/previouselementsibling/) Devuelve el nodo elemento hermano anterior de este elemento. null si este elemento no tiene nodos hermanos de elemento que precedan a este en el árbol del documento. |

### Ver también

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
