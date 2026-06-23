---
title: "IXPathEvaluator.CreateExpression"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathEvaluator‑metod. Skapar ett parsat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathevaluator/createexpression/
---
## IXPathEvaluator.CreateExpression method

Skapar ett parsat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uttryck | String | XPath‑uttrycksssträngen som ska parsas. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑paketprefixet, inom XPath‑uttrycket till lämpliga paket‑URI:er. Om detta anges som `null` kommer alla paketprefix i uttrycket att leda till att [`DOMException`](../../../com.aspose.html.dom/domexception/) kastas med koden `NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath‑uttrycket.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Uppstår om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Uppstår om uttrycket innehåller paketprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../ixpathexpression/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
