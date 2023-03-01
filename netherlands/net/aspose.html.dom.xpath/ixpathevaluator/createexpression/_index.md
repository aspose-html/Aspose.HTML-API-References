---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML voor .NET API-referentie
description: IXPathEvaluator methode. Maakt een geparseerde XPathexpressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Maakt een geparseerde XPath-expressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De tekenreeks voor de XPath-expressie die moet worden geparseerd. |
| resolver | IXPathNSResolver | De`oplosser` staat de vertaling toe van alle voorvoegsels, inclusief de`xml` naamruimtevoorvoegsel, binnen de XPath-expressie in geschikte naamruimte-URI's. Als dit is gespecificeerd als`nul` , zal elke naamruimte prefix binnen de uitdrukking resulteren in[`DOMException`](../../../aspose.html.dom/domexception/) wordt gegooid met de code`NAMESPACE_ERR`. |

### Winstwaarde

De gecompileerde vorm van de XPath-expressie.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: verhoogd als de expressie niet legaal is volgens de regels van de[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Verhoogd als de expressie naamruimte prefixen bevat die niet kunnen worden opgelost door de opgegeven[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* naamruimte [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* montage [Aspose.HTML](../../../)


