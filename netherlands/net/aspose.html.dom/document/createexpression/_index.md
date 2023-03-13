---
title: Document.CreateExpression
second_title: Aspose.HTML voor .NET API-referentie
description: Document methode. Maakt een geparseerde XPathexpressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen.
type: docs
weight: 890
url: /nl/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Maakt een geparseerde XPath-expressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expression | String | De tekenreeks voor de XPath-expressie die moet worden geparseerd. |
| resolver | IXPathNSResolver | De`oplosser` staat de vertaling toe van alle voorvoegsels, inclusief de`xml` naamruimtevoorvoegsel, binnen de XPath-expressie in geschikte naamruimte-URI's. Als dit is gespecificeerd als`nul` , zal elke naamruimte prefix binnen de uitdrukking resulteren in[`DOMException`](../../domexception/) wordt gegooid met de code`NAMESPACE_ERR`. |

### Winstwaarde

De gecompileerde vorm van de XPath-expressie.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: verhoogd als de expressie niet legaal is volgens de regels van de[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Verhoogd als de expressie naamruimte prefixen bevat die niet kunnen worden opgelost door de opgegeven[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### Zie ook

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)


