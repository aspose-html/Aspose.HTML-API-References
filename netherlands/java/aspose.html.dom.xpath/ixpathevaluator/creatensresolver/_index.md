---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IXPathEvaluator method. Past elke DOM-knooppunt aan om pakketten op te lossen zodat een XPath-expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3-methode lookupNamespaceURI op knooppunten bij het oplossen van de packageURI vanuit een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van knooppunten op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook correct de impliciete xml-prefix op."
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Past elk DOM‑knooppunt aan om pakketten op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waarin het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knooppunten bij het oplossen van de packageURI vanuit een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat moet worden gebruikt als context voor pakketresolutie. |

### Retourwaarde

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Zie ook

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
