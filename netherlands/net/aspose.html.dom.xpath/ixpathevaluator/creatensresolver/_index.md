---
title: IXPathEvaluator.CreateNSResolver
second_title: Aspose.HTML voor .NET API-referentie
description: IXPathEvaluator methode. Past elk DOMknooppunt aan om naamruimten op te lossen zodat een XPathexpressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3methodeopzoekenNaamruimteURI op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen waarbij ook het impliciete xmlvoorvoegsel correct wordt opgelost.
type: docs
weight: 20
url: /nl/net/aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Past elk DOM-knooppunt aan om naamruimten op te lossen, zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode`opzoekenNaamruimteURI` op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, waarbij ook het impliciete xml-voorvoegsel correct wordt opgelost.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat moet worden gebruikt als context voor naamruimteomzetting. |

### Winstwaarde

[`IXPathNSResolver`](../../ixpathnsresolver/) die naamruimten oplost met betrekking tot de definities in bereik voor een gespecificeerd knooppunt.

### Zie ook

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* naamruimte [Aspose.Html.Dom.XPath](../../ixpathevaluator/)
* montage [Aspose.HTML](../../../)


