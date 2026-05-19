---
title: "Interfaz IXPathResult"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.xpath.IXPathResult. La interfaz XPathResult representa el resultado de la evaluación de una expresión XPath 1.0 dentro del contexto de un nodo particular. Dado que la evaluación de una expresión XPath puede resultar en varios tipos de resultados, este objeto permite descubrir y manipular el tipo y el valor del resultado."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathresult/
---
## IXPathResult interface

La interfaz `XPathResult` representa el resultado de la evaluación de una expresión XPath 1.0 dentro del contexto de un nodo particular. Dado que la evaluación de una expresión XPath puede producir varios tipos de resultados, este objeto permite descubrir y manipular el tipo y el valor del resultado.

```java
public interface IXPathResult
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBooleanValue](../../com.aspose.html.dom.xpath/ixpathresult/booleanvalue/) El valor de este resultado booleano. |
| [getInvalidIteratorState](../../com.aspose.html.dom.xpath/ixpathresult/invaliditeratorstate/) Indica que el iterador se ha vuelto inválido. Verdadero si `resultType` es del tipo `UnorderedNodeIterator` o `OrderedNodeIterator` y el documento ha sido modificado desde que se devolvió este resultado. |
| [getNumberValue](../../com.aspose.html.dom.xpath/ixpathresult/numbervalue/) El valor de este resultado numérico. |
| [getResultType](../../com.aspose.html.dom.xpath/ixpathresult/resulttype/) Un código que representa el tipo de este resultado, según lo definido por el enumerado http://www.w3.org/TR/DOM-Level-3-XPath/xpath.html#XPathResult[`XPathResultType`](../xpathresulttype/) enum. |
| [getSingleNodeValue](../../com.aspose.html.dom.xpath/ixpathresult/singlenodevalue/) El valor de este resultado de nodo único, que puede ser `null`. |
| [getSnapshotLength](../../com.aspose.html.dom.xpath/ixpathresult/snapshotlength/) El número de nodos en la instantánea del resultado. Los valores válidos para los índices de snapshotItem son `0` a `snapshotLength-1` inclusive. |
| [getStringValue](../../com.aspose.html.dom.xpath/ixpathresult/Stringvalue/) El valor de este resultado de cadena. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [iterateNext](../../com.aspose.html.dom.xpath/ixpathresult/iteratenext/)() | Itera y devuelve el siguiente nodo del conjunto de nodos o `null` si no hay más nodos. |
| [snapshotItem](../../com.aspose.html.dom.xpath/ixpathresult/snapshotitem/)(int) | Devuelve el elemento `index`‑ésimo de la colección de instantáneas. Si `index` es mayor o igual que el número de nodos en la lista, este método devuelve `null`. A diferencia del resultado del iterador, la instantánea no se invalida, pero puede no corresponder al documento actual si este se ha modificado. |

### Ver también

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
