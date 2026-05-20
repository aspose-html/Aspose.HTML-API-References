---
title: "IXPathEvaluator.CreateNSResolver"
second_title: "Aspose.HTML för Java API-referens"
description: "IXPathEvaluator-metod. Anpassar vilken DOM-nod som helst för att lösa paket så att ett XPath-uttryck kan utvärderas enkelt i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3-metoden lookupNamespaceURI på noder för att lösa packageURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, samt korrekt löser det implicita xml-prefixet."
type: docs

url: /sv/java/com.aspose.html.dom.xpath/ixpathevaluator/creatensresolver/
---
## IXPathEvaluator.CreateNSResolver method

Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas relativt till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden `lookupNamespaceURI` på noder för att lösa paket‑URI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeResolver | Node | Noden som ska användas som kontext för paketupplösning. |

### Returvärde

[`IXPathNSResolver`](../../ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Se även

* interface [IXPathNSResolver](../../ixpathnsresolver/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IXPathEvaluator](../)
* package [com.aspose.html.dom.xpath](../../../com.aspose.html.dom.xpath/)
* package [Aspose.HTML](../../../)
