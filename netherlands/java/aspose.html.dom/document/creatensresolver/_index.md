---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document method. Past elk DOM‑knooppunt aan om pakketten op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waar het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode lookupNamespaceURI op knooppunten bij het oplossen van de packageURI vanuit een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van knooppunten op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op."
type: docs

url: /nl/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Past elk DOM‑knooppunt aan om pakketten op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waarin het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knooppunten bij het oplossen van de packageURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| nodeResolver | Node | Het knooppunt dat moet worden gebruikt als context voor pakketresolutie. |

### Retourwaarde

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Zie ook

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
