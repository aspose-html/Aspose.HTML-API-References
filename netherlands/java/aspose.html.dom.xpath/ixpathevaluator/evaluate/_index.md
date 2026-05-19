---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IXPathEvaluator-methode. Evalueert een XPath‑expressie‑String en retourneert een resultaat van het opgegeven type indien mogelijk."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Evalueert een XPath‑expressie‑String en retourneert, indien mogelijk, een resultaat van het opgegeven type.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expressie | String | De XPath‑expressie‑String die moet worden geparseerd en geëvalueerd. |
| contextNode | Node | De `context` is het contextknooppunt voor de evaluatie van deze XPath‑expressie. Als de [`IXPathEvaluator`](../) is verkregen door het casten van het [`Document`](../../../com.aspose.html.dom/document/), dan moet dit eigendom zijn van hetzelfde document en moet het een [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) of XPathNamespace‑knooppunt zijn. Als het contextknooppunt een [`Text`](../../../com.aspose.html.dom/text/) of een [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) is, dan wordt de context geïnterpreteerd als het volledige logische tekstknooppunt zoals gezien door XPath, tenzij het knooppunt leeg is, in welk geval het niet als XPath‑context kan dienen. |
| resolver | IXPathNSResolver | De `resolver` staat vertaling van alle prefixen toe, inclusief de `xml`-pakketprefix, binnen de XPath‑expressie naar de juiste pakket‑URI's. Als dit wordt opgegeven als `null`, zal elke pakket‑prefix in de expressie resulteren in een [`DOMException`](../../../com.aspose.html.dom/domexception/) met de code `NAMESPACE_ERR`. |
| type | XPathResultType | Als een specifiek `type` is opgegeven, wordt het resultaat geretourneerd als het overeenkomstige type. Voor XPath 1.0‑resultaten moet dit een van de waarden van de [`XPathResultType`](../../xpathresulttype/)‑enum zijn. |
| result | Object | De `result` geeft een specifiek resultaatobject aan dat door deze methode kan worden hergebruikt en geretourneerd. Als dit is opgegeven als `null` of de implementatie het opgegeven resultaat niet hergebruikt, wordt een nieuw resultaatobject geconstrueerd en geretourneerd. Voor XPath 1.0-resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn. |

### Retourwaarde

Het resultaat van de evaluatie van de XPath-expressie. Voor XPath 1.0-resultaten zal dit object van het type [`IXPathResult`](../../ixpathresult/) zijn.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Opgeworpen als de expressie niet geldig is volgens de regels van de [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Opgeworpen als het resultaat niet kan worden geconverteerd naar het opgegeven type. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Opgeworpen als de expressie pakket‑prefixen bevat die niet kunnen worden opgelost door de opgegeven [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Het knooppunt komt uit een document dat niet wordt ondersteund door deze [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Het knooppunt is geen type dat is toegestaan als XPath‑contextknooppunt of het aangevraagde type is niet toegestaan door deze [`IXPathEvaluator`](../). |

### Zie ook

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
