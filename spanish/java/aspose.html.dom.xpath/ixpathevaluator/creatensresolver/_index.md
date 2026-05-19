---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IXPathEvaluator. Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método lookupNamespaceURI del DOM Level 3 en los nodos, resolviendo el packageURI a partir de un prefijo dado usando la información disponible en la jerarquía de nodos en el momento en que se llama a lookupNamespaceURI, y también resolviendo correctamente el prefijo implícito xml."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método de DOM Level 3 `lookupNamespaceURI` en los nodos para resolver el packageURI a partir de un prefijo dado usando la información disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, resolviendo también correctamente el prefijo implícito xml.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeResolver | Node | El nodo que se utilizará como contexto para la resolución de paquetes. |

### Valor de retorno

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Ver también

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
