---
title: "Interfaz INodeFilter"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.traversal.INodeFilter. Los filtros son objetos que saben cómo filtrar nodos. Si a un NodeIterator o TreeWalker se le proporciona un NodeFilter, este aplica el filtro antes de devolver el siguiente nodo. Si el filtro indica que se acepte el nodo, la lógica de recorrido lo devuelve; de lo contrario, el recorrido busca el siguiente nodo y simula que el nodo rechazado no está."
type: docs

url: /es/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Los filtros son objetos que saben cómo \"filtrar\" nodos. Si a un NodeIterator o TreeWalker se le proporciona un NodeFilter, éste aplica el filtro antes de devolver el siguiente nodo. Si el filtro indica que se acepte el nodo, la lógica de recorrido lo devuelve; de lo contrario, el recorrido busca el siguiente nodo y simula que el nodo rechazado no existía.

El DOM no proporciona filtros. NodeFilter es simplemente una interfaz que los usuarios pueden implementar para proporcionar sus propios filtros.

Los NodeFilters no necesitan saber cómo recorrer de nodo a nodo, ni necesitan conocer nada sobre la estructura de datos que se está recorriendo. Esto hace que sea muy fácil escribir filtros, ya que lo único que deben saber hacer es evaluar un único nodo. Un filtro puede usarse con varios tipos diferentes de recorridos, fomentando la reutilización de código.

Vea también la [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Comprueba si un nodo especificado es visible en la vista lógica de un TreeWalker o NodeIterator. Esta función será llamada por la implementación de TreeWalker y NodeIterator; normalmente no se llama directamente desde el código del usuario. (Aunque podrías hacerlo si quisieras usar el mismo filtro para guiar la lógica de tu propia aplicación.) |

### Ver también

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
