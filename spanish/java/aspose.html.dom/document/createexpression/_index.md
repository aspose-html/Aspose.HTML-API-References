---
title: "Document.CreateExpression"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del documento. Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la cadena de expresión en una forma interna más eficiente y preresolver todos los prefijos de paquetes que aparecen dentro de la expresión."
type: docs

url: /es/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la cadena de expresión en una forma interna más eficiente y preresolver todos los prefijos de paquete que aparecen en la expresión.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expresión | Cadena | La cadena de expresión XPath que se analizará. |
| resolver | IXPathNSResolver | El `resolver` permite la traducción de todos los prefijos, incluido el prefijo de paquete `xml`, dentro de la expresión XPath a URIs de paquete apropiados. Si se especifica como `null`, cualquier prefijo de paquete dentro de la expresión provocará que se lance una [`DOMException`](../../domexception/) con el código `NAMESPACE_ERR`. |

### Valor devuelto

La forma compilada de la expresión XPath.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es legal según las reglas del [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Se genera si la expresión contiene prefijos de paquete que no pueden ser resueltos por el [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) especificado. |

### Ver también

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
