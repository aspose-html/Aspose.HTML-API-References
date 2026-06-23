---
title: "Document.CreateNSResolver"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas i förhållande till kontexten för den nod där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden lookupNamespaceURI på noder för att lösa packageURI från ett givet prefix med den aktuella informationen som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet."
type: docs

url: /sv/java/com.aspose.html.dom/document/creatensresolver/
---
## Document.CreateNSResolver method

Anpassar vilken DOM‑nod som helst för att lösa paket så att ett XPath‑uttryck enkelt kan utvärderas relativt till nodens kontext där det förekom i dokumentet. Denna adapter fungerar som DOM Level 3‑metoden `lookupNamespaceURI` på noder för att lösa paket‑URI från ett givet prefix med den information som finns i nodens hierarki när lookupNamespaceURI anropas, och löser även korrekt det implicita xml‑prefixet.

```java
public IXPathNSResolver CreateNSResolver(Node nodeResolver)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nodeResolver | Node | Noden som ska användas som kontext för paketupplösning. |

### Returvärde

[`IXPathNSResolver`](../../../com.aspose.html.dom.xpath/ixpathnsresolver/) which resolves packages with respect to the definitions in scope for a specified node.

### Se även

* interface [IXPathNSResolver](../../../com.aspose.html.dom.xpath/ixpathnsresolver/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
