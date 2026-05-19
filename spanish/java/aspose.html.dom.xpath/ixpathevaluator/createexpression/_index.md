---
title: "IXPathEvaluator.CreateExpression"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IXPathEvaluator. Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la expresión String en una forma interna más eficiente y preresolver todos los prefijos de paquetes que aparecen dentro de la expresión."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crea una expresión XPath analizada con paquetes resueltos. Esto es útil cuando una expresión se reutilizará en una aplicación, ya que permite compilar la cadena de expresión en una forma interna más eficiente y preresolver todos los prefijos de paquete que aparecen en la expresión.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expresión | String | La cadena de expresión XPath que se debe analizar. |
| resolver | IXPathNSResolver | El `resolver` permite la traducción de todos los prefijos, incluido el prefijo de paquete `xml`, dentro de la expresión XPath a URIs de paquete apropiados. Si se especifica como `null`, cualquier prefijo de paquete dentro de la expresión provocará que se lance [`DOMException`](../../../com.aspose.html.dom/domexception/) con el código `NAMESPACE_ERR`. |

### Valor de retorno

La forma compilada de la expresión XPath.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es válida según las reglas de [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Se genera si la expresión contiene prefijos de paquete que no pueden ser resueltos por el [`IXPathNSResolver`](../../ixpathnsresolver/) especificado. |

### Ver también

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
