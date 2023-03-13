---
title: Interface IXPathEvaluator
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.XPath.IXPathEvaluator interfaz. La evaluación de las expresiones XPath la proporcionaIXPathEvaluator .
type: docs
weight: 2560
url: /es/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

La evaluación de las expresiones XPath la proporciona`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación, ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adapta cualquier nodo DOM para resolver espacios de nombres de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método DOM Nivel 3`lookupNamespaceURI` en los nodos para resolver el namespaceURI de un prefijo dado usando la información actual disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, también resolviendo correctamente el prefijo xml implícito. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* asamblea [Aspose.HTML](../../)


