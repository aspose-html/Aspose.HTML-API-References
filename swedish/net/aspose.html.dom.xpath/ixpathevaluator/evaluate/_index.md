---
title: IXPathEvaluator.Evaluate
second_title: Aspose.HTML för .NET API Referens
description: IXPathEvaluator metod. Utvärderar en XPathuttryckssträng och returnerar ett resultat av den angivna typen om möjligt.
type: docs
weight: 30
url: /sv/net/aspose.html.dom.xpath/ixpathevaluator/evaluate/
---
## IXPathEvaluator.Evaluate method

Utvärderar en XPath-uttryckssträng och returnerar ett resultat av den angivna typen om möjligt.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttryckssträngen som ska tolkas och utvärderas. |
| contextNode | Node | De`sammanhang` är kontextnod för utvärderingen av detta XPath-uttryck. Om[`IXPathEvaluator`](../) erhölls genom att gjuta [`Document`](../../../aspose.html.dom/document/) då måste detta ägas av samma dokument och måste vara en [`Document`](../../../aspose.html.dom/document/) ,[`Element`](../../../aspose.html.dom/element/) ,[`Attr`](../../../aspose.html.dom/attr/) ,[`Text`](../../../aspose.html.dom/text/) , [`CDATASection`](../../../aspose.html.dom/cdatasection/) ,[`Comment`](../../../aspose.html.dom/comment/) ,[`ProcessingInstruction`](../../../aspose.html.dom/processinginstruction/) , ellerXPathNamespace nod. Om kontextnoden är en[`Text`](../../../aspose.html.dom/text/) eller en [`CDATASection`](../../../aspose.html.dom/cdatasection/)då tolkas kontexten som hela den logiska textnoden som ses av XPath, såvida inte noden är tom, i vilket fall den kanske inte fungerar som XPath-kontext. |
| resolver | IXPathNSResolver | De`resolver` tillåter översättning av alla prefix, inklusive the`xml` namnområdesprefix, inom XPath-uttrycket till lämpliga namnområdes-URI:er. Om detta anges som`null` , kommer alla namnområdesprefix i uttrycket att resultera i [`DOMException`](../../../aspose.html.dom/domexception/) kastas med koden`NAMESPACE_ERR`. |
| type | XPathResultType | Om en specifik`typ` anges, kommer resultatet att returneras som motsvarande typ. För XPath 1.0-resultat måste detta vara ett av värdena för [`XPathResultType`](../../xpathresulttype/) uppräkning. |
| result | Object | De`resultat` anger ett specifikt resultatobjekt som kan återanvändas och returneras med denna metod. Om detta anges som`null`eller att implementeringen inte återanvänder det angivna resultatet, kommer ett nytt resultatobjekt att konstrueras och returneras. För XPath 1.0 -resultat kommer detta objekt att vara av typen[`IXPathResult`](../../ixpathresult/). |

### Returvärde

Resultatet av utvärderingen av XPath-uttrycket. För XPath 1.0-resultat kommer detta objekt att vara av typen[`IXPathResult`](../../ixpathresult/).

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INVALID_EXPRESSION_ERR: Ökas om uttrycket inte är lagligt enligt enligt reglerna i[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | TYPE_ERR: Ökas om resultatet inte kan konverteras för att returnera den angivna typen . |
| [DOMException](../../../aspose.html.dom/domexception/) | NAMESPACE_ERR: Ökas om uttrycket innehåller namnområdesprefix som inte kan lösas av den angivna[`IXPathNSResolver`](../../ixpathnsresolver/). |
| [DOMException](../../../aspose.html.dom/domexception/) | WRONG_DOCUMENT_ERR: Noden är från ett dokument som inte stöds av detta[`IXPathEvaluator`](../). |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Noden är inte en typ som är tillåten som en XPath-kontext nod eller så är begäranstypen inte tillåten av denna[`IXPathEvaluator`](../). |

### Se även

* interface [IXPathResult](../../ixpathresult/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathNSResolver](../../ixpathnsresolver/)
* enum [XPathResultType](../../xpathresulttype/)
* interface [IXPathEvaluator](../)
* namnutrymme [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* hopsättning [Aspose.HTML](../../../)


