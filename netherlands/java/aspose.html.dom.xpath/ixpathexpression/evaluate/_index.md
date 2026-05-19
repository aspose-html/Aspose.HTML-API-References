---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IXPathExpression methode. Evalueert deze XPath-expressie en retourneert een resultaat"
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Evalueert deze XPath-expressie en retourneert een resultaat.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contextNode | Node | De `context` is het contextknooppunt voor de evaluatie van deze XPath-expressie. Als de [`IXPathEvaluator`](../../ixpathevaluator/) is verkregen door het casten van het [`Document`](../../../com.aspose.html.dom/document/), dan moet dit eigendom zijn van hetzelfde document en moet het een [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/), of XPathNamespace-knooppunt zijn. Als het contextknooppunt een [`Text`](../../../com.aspose.html.dom/text/) of een [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) is, dan wordt de context geïnterpreteerd als het volledige logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is, in welk geval het niet als XPath-context kan dienen. |
| type | XPathResultType | Als een specifiek `type` is opgegeven, wordt het resultaat omgezet om het opgegeven type te retourneren, gebruikmakend van XPath-conversies, en mislukt als de gewenste conversie niet mogelijk is. Dit moet een van de waarden van [`XPathResultType`](../../xpathresulttype/) zijn. |
| result | Object | De `result` geeft een specifiek resultaatobject aan dat door deze methode kan worden hergebruikt en geretourneerd. Als dit is opgegeven als `null` of de implementatie het opgegeven resultaat niet hergebruikt, wordt een nieuw resultaatobject geconstrueerd en geretourneerd. Voor XPath 1.0-resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath-expressie. Voor XPath 1.0-resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Opgeworpen als het resultaat niet kan worden geconverteerd naar het opgegeven type. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Het knooppunt komt uit een document dat niet wordt ondersteund door de [`IXPathEvaluator`](../../ixpathevaluator/) die deze [`IXPathExpression`](../) heeft gemaakt. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Het knooppunt is geen type dat is toegestaan als XPath-contextknooppunt of het verzoektype is niet toegestaan door deze [`IXPathExpression`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
