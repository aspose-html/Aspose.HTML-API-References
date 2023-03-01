---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML voor .NET API-referentie
description: IXPathExpression methode. Evalueert deze XPathexpressie en retourneert een resultaat.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evalueert deze XPath-expressie en retourneert een resultaat.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contextNode | Node | De`context` is contextknooppunt voor de evaluatie van deze XPath-expressie. Als de[`IXPathEvaluator`](../../ixpathevaluator/) werd verkregen door het gieten van de[`Document`](../../../aspose.html.dom/document/) dan moet dit eigendom zijn van hetzelfde document en moet het een[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ofXPathNamespace knooppunt. Als het contextknooppunt een[`Text`](../../../aspose.html.dom/text/) of een[`CDATASection`](../../../aspose.html.dom/cdatasection/), dan wordt de context geïnterpreteerd als het hele logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is , in welk geval het niet kan dienen als de XPath-context. |
| type | XPathResultType | Als een specifieke`type` is opgegeven, wordt het resultaat gedwongen om het door gespecificeerde type te retourneren op basis van XPath-conversies en mislukt het als de gewenste dwang niet mogelijk is. Dit moet een van de waarden zijn van[`XPathResultType`](../../xpathresulttype/). |
| result | Object | De`resultaat` specificeert een specifiek resultaatobject dat door deze methode opnieuw kan worden gebruikt en kan worden geretourneerd. Als dit is gespecificeerd als`nul`of de implementatie gebruikt het gespecificeerde resultaat niet opnieuw, een nieuw resultaatobject wordt geconstrueerd en geretourneerd. Voor XPath 1.0-resultaten is dit object van het type[`IXPathResult`](../../ixpathresult/). |

### Winstwaarde

Het resultaat van de evaluatie van de XPath-expressie. Voor XPath 1.0-resultaten is dit object van het type[`IXPathResult`](../../ixpathresult/).

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: verhoogd als het resultaat niet kan worden geconverteerd om het opgegeven type te retourneren. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: het knooppunt komt uit een document dat niet wordt ondersteund door de[`IXPathEvaluator`](../../ixpathevaluator/) die dit heeft gemaakt[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: het knooppunt is geen type dat is toegestaan als een XPath-contextknooppunt of het verzoektype is hierdoor niet toegestaan[`IXPathExpression`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* naamruimte [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* montage [Aspose.HTML](../../../)


