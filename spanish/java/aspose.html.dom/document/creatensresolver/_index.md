---
title: "Document.CreateNSResolver"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Document método. Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método de nivel 3 del DOM lookupNamespaceURI en los nodos para resolver el packageURI a partir de un prefijo dado usando la información disponible actualmente en la jerarquía de los nodos en el momento en que se llama a lookupNamespaceURI, también resolviendo correctamente el prefijo implícito xml"
type: docs

url: /es/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método de DOM Level 3 `lookupNamespaceURI` en los nodos para resolver el packageURI a partir de un prefijo dado usando la información disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, resolviendo también correctamente el prefijo implícito xml.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeResolver | Node | El nodo que se utilizará como contexto para la resolución de paquetes. |

### Valor de retorno

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Ver también

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
