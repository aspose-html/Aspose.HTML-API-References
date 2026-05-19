---
title: "IXPathEvaluator‑interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.xpath.IXPathEvaluator‑interface. De evaluatie van XPath‑expressies wordt verzorgd door IXPathEvaluator"
type: docs

url: /nl/java/com.aspose.html.dom.xpath/ixpathevaluator/
---
## IXPathEvaluator interface

De evaluatie van XPath‑expressies wordt verzorgd door `IXPathEvaluator`.

```java
public interface IXPathEvaluator
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [createExpression](../../com.aspose.html.dom.xpath/ixpathevaluator/createexpression/)(String, IXPathNSResolver) | Maakt een geparseerde XPath‑expressie met opgeloste pakketten. Dit is nuttig wanneer een expressie opnieuw wordt gebruikt in een toepassing, omdat het mogelijk maakt de expressie‑String te compileren naar een efficiëntere interne vorm en alle pakket‑prefixen die in de expressie voorkomen vooraf op te lossen. |
| [createNSResolver](../../com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/)(Node) | Past elk DOM‑knooppunt aan om pakketten op te lossen zodat een XPath‑expressie gemakkelijk kan worden geëvalueerd ten opzichte van de context van het knooppunt waarin het in het document verscheen. Deze adapter werkt zoals de DOM Level 3‑methode `lookupNamespaceURI` op knooppunten bij het oplossen van de packageURI van een gegeven prefix met behulp van de huidige informatie die beschikbaar is in de hiërarchie van het knooppunt op het moment dat lookupNamespaceURI wordt aangeroepen, en lost ook de impliciete xml‑prefix correct op. |
| [evaluate](../../com.aspose.html.dom.xpath/ixpathevaluator/evaluate/)(String, Node, IXPathNSResolver, XPathResultType, object) | Evalueert een XPath‑expressie‑String en retourneert, indien mogelijk, een resultaat van het opgegeven type. |

### Zie ook

* package [com.aspose.html.dom.xpath](../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../)
