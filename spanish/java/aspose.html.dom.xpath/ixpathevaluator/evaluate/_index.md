---
title: "IXPathEvaluator.Evaluate"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IXPathEvaluator. Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expresión | String | La cadena de expresión XPath que se debe analizar y evaluar. |
| contextNode | Node | El `context` es el nodo de contexto para la evaluación de esta expresión XPath. Si el [`IXPathEvaluator`](../) se obtuvo mediante un casting del [`Document`](../../../com.aspose.html.dom/document/), entonces este debe pertenecer al mismo documento y debe ser un [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), o un nodo XPathNamespace. Si el nodo de contexto es un [`Text`](../../../com.aspose.html.dom/text/) o un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), entonces el contexto se interpreta como todo el nodo de texto lógico visto por XPath, a menos que el nodo esté vacío, en cuyo caso no podrá servir como contexto XPath. |
| resolver | IXPathNSResolver | El `resolver` permite la traducción de todos los prefijos, incluido el prefijo de paquete `xml`, dentro de la expresión XPath a URIs de paquete apropiados. Si se especifica como `null`, cualquier prefijo de paquete dentro de la expresión provocará que se lance [`DOMException`](../../../com.aspose.html.dom/domexception/) con el código `NAMESPACE_ERR`. |
| type | XPathResultType | Si se especifica un `type` concreto, el resultado se devolverá como el tipo correspondiente. Para resultados de XPath 1.0, esto debe ser uno de los valores del enum [`XPathResultType`](../../xpathresulttype/). |
| result | Object | El `result` especifica un objeto de resultado concreto que puede ser reutilizado y devuelto por este método. Si se especifica como `null` o la implementación no reutiliza el resultado especificado, se construirá y devolverá un nuevo objeto de resultado. Para resultados XPath 1.0, este objeto será del tipo [`IXPathResult`](../../ixpathresult/). |

### Valor de retorno

El resultado de la evaluación de la expresión XPath. Para resultados XPath 1.0, este objeto será del tipo [`IXPathResult`](../../ixpathresult/).

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es válida según las reglas de [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Se produce si el resultado no puede convertirse para devolver el tipo especificado. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Se genera si la expresión contiene prefijos de paquete que no pueden ser resueltos por el [`IXPathNSResolver`](../../ixpathnsresolver/) especificado. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: El nodo proviene de un documento que no es compatible con este [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: El nodo no es un tipo permitido como nodo de contexto XPath o el tipo de solicitud no está permitido por este [`IXPathEvaluator`](../). |

### Ver también

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
