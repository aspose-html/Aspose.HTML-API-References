---
title: IXPathEvaluator.CreateExpression
second_title: Aspose.HTML för .NET API Referens
description: IXPathEvaluator metod. Skapar ett tolkat XPathuttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Skapar ett tolkat XPath-uttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttryckssträngen som ska tolkas. |
| resolver | IXPathNSResolver | De`resolver` tillåter översättning av alla prefix, inklusive`xml` namnområdesprefix, inom XPath-uttrycket till lämpliga namnområdes-URI:er. Om detta anges som`null` , kommer alla namnområde prefix i uttrycket att resultera i[`DOMException`](../../../aspose.html.dom/domexception/) kastas med koden`NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath-uttrycket.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Ökas om uttrycket inte är lagligt enligt reglerna i[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Ökas om uttrycket innehåller namnutrymmet prefix som inte kan lösas av den angivna[`IXPathNSResolver`](../../ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* namnutrymme [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* hopsättning [Aspose.HTML](../../../)


