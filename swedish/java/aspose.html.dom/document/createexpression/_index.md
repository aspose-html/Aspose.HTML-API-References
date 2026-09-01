---
title: "Document.CreateExpression"
second_title: "Aspose.HTML för Java API-referens"
description: "Dokumentmetod. Skapar ett analyserat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck kommer att återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket."
type: docs

url: /sv/java/com.aspose.html.dom/document/createexpression/
---
## Document.CreateExpression method

Skapar ett parsat XPath‑uttryck med upplösta paket. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det möjliggör att kompilera uttrycksssträngen till en mer effektiv intern form och förupplösa alla paketprefix som förekommer i uttrycket.

```java
public IXPathExpression CreateExpression(String expression, IXPathNSResolver resolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uttryck | String | XPath‑uttrycksssträngen som ska parsas. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑paketprefixet, inom XPath‑uttrycket till lämpliga paket‑URI:er. Om detta anges som `null` kommer vilket paketprefix som helst i uttrycket att resultera i att [`DOMException`](../../domexception/) kastas med koden `NAMESPACE_ERR`. |

### Returvärde

Den kompilerade formen av XPath‑uttrycket.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | INVALID_EXPRESSION_ERR: Utlöses om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../../../com.aspose.html.dom.xpath/ixpathevaluator/). |
| [dOMException](../../domexception/) | NAMESPACE_ERR: Utlöses om uttrycket innehåller paketprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/). |

### Se även

* interface [IXPathExpression](../../../com.aspose.html.dom.xpath/ixpathexpression/)
* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
