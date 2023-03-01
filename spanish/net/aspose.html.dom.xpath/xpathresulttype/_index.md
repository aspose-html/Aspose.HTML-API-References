---
title: Enum XPathResultType
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.XPath.XPathResultType enumeración. Un corto sin firmar que indica qué tipo de resultado es este. Si un específicotipose especifica el resultado se devolverá como el tipo correspondiente utilizando conversiones de tipo XPath donde sea necesario y posible.
type: docs
weight: 2610
url: /es/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Un corto sin firmar que indica qué tipo de resultado es este. Si un específico`tipo`se especifica, el resultado se devolverá como el tipo correspondiente, utilizando conversiones de tipo XPath donde sea necesario y posible.

```csharp
public enum XPathResultType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Any | `0` | Este código no representa un tipo específico. Una evaluación de una expresión XPath nunca producirá este tipo. Si se solicita este tipo, la evaluación devuelve cualquier tipo que resulte naturalmente de la evaluación de la expresión. Si el resultado natural es un conjunto de nodos cuando`Cualquier` tipo fue solicitado, entonces`Iterador de nodo desordenado` es siempre el tipo resultante. Cualquier otra representación de un conjunto de nodos debe ser solicitada explícitamente. |
| Number | `1` | El resultado es un número definido por [XPath 1.0]. La modificación del documento no invalida el número, pero puede significar que la reevaluación no produciría el mismo número. |
| String | `2` | El resultado es una cadena definida por [XPath 1.0]. La modificación del documento no invalida la cadena, pero puede significar que la cadena ya no corresponde al documento actual. |
| Boolean | `3` | El resultado es un valor booleano definido por [XPath 1.0]. La modificación del documento no invalida el booleano, pero puede significar que la reevaluación no produciría el mismo booleano. |
| UnorderedNodeIterator | `4` | El resultado es un conjunto de nodos definido por [XPath 1.0] al que se accederá de manera iterativa, que puede no producir nodos en un orden particular. La modificación del documento invalida la iteración . Este es el tipo predeterminado devuelto si el resultado es un conjunto de nodos y`Cualquier` Se solicita el tipo . |
| OrderedNodeIterator | `5` | El resultado es un conjunto de nodos definido por [XPath 1.0] al que se accederá de forma iterativa, que producirá nodos ordenados por documentos. La modificación del documento invalida la iteración. |
| UnorderedNodeSnapshot | `6` | El resultado es un conjunto de nodos definido por [XPath 1.0] al que se accederá como una instantánea lista de nodos que pueden no estar en un orden particular. La modificación del documento no invalida la instantánea, pero puede significar que la reevaluación no generará la misma instantánea y que los nodos de la instantánea pueden haber sido alterados, movidos o eliminados del documento. |
| OrderedNodeSnapshot | `7` | El resultado es un conjunto de nodos definido por [XPath 1.0] al que se accederá como una instantánea lista de nodos que estarán en el orden del documento original. La modificación del documento no invalida la instantánea, pero puede significar que la reevaluación no generará la misma instantánea y que los nodos de la instantánea pueden haber sido alterados, movidos o eliminados del documento. |
| AnyUnorderedNode | `8` | El resultado es un conjunto de nodos definido por [XPath 1.0] y se accederá como un solo nodo, que puede ser`nulo`si el conjunto de nodos está vacío. La modificación del documento no invalida el nodo, pero puede significar que el nodo de resultado ya no corresponde al documento actual. Esta es una conveniencia que permite la optimización ya que la implementación puede detenerse una vez que se haya encontrado cualquier nodo en el conjunto resultante. Si hay más de un nodo en el resultado real, es posible que el único nodo devuelto no sea el primero en el orden del documento. |
| FirstOrderedNode | `9` | El resultado es un conjunto de nodos definido por [XPath 1.0] y se accederá como un solo nodo, que puede ser`nulo`si el conjunto de nodos está vacío. La modificación del documento no invalida el nodo, pero puede significar que el nodo de resultado ya no corresponde al documento actual. Esta es una conveniencia que permite la optimización ya que la implementación puede detenerse una vez que se ha encontrado el primer nodo en el orden del documento del conjunto resultante. Si hay más de un nodo en el resultado real, el único nodo devuelto será el primero en el orden del documento. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* asamblea [Aspose.HTML](../../)


