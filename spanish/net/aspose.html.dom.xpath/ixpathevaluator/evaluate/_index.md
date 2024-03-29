---
title: IXPathEvaluator.Evaluate
second_title: Referencia de API de Aspose.HTML para .NET
description: IXPathEvaluator método. Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.
type: docs
weight: 30
url: /es/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evalúa una cadena de expresión XPath y devuelve un resultado del tipo especificado si es posible.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| expression | String | La cadena de expresión XPath que se analizará y evaluará. |
| contextNode | Node | El`contexto` es un nodo de contexto para la evaluación de esta expresión XPath . Si el[`IXPathEvaluator`](../) se obtuvo lanzando el [`Document`](../../../aspose.html.dom/document/) entonces este debe ser propiedad del mismo documento y debe ser un [`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , oXPathNamespace nodo. Si el nodo de contexto es un[`Text`](../../../aspose.html.dom/text/) o un [`CDATASection`](../../../aspose.html.dom/cdatasection/)el contexto se interpreta como el nodo de texto lógico completo tal como lo ve XPath, a menos que el nodo esté vacío, en cuyo caso puede que no sirva como contexto XPath. |
| resolver | IXPathNSResolver | El`resolver` permite la traducción de todos los prefijos, incluido el`xml` prefijo de espacio de nombres, dentro de la expresión XPath en los URI de espacio de nombres apropiados. Si esto se especifica como`nulo` , cualquier prefijo de espacio de nombres dentro de la expresión dará como resultado en[`DOMException`](../../../aspose.html.dom/domexception/) ser arrojado con el código`ESPACIO DE NOMBRES_ERR`. |
| type | XPathResultType | Si un especifico`tipo` se especifica, entonces el resultado se devolverá como el tipo correspondiente. Para los resultados de XPath 1.0, este debe ser uno de los valores de [`XPathResultType`](../../xpathresulttype/) enumeración |
| result | Object | El`resultado` especifica un objeto de resultado específico que puede ser reutilizado y devuelto por este método. Si esto se especifica como`nulo` la implementación no reutiliza el resultado especificado, se construirá y devolverá un nuevo objeto de resultado. Para los resultados de XPath 1.0 , este objeto será del tipo[`IXPathResult`](../../ixpathresult/). |

### Valor_devuelto

El resultado de la evaluación de la expresión XPath. Para los resultados de XPath 1.0, este objeto será del tipo[`IXPathResult`](../../ixpathresult/).

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Se genera si la expresión no es legal según a las reglas de la[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: se genera si el resultado no se puede convertir para devolver el tipo especificado . |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: se genera si la expresión contiene prefijos de espacio de nombres que no pueden ser resueltos por el especificado[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: El nodo es de un documento que no es compatible con este[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: el nodo no es un tipo permitido como un contexto XPath nodo o el tipo de solicitud no está permitido por este[`IXPathEvaluator`](../). |

### Ver también

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* espacio de nombres [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* asamblea [Aspose.HTML](../../../)


