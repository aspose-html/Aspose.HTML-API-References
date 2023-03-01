---
title: Interface IXPathEvaluator
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.XPath.IXPathEvaluator gränssnitt. Utvärderingen av XPathuttryck tillhandahålls avIXPathEvaluator .
type: docs
weight: 2560
url: /sv/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

Utvärderingen av XPath-uttryck tillhandahålls av`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Skapar ett tolkat XPath-uttryck med lösta namnutrymmen. Detta är användbart när ett uttryck ska återanvändas i en applikation eftersom det gör det möjligt att kompilera uttryckssträngen till en mer effektiv intern form och förlösa alla namnområdesprefix som förekommer i uttrycket. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Anpassar valfri DOM-nod för att lösa namnområden så att ett XPath-uttryck enkelt kan utvärderas i förhållande till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden`lookupNamespaceURI` på noder för att lösa namnutrymmetURI från ett givet prefix med den aktuella informationen som är tillgänglig i nodens hierarki vid den tidpunkt lookupNamespaceURI anropas, vilket också korrekt löser det implicita xml-prefixet. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Utvärderar en XPath-uttryckssträng och returnerar ett resultat av den angivna typen om möjligt. |

### Se även

* namnutrymme [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* hopsättning [Aspose.HTML](../../)


