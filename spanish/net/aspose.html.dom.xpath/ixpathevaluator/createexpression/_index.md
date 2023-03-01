---
title: IXPathEvaluator.CreateExpression
second_title: Referencia de API de Aspose.HTML para .NET
description: IXPathEvaluator método. Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión.
type: docs
weight: 10
url: /es/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Crea una expresión XPath analizada con espacios de nombres resueltos. Esto es útil cuando se va a reutilizar una expresión en una aplicación, ya que permite compilar la cadena de expresión en un formato interno más eficiente y preresolver todos los prefijos de espacio de nombres que se producen dentro de la expresión.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expression | String | La cadena de expresión XPath que se va a analizar. |
| resolver | IXPathNSResolver | El`resolver` permite la traducción de todos los prefijos, incluido el`xml` prefijo de espacio de nombres, dentro de la expresión XPath en URI de espacio de nombres apropiados. Si esto se especifica como`nulo` , cualquier prefijo de espacio de nombres dentro de la expresión dará como resultado[`DOMException`](../../../aspose.html.dom/domexception/) siendo arrojado con el código`ESPACIO DE NOMBRES_ERR`. |

### Valor_devuelto

La forma compilada de la expresión XPath.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es legal de acuerdo con las reglas de la[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: se genera si la expresión contiene prefijos de espacio de nombres que no pueden ser resueltos por el especificado[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Ver también

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* espacio de nombres [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* asamblea [Aspose.HTML](../../../)


