---
title: "IXPathExpression.Evaluate"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IXPathExpression. Evalúa esta expresión XPath y devuelve un resultado."
type: docs

url: /es/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evalúa esta expresión XPath y devuelve un resultado.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| contextNode | Node | El `context` es el nodo de contexto para la evaluación de esta expresión XPath. Si el [`IXPathEvaluator`](../../ixpathevaluator/) se obtuvo mediante casting del [`Document`](../../../com.aspose.html.dom/document/), entonces debe pertenecer al mismo documento y debe ser un [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), o un nodo XPathNamespace. Si el nodo de contexto es un [`Text`](../../../com.aspose.html.dom/text/) o un [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), entonces el contexto se interpreta como todo el nodo de texto lógico visto por XPath, a menos que el nodo esté vacío, en cuyo caso no puede servir como contexto XPath. |
| type | XPathResultType | Si se especifica un `type` concreto, entonces el resultado se coercionará para devolver el tipo especificado basándose en conversiones XPath y fallará si la coerción deseada no es posible. Esto debe ser uno de los valores de [`XPathResultType`](../../xpathresulttype/). |
| result | Object | El `result` especifica un objeto de resultado concreto que puede ser reutilizado y devuelto por este método. Si se especifica como `null` o la implementación no reutiliza el resultado especificado, se construirá y devolverá un nuevo objeto de resultado. Para resultados XPath 1.0, este objeto será del tipo [`IXPathResult`](../../ixpathresult/). |

### Valor de retorno

El resultado de la evaluación de la expresión XPath. Para resultados XPath 1.0, este objeto será del tipo [`IXPathResult`](../../ixpathresult/).

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Se produce si el resultado no puede convertirse para devolver el tipo especificado. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: El Nodo proviene de un documento que no es compatible con el [`IXPathEvaluator`](../../ixpathevaluator/) que creó este [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: El Nodo no es un tipo permitido como nodo de contexto XPath o el tipo de solicitud no está permitido por este [`IXPathExpression`](../). |

### Ver también

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
