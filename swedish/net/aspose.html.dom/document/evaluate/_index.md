---
title: Document.Evaluate
second_title: Aspose.HTML för .NET API Referens
description: Document metod. Utvärderar en XPathuttryckssträng och returnerar ett resultat av den angivna typen om möjligt.
type: docs
weight: 950
url: /sv/net/aspose.html.dom/document/evaluate/
---
## Document.Evaluate method

Utvärderar en XPath-uttryckssträng och returnerar ett resultat av den angivna typen om möjligt.

```csharp
public IXPathResult Evaluate(string expression, Node contextNode, IXPathNSResolver resolver, 
    XPathResultType type, object result)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| expression | String | XPath-uttryckssträngen som ska tolkas och utvärderas. |
| contextNode | Node | Kontexten är kontextnod för utvärderingen av detta XPath-uttryck. |
| resolver | IXPathNSResolver | Resolvern tillåter översättning av alla prefix, inklusive namnområdesprefixet xml , inom XPath-uttrycket till lämpliga namnområdes-URI:er. |
| type | XPathResultType | Om en specifik typ anges, kommer resultatet att returneras som motsvarande typ. |
| result | Object | Resultatet anger ett specifikt resultatobjekt som kan återanvändas och returneras med denna metod. |

### Returvärde

Resultatet av utvärderingen av XPath-uttrycket.

### Se även

* interface [IXPathResult](../../../aspose.html.dom.xpath/ixpathresult/)
* class [Node](../../node/)
* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* enum [XPathResultType](../../../aspose.html.dom.xpath/xpathresulttype/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)


