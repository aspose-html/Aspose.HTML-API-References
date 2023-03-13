---
title: Document.CreateNSResolver
second_title: Aspose.HTML för .NET API Referens
description: Document metod. Anpassar valfri DOMnod för att lösa namnområden så att ett XPathuttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3metodenlookupNamespaceURI på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas vilket också korrekt löser det implicita xmlprefixet.
type: docs
weight: 910
url: /sv/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Anpassar valfri DOM-nod för att lösa namnområden så att ett XPath-uttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden`lookupNamespaceURI` på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas, vilket också korrekt löser det implicita xml-prefixet.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeResolver | Node | Noden som ska användas som en kontext för upplösning av namnutrymmet. |

### Returvärde

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) som löser namnutrymmen med avseende på definitionerna i omfånget för en specificerad nod.

### Se även

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* namnutrymme [Aspose.Html.Dom](../../document/)
* hopsättning [Aspose.HTML](../../../)


