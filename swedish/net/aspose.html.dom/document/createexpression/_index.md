---
title: Document.CreateExpression
second_title: Aspose.HTML för .NET API Referens
description: Document metod. Skapar ett tolkat XPathuttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket.
type: docs
weight: 890
url: /sv/net/aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Skapar ett tolkat XPath-uttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket.

```csharp
public IXPathExpression CreateExpression(string expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttryckssträngen som ska tolkas. |
| resolver | IXPathNSResolver | De`resolver` tillåter översättning av alla prefix, inklusive`xml` namnområdesprefix, inom XPath-uttrycket till lämpliga namnområdes-URI:er. Om detta anges som`null` , kommer alla namnområde prefix i uttrycket att resultera i[`DOMException`](../../domexception/) kastas med koden`NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath-uttrycket.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Ökas om uttrycket inte är lagligt enligt reglerna i[`IXPathEvaluator`](../../../aspose.html.dom.xpath/ixpathevaluator/). |
| [DOMException](../../domexception/) | NAMESPACE_ERR: Ökas om uttrycket innehåller namnutrymmet prefix som inte kan lösas av den angivna[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../../aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)


