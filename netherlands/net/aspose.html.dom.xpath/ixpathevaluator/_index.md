---
title: Interface IXPathEvaluator
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.XPath.IXPathEvaluator koppel. De evaluatie van XPathexpressies wordt verzorgd doorIXPathEvaluator .
type: docs
weight: 2560
url: /nl/net/aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

De evaluatie van XPath-expressies wordt verzorgd door`IXPathEvaluator` .

```csharp
public interface IXPathEvaluator
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [CreateExpression](../../aspose.html.dom.xpath/ixpathevaluator/createexpression/)(string, IXPathNSResolver) | Maakt een geparseerde XPath-expressie met opgeloste naamruimten. Dit is handig wanneer een expressie opnieuw wordt gebruikt in een toepassing, aangezien het mogelijk maakt om de uitdrukkingsreeks in een efficiëntere interne vorm te compileren en alle naamruimtevoorvoegsels die binnen de uitdrukking voorkomen vooraf op te lossen. |
| [CreateNSResolver](../../aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Past elk DOM-knooppunt aan om naamruimten op te lossen, zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode`opzoekenNaamruimteURI` op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, waarbij ook het impliciete xml-voorvoegsel correct wordt opgelost. |
| [Evaluate](../../aspose.html.dom.xpath/ixpathevaluator/evaluate/)(string, Node, IXPathNSResolver, XPathResultType, object) | Evalueert een XPath-expressietekenreeks en retourneert indien mogelijk een resultaat van het opgegeven type. |

### Zie ook

* naamruimte [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath/)
* montage [Aspose.HTML](../../)


