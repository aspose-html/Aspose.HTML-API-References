---
title: IXPathEvaluator.CreateNSResolver
second_title: Referencia de API de Aspose.HTML para .NET
description: IXPathEvaluator método. Adapta cualquier nodo DOM para resolver espacios de nombres de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método DOM Nivel 3lookupNamespaceURI en los nodos para resolver el namespaceURI de un prefijo dado usando la información actual disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI también resolviendo correctamente el prefijo xml implícito.
type: docs
weight: 20
url: /es/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Adapta cualquier nodo DOM para resolver espacios de nombres de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método DOM Nivel 3`lookupNamespaceURI` en los nodos para resolver el namespaceURI de un prefijo dado usando la información actual disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, también resolviendo correctamente el prefijo xml implícito.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| nodeResolver | Node | El nodo que se utilizará como contexto para la resolución del espacio de nombres. |

### Valor_devuelto

[`IXPathNSResolver`](../../ixpathnsresolver/) que resuelve los espacios de nombres con respecto a las definiciones en el ámbito de un nodo especificado.

### Ver también

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* espacio de nombres [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* asamblea [Aspose.HTML](../../../)


