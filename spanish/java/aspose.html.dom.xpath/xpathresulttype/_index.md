---
title: "Enumeración XPathResultType"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.xpath.XPathResultType enum. Un entero sin signo corto que indica qué tipo de resultado es. Si se especifica un tipo concreto, el resultado se devolverá como el tipo correspondiente usando conversiones de tipo XPath donde sea necesario y posible."
type: docs

url: /es/java/com.aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

Un entero corto sin signo que indica qué tipo de resultado es este. Si se especifica un `type` concreto, entonces el resultado se devolverá como el tipo correspondiente, utilizando conversiones de tipo XPath donde sea necesario y posible.

```java
public enum XPathResultType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Any | `0` | Este código no representa un tipo específico. La evaluación de una expresión XPath nunca producirá este tipo. Si se solicita este tipo, la evaluación devuelve el tipo que resulte naturalmente de la evaluación de la expresión. Si el resultado natural es un conjunto de nodos cuando se solicitó el tipo `Any`, entonces `UnorderedNodeIterator` siempre es el tipo resultante. Cualquier otra representación de un conjunto de nodos debe solicitarse explícitamente. |
| Number | `1` | El resultado es un número según lo definido por [XPath 1.0]. La modificación del documento no invalida el número, pero puede significar que una reevaluación no produzca el mismo número. |
| String | `2` | El resultado es una cadena según lo definido por [XPath 1.0]. La modificación del documento no invalida la cadena, pero puede significar que la cadena ya no corresponda al documento actual. |
| Boolean | `3` | El resultado es un booleano según lo definido por [XPath 1.0]. La modificación del documento no invalida el booleano, pero puede significar que una reevaluación no produzca el mismo booleano. |
| UnorderedNodeIterator | `4` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] que se accederá de forma iterativa, lo que puede no producir nodos en un orden particular. La modificación del documento invalida la iteración. Este es el tipo predeterminado que se devuelve si el resultado es un conjunto de nodos y se solicita el tipo `Any`. |
| OrderedNodeIterator | `5` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] que se accederá de forma iterativa, lo que producirá nodos ordenados según el documento. La modificación del documento invalida la iteración. |
| UnorderedNodeSnapshot | `6` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] que se accederá como una lista de instantánea de nodos que puede no estar en un orden particular. La modificación del documento no invalida la instantánea, pero puede significar que una reevaluación no produzca la misma instantánea y que los nodos en la instantánea hayan sido alterados, movidos o eliminados del documento. |
| OrderedNodeSnapshot | `7` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] que se accederá como una lista de instantánea de nodos que estarán en el orden original del documento. La modificación del documento no invalida la instantánea, pero puede significar que una reevaluación no produzca la misma instantánea y que los nodos en la instantánea hayan sido alterados, movidos o eliminados del documento. |
| AnyUnorderedNode | `8` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] y se accederá como un único nodo, que puede ser `null` si el conjunto de nodos está vacío. La modificación del documento no invalida el nodo, pero puede significar que el nodo resultante ya no corresponda al documento actual. Esto es una conveniencia que permite optimizar, ya que la implementación puede detenerse una vez que se haya encontrado cualquier nodo en el conjunto resultante. Si hay más de un nodo en el resultado real, el nodo único devuelto podría no ser el primero en el orden del documento. |
| FirstOrderedNode | `9` | El resultado es un conjunto de nodos según lo definido por [XPath 1.0] y se accederá como un único nodo, que puede ser `null` si el conjunto de nodos está vacío. La modificación del documento no invalida el nodo, pero puede significar que el nodo resultante ya no corresponda al documento actual. Esto es una conveniencia que permite optimizar, ya que la implementación puede detenerse una vez que se haya encontrado el primer nodo en el orden del documento del conjunto resultante. Si hay más de un nodo en el resultado real, el nodo único devuelto será el primero en el orden del documento. |

### Ver también

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
