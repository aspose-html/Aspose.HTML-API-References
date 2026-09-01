---
title: "IXPathExpression.Evaluate"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathExpression-metod. Utvärderar detta XPath-uttryck och returnerar ett resultat."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Utvärderar detta XPath-uttryck och returnerar ett resultat.

```java
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contextNode | Node | `context` är kontextnod för utvärderingen av detta XPath-uttryck. Om [`IXPathEvaluator`](../../ixpathevaluator/) erhölls genom att kasta [`Document`](../../../com.aspose.html.dom/document/) måste den ägas av samma dokument och måste vara ett [`Document`](../../../com.aspose.html.dom/document/), [`Element`](../../../com.aspose.html.dom/element/), [`Attr`](../../../com.aspose.html.dom/attr/), [`Text`](../../../com.aspose.html.dom/text/), [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), [`Comment`](../../../com.aspose.html.dom/comment/), [`ProcessingInstruction`](../../../com.aspose.html.dom/processinginstruction/) eller XPathNamespace-nod. Om kontextnoden är ett [`Text`](../../../com.aspose.html.dom/text/) eller en [`CDATASection`](../../../com.aspose.html.dom/cdatasection/), tolkas kontexten som hela den logiska textnoden som ses av XPath, såvida inte noden är tom, i så fall kan den inte fungera som XPath-kontext. |
| type | XPathResultType | Om en specifik `type` anges, kommer resultatet att tvingas till den angivna typen med hjälp av XPath-omvandlingar och misslyckas om den önskade omvandlingen inte är möjlig. Detta måste vara ett av värdena i [`XPathResultType`](../../xpathresulttype/). |
| result | Object | `result` anger ett specifikt resultatobjekt som kan återanvändas och returneras av denna metod. Om detta anges som `null` eller om implementationen inte återanvänder det angivna resultatet, kommer ett nytt resultatobjekt att skapas och returneras. För XPath 1.0-resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath-uttrycket. För XPath 1.0-resultat kommer detta objekt att vara av typen [`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | TYPE_ERR: Uppstår om resultatet inte kan konverteras för att returnera den angivna typen. |
| [dOMException](../../../com.aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden kommer från ett dokument som inte stöds av den [`IXPathEvaluator`](../../ixpathevaluator/) som skapade detta [`IXPathExpression`](../). |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte av en typ som tillåts som XPath-kontextnod eller så är begäranstypen inte tillåten av detta [`IXPathExpression`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../com.aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
