---
title: "IXPathEvaluator.Evaluate"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathEvaluator‑metod. Utvärderar en XPath‑uttrycksssträng och returnerar ett resultat av den angivna typen om möjligt."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Utvärderar en XPath‑uttryck‑String och returnerar ett resultat av den angivna typen om möjligt.

```java
public IXPathResult Evaluate(String expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uttryck | String | XPath‑uttrycksssträngen som ska parsas och utvärderas. |
| contextNode | Node | `context` är kontextnod för utvärderingen av detta XPath‑uttryck. Om [`IXPathEvaluator`](../) erhölls genom att kasta [`Document`](../../../com.aspose.html.dom/document/) måste detta ägas av samma dokument och vara ett [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) eller XPathNamespace‑nod. Om kontextnoden är ett [`Text`](../../../com.aspose.html.dom/text/) eller ett [`CDATASection`](../../../com.aspose.html.dom/cdatasection/) tolkas kontexten som hela den logiska textnoden som XPath ser, såvida inte noden är tom, vilket då kan göra att den inte kan användas som XPath‑kontext. |
| resolver | IXPathNSResolver | `resolver` tillåter översättning av alla prefix, inklusive `xml`‑paketprefixet, inom XPath‑uttrycket till lämpliga paket‑URI:er. Om detta anges som `null` kommer alla paketprefix i uttrycket att leda till att [`DOMException`](../../../com.aspose.html.dom/domexception/) kastas med koden `NAMESPACE_ERR`. |
| type | XPathResultType | Om en specifik `type` anges, kommer resultatet att returneras som motsvarande typ. För XPath 1.0‑resultat måste detta vara ett av värdena i enum‑typen [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` anger ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. Om detta anges som `null` eller om implementationen inte återanvänder det angivna resultatet, kommer ett nytt resultatobjekt att skapas och returneras. För XPath 1.0-resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath-uttrycket. För XPath 1.0-resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Uppstår om uttrycket inte är giltigt enligt reglerna för [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Uppstår om resultatet inte kan konverteras för att returnera den angivna typen. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NAMESPACE_ERR: Uppstår om uttrycket innehåller paketprefix som inte kan lösas upp av den angivna [`IXPathNSResolver`](../../ixpathnsresolver/). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden kommer från ett dokument som inte stöds av denna [`IXPathEvaluator`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte av en typ som tillåts som XPath‑kontextnod eller så är den begärda typen inte tillåten av denna [`IXPathEvaluator`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
