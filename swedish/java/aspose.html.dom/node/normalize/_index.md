---
title: "Node.Normalize"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. Placera alla Text‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i en normal form där endast struktur – t.ex. element, kommentarer, bearbetningsinstruktioner, CDATA‑sektioner och entitetsreferenser – separerar Text‑noder, dvs. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och lästes in igen och är användbart när operationer såsom XPointer‑uppslag som beror på en viss dokumentträdstruktur ska användas. Om parametern normalize-characters i DOMConfiguration‑objektet som är bifogat till Node.ownerDocument är sann, normaliserar denna metod även tecknen i Text‑noderna fullt ut."
type: docs

url: /sv/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Placera alla [`Text`](../../text/)‑noder i hela djupet av delträdet under denna Node, inklusive attributnoder, i ett "normalt" format där endast struktur (t.ex. [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), och [`entity references`](../../entityreference/)) separerar [`Text`](../../text/)‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och lästes in igen, och är användbart när operationer (såsom XPointer‑[XPointer]‑uppslag) som beror på en viss dokumentträdstruktur ska användas. Om parametern "normalize-characters" i [`DOMConfiguration`](../../../com.aspose.html/configuration/)‑objektet som är bifogat till [`Node.ownerDocument`](../ownerdocument/) är sann, normaliserar denna metod även tecknen i Text‑noderna fullt ut.

```java
public void Normalize()
```

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
