---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML voor .NET API-referentie
description: IXPathEvaluator methode. Evalueert een XPathexpressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type.
type: docs
weight: 30
url: /nl/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evalueert een XPath-expressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De tekenreeks voor de XPath-expressie die moet worden geparseerd en geëvalueerd. |
| contextNode | Node | De`context` is contextknooppunt voor de evaluatie van deze XPath-expressie. Als de[`IXPathEvaluator`](../) werd verkregen door de te casten[`Document`](../../../aspose.html.dom/document/) dan moet dit eigendom zijn van hetzelfde document en moet het een zijn[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ofXPathNamespace knooppunt. Als het contextknooppunt een[`Text`](../../../aspose.html.dom/text/) of een [`CDATASection`](../../../aspose.html.dom/cdatasection/)dan wordt de context geïnterpreteerd als het hele logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is, in welk geval het mogelijk niet dient als de XPath-context. |
| resolver | IXPathNSResolver | De`oplosser` staat vertaling van alle prefixen toe, inclusief the`xml` naamruimtevoorvoegsel, binnen de XPath-expressie in de juiste naamruimte-URI's. Als dit is opgegeven als`nul` , zal elk naamruimtevoorvoegsel binnen de uitdrukking resulteren in [`DOMException`](../../../aspose.html.dom/domexception/) met de code worden gegooid`NAMESPACE_ERR`. |
| type | XPathResultType | Als een specifieke`type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. Voor XPath 1.0-resultaten moet dit een van de waarden zijn van de [`XPathResultType`](../../xpathresulttype/) opsomming. |
| result | Object | De`resultaat` specificeert een specifiek resultaatobject dat kan worden hergebruikt en geretourneerd door deze methode. Als dit is gespecificeerd als`nul`of de implementatie hergebruikt het opgegeven resultaat niet , een nieuw resultaatobject wordt geconstrueerd en geretourneerd. Voor XPath 1.0 resultaten zal dit object van het type zijn[`IXPathResult`](../../ixpathresult/). |

### Winstwaarde

Het resultaat van de evaluatie van de XPath-expressie. Voor XPath 1.0-resultaten zal dit object van het type zijn[`IXPathResult`](../../ixpathresult/).

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Verhoogd als de uitdrukking niet legaal is volgens volgens de regels van de[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: verhoogd als het resultaat niet kan worden geconverteerd om het door gespecificeerde type te retourneren. |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Verhoogd als de expressie naamruimtevoorvoegsels bevat die niet kunnen worden opgelost door de opgegeven[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: het knooppunt komt uit een document dat hierdoor niet wordt ondersteund[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: het knooppunt is geen type dat is toegestaan als een XPath-context -knooppunt of het verzoektype is hierdoor niet toegestaan[`IXPathEvaluator`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* naamruimte [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* montage [Aspose.HTML](../../../)


