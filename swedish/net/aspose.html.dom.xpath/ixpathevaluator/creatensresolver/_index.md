---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.HTML för .NET API Referens
description: IXPathEvaluator metod. Anpassar valfri DOMnod för att lösa namnområden så att ett XPathuttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3metodenlookupNamespaceURI på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas vilket också korrekt löser det implicita xmlprefixet.
type: docs
weight: 20
url: /sv/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Anpassar valfri DOM-nod för att lösa namnområden så att ett XPath-uttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden`lookupNamespaceURI` på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas, vilket också korrekt löser det implicita xml-prefixet.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeResolver | Node | Noden som ska användas som en kontext för upplösning av namnutrymmet. |

### Returvärde

[`IXPathNSResolver`](../../ixpathnsresolver/) som löser namnområden med avseende på definitions i omfånget för en specificerad nod.

### Se även

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* namnutrymme [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* hopsättning [Aspose.HTML](../../../)


