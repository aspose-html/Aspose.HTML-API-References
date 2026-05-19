---
title: "com.aspose.html.dom.xpath"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "El paquete contiene métodos para navegar a través de elementos y atributos en un documento XML."
type: docs

url: /es/java/com.aspose.html.dom.xpath/
---
El paquete contiene métodos para navegar a través de elementos y atributos en un documento XML.

## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IXPathEvaluator](./ixpathevaluator/) | La evaluación de expresiones XPath es proporcionada por [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [IXPathExpression](./ixpathexpression/) | La interfaz `XPathExpression` representa una expresión XPath analizada y resuelta. |
| [IXPathNamespace](./ixpathpackage/) | La interfaz XPathNamespace es devuelta por interfaces XPathResult para representar el tipo de nodo del paquete XPath que falta en el DOM. |
| [IXPathNSResolver](./ixpathnsresolver/) | La interfaz `XPathNSResolver` permite que las cadenas `prefix` en la expresión se vinculen correctamente a las cadenas `packageURI`. [`IXPathEvaluator`](../com.aspose.html.dom.xpath/ixpathevaluator/) puede construir una implementación de [`IXPathNSResolver`](../com.aspose.html.dom.xpath/ixpathnsresolver/) a partir de un nodo, o la interfaz puede ser implementada por cualquier aplicación. |
| [IXPathResult](./ixpathresult/) | La interfaz `XPathResult` representa el resultado de la evaluación de una expresión XPath 1.0 dentro del contexto de un nodo particular. Dado que la evaluación de una expresión XPath puede producir varios tipos de resultados, este objeto permite descubrir y manipular el tipo y el valor del resultado. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [XPathResultType](./xpathresulttype/) | Un entero corto sin signo que indica qué tipo de resultado es este. Si se especifica un `type` concreto, entonces el resultado se devolverá como el tipo correspondiente, utilizando conversiones de tipo XPath donde sea necesario y posible. |
