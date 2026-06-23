---
title: "com.aspose.html.dom.traversal"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "El paquete com.aspose.html.dom.traversal contiene métodos que crean iteradores y recorridos de árbol para navegar entre elementos y recorrer un nodo y sus hijos en orden de documento."
type: docs

url: /es/java/com.aspose.html.dom.traversal/
---
El paquete **com.aspose.html.dom.traversal** contiene métodos que crean iteradores y recorridos de árbol para navegar entre elementos y recorrer un nodo y sus hijos en orden de documento.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contiene métodos que crean iteradores y recorridos de árbol para recorrer un nodo y sus hijos en orden de documento (profundidad primero, recorrido preorden, que es equivalente al orden en que aparecen las etiquetas de inicio en la representación textual del documento). En los DOM que admiten la característica Traversal, DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document. |
| [IElementTraversal](./ielementtraversal/) | La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten al autor navegar fácilmente entre elementos en un documento. En implementaciones conformes de Element Traversal, todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal. |
| [INodeFilter](./inodefilter/) | Los filtros son objetos que saben cómo \"filtrar\" nodos. Si a un NodeIterator o TreeWalker se le proporciona un NodeFilter, éste aplica el filtro antes de devolver el siguiente nodo. Si el filtro indica que se acepte el nodo, la lógica de recorrido lo devuelve; de lo contrario, el recorrido busca el siguiente nodo y simula que el nodo rechazado no existía. |
| [INodeIterator](./inodeiterator/) | Los iteradores se utilizan para recorrer un conjunto de nodos, p. ej., el conjunto de nodos en una NodeList, el subárbol del documento gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar lo determina la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Los iteradores se utilizan para recorrer un conjunto de nodos, p. ej., el conjunto de nodos en una NodeList, el subárbol del documento gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar lo determina la implementación del NodeIterator. DOM Level 2 especifica una única implementación de NodeIterator para el recorrido en orden de documento de un subárbol del documento. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Los objetos TreeWalker se utilizan para navegar un árbol o subárbol de documento usando la vista del documento definida por sus banderas whatToShow y filtro (si lo hay). Cualquier función que realice navegación usando un TreeWalker admitirá automáticamente cualquier vista definida por un TreeWalker. |
