---
title: "Interfaz IXPathNSResolver"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.xpath.IXPathNSResolver interface. La interfaz XPathNSResolver permite que las cadenas de prefijo en la expresión se vinculen correctamente a cadenas packageURI. IXPathEvaluator puede construir una implementación de IXPathNSResolver a partir de un nodo o la interfaz puede ser implementada por cualquier aplicación"
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathnsresolver/
---
## IXPathNSResolver interface

La interfaz `XPathNSResolver` permite que las cadenas `prefix` en la expresión se vinculen correctamente a las cadenas `packageURI`. [`IXPathEvaluator`](../ixpathevaluator/) puede construir una implementación de `IXPathNSResolver` a partir de un nodo, o la interfaz puede ser implementada por cualquier aplicación.

```java
public interface IXPathNSResolver
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [lookupNamespaceURI](../../com.aspose.html.dom.xpath/ixpathnsresolver/lookuppackageuri/)(String) | Busca el URI del paquete asociado al prefijo de paquete dado. El evaluador XPath nunca debe llamar a esto con un argumento `null` o vacío, porque el resultado de hacerlo es indefinido. |

### Ver también

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
