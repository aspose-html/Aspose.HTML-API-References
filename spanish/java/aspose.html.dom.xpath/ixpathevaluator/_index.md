---
title: "Interfaz IXPathEvaluator"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.xpath.IXPathEvaluator interface. La evaluación de expresiones XPath es proporcionada por IXPathEvaluator"
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

La evaluación de expresiones XPath es proporcionada por `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la cadena de expresión en una forma interna más eficiente y preresolver todos los prefijos de paquete que aparecen en la expresión. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Adapta cualquier nodo DOM para resolver paquetes de modo que una expresión XPath pueda evaluarse fácilmente en relación con el contexto del nodo donde apareció dentro del documento. Este adaptador funciona como el método de DOM Level 3 `lookupNamespaceURI` en los nodos para resolver el packageURI a partir de un prefijo dado usando la información disponible en la jerarquía del nodo en el momento en que se llama a lookupNamespaceURI, resolviendo también correctamente el prefijo implícito xml. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible. |

### Ver también

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
