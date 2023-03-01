---
title: IXPathExpression.Evaluate
second_title: Aspose.HTML för .NET API Referens
description: IXPathExpression metod. Utvärderar detta XPathuttryck och returnerar ett resultat.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.xpath/ixpathexpression/evaluate/
---
## IXPathExpression.Evaluate method

Utvärderar detta XPath-uttryck och returnerar ett resultat.

```csharp
public IXPathResult Evaluate(Node contextNode, XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contextNode | Node | De`sammanhang` är kontextnod för utvärderingen av detta XPath-uttryck. Om[`IXPathEvaluator`](../../ixpathevaluator/) erhölls genom gjutning av[`Document`](../../../aspose.html.dom/document/) då måste detta ägas av samma dokument och måste vara en[`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) , [`Text`](../../../aspose.html.dom/text/) ,[`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ellerXPathNamespace nod. Om kontextnoden är en[`Text`](../../../aspose.html.dom/text/) eller a[`CDATASection`](../../../aspose.html.dom/cdatasection/), då tolkas kontexten som hela den logiska textnoden som den ses av XPath, om inte noden är tom i vilket fall den kanske inte fungerar som XPath-kontext. |
| type | XPathResultType | Om en specifik`typ` anges, kommer resultatet att tvingas att returnera den specificerade typen som förlitar sig på XPath-konverteringar och misslyckas om det önskade tvånget inte är möjligt. Detta måste vara ett av värdena för[`XPathResultType`](../../xpathresulttype/). |
| result | Object | De`resultat` anger ett specifikt resultatobjekt som kan återanvändas och returneras med den här metoden. Om detta anges som`null`eller att implementeringen inte återanvänder det angivna -resultatet, kommer ett nytt resultatobjekt att konstrueras och returneras. För XPath 1.0-resultat kommer detta objekt att vara av typen[`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath-uttrycket. För XPath 1.0-resultat kommer detta objekt att vara av typen[`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Ökas om resultatet inte kan konverteras för att returnera den angivna typen. |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden är från ett dokument som inte stöds av [`IXPathEvaluator`](../../ixpathevaluator/) som skapade detta[`IXPathExpression`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte en typ som är tillåten som en XPath-kontextnod eller så är begäranstypen inte tillåten av detta[`IXPathExpression`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathExpression](../)
* namnutrymme [Aspose.Html.Dom.XPath](../../ixpathexpression/)
* hopsättning [Aspose.HTML](../../../)


