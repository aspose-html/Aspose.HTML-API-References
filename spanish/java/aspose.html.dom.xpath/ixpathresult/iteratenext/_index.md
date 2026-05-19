---
title: "IXPathResult.IterateNext"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IXPathResult. Itera y devuelve el siguiente nodo del conjunto de nodos o null si no hay más nodos"
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathresult/iteratenext/
---
## IXPathResult.IterateNext method

Itera y devuelve el siguiente nodo del conjunto de nodos o `null` si no hay más nodos.

```java
public Node IterateNext()
```

### Valor de retorno

Devuelve el siguiente nodo.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: se produce si `resultType` no es del tipo `UnorderedNodeIterator` o `OrderedNodeIterator`. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_STATE_ERR: El documento ha sido modificado desde que se devolvió el resultado. |

### Ver también

* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathResult](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
