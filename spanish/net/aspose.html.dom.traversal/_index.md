---
title: Aspose.Html.Dom.Traversal
second_title: Referencia de API de Aspose.HTML para .NET
description: El Aspose.Html.Dom.TraversalEl espacio de nombres contiene métodos que crean iteradores y trepadores de árboles para navegar entre elementos y atraviesan un nodo y sus elementos secundarios en el orden del documento.
type: docs
weight: 170
url: /es/net/aspose.html.dom.traversal/
---
El **Aspose.Html.Dom.Traversal**El espacio de nombres contiene métodos que crean iteradores y trepadores de árboles para navegar entre elementos y atraviesan un nodo y sus elementos secundarios en el orden del documento.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IDocumentTraversal](./idocumenttraversal/) | DocumentTraversal contiene métodos que crean iteradores y tree-walkers para recorrer un nodo y sus elementos secundarios en el orden del documento (profundidad primero, recorrido previo al pedido, que es equivalente al orden en que aparecen las etiquetas de inicio en la representación de texto de el documento). En los DOM que admiten la función Traversal, DocumentTraversal será implementado por los mismos objetos que implementan la interfaz Document. |
| [IElementTraversal](./ielementtraversal/) | La interfaz ElementTraversal es un conjunto de atributos de solo lectura que permiten al autor navegar fácilmente entre los elementos de un documento. Al cumplir con las implementaciones de Element Traversal, todos los objetos que implementan Element también deben implementar la interfaz ElementTraversal. |
| [INodeFilter](./inodefilter/) | Los filtros son objetos que saben cómo "filtrar" los nodos. Si un NodeIterator o TreeWalker recibe un NodeFilter, aplica el filtro antes de devolver el siguiente nodo . Si el filtro dice que acepte el nodo, la lógica transversal lo devuelve ; de lo contrario, el cruce busca el siguiente nodo y finge que el nodo que fue rechazado no estaba allí. |
| [INodeIterator](./inodeiterator/) | Los iteradores se utilizan para recorrer un conjunto de nodos, por ejemplo, el conjunto de nodos en una lista de nodos, el subárbol de documentos gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator(). |
| [ITraversal](./itraversal/) | Los iteradores se utilizan para recorrer un conjunto de nodos, por ejemplo, el conjunto de nodos en una lista de nodos, el subárbol de documentos gobernado por un nodo particular, los resultados de una consulta o cualquier otro conjunto de nodos. El conjunto de nodos a iterar está determinado por la implementación del NodeIterator. El nivel 2 de DOM especifica una implementación única de NodeIterator para el recorrido de orden de documentos de un subárbol de documentos. Las instancias de estos iteradores se crean llamando a DocumentTraversal .createNodeIterator(). |
| [ITreeWalker](./itreewalker/) | Los objetos TreeWalker se utilizan para navegar por un árbol de documentos o un subárbol utilizando la vista del documento definida por sus indicadores y filtros whatToShow (si los hay). Cualquier función que realice la navegación usando un TreeWalker automáticamente admitirá cualquier vista definida por un TreeWalker. |


