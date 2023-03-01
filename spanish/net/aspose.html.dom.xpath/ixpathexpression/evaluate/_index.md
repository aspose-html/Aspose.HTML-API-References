---
title: IXPathExpression.Evaluate
second_title: Referencia de API de Aspose.HTML para .NET
description: IXPathExpression método. Evalúa esta expresión XPath y devuelve un resultado.
type: docs
weight: 10
url: /es/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evalúa esta expresión XPath y devuelve un resultado.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| contextNode | Node | El`contexto` es un nodo de contexto para la evaluación de esta expresión XPath. Si el[`IXPathEvaluator`](../../ixpathevaluator/) se obtuvo echando el[`Document`](../../../aspose.html.dom/document/) entonces esto debe ser propiedad del mismo documento y debe ser un[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oXPathNamespace nodo. Si el nodo de contexto es un[`Text`](../../../aspose.html.dom/text/) o un[`CDATASection`](../../../aspose.html.dom/cdatasection/), , el contexto se interpreta como el nodo de texto lógico completo tal como lo ve XPath, a menos que el nodo esté vacío , en cuyo caso es posible que no sirva como contexto XPath. |
| type | XPathResultType | Si un especifico`tipo` se especifica, entonces el resultado será obligado a devolver el tipo especificado basándose en las conversiones de XPath y fallará si la coerción deseada no es posible. Este debe ser uno de los valores de[`XPathResultType`](../../xpathresulttype/). |
| result | Object | El`resultado` especifica un objeto de resultado específico que puede ser reutilizado y devuelto por este método. Si esto se especifica como`nulo` la implementación no reutiliza el resultado especificado, se construirá y devolverá un nuevo objeto de resultado. Para los resultados de XPath 1.0, este objeto será de tipo[`IXPathResult`](../../ixpathresult/). |

### Valor_devuelto

El resultado de la evaluación de la expresión XPath. Para los resultados de XPath 1.0, este objeto será de tipo[`IXPathResult`](../../ixpathresult/).

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: se genera si el resultado no se puede convertir para devolver el tipo especificado. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: El nodo es de un documento que no es compatible con el[`IXPathEvaluator`](../../ixpathevaluator/) que creó esto[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: el nodo no es un tipo permitido como nodo de contexto XPath o el tipo de solicitud no está permitido por este[`IXPathExpression`](../). |

### Ver también

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* espacio de nombres [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* asamblea [Aspose.HTML](../../../)


