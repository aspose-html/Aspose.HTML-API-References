---
title: Document.CreateNSResolver
second_title: Aspose.HTML voor .NET API-referentie
description: Document methode. Past elk DOMknooppunt aan om naamruimten op te lossen zodat een XPathexpressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3methodeopzoekenNaamruimteURI op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen waarbij ook het impliciete xmlvoorvoegsel correct wordt opgelost.
type: docs
weight: 910
url: /nl/net/aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Past elk DOM-knooppunt aan om naamruimten op te lossen, zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode`opzoekenNaamruimteURI` op knooppunten bij het oplossen van de namespaceURI van een bepaald voorvoegsel met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, waarbij ook het impliciete xml-voorvoegsel correct wordt opgelost.

```csharp
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat moet worden gebruikt als context voor naamruimteomzetting. |

### Winstwaarde

[`IXPathNSResolver`](../../../aspose.html.dom.xpath/ixpathnsresolver/) die naamruimten oplost met betrekking tot de definities binnen bereik voor een opgegeven knooppunt.

### Zie ook

* interface [IXPathNSResolver](../../../aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* naamruimte [Aspose.Html.Dom](../../document/)
* montage [Aspose.HTML](../../../)


