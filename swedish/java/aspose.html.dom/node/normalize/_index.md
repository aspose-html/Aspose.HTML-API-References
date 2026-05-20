---
title: "Node.Normalize"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. Placera alla Text‑noder i hela djupet av underträdet under denna Node, inklusive attributnoder, i ett normalt format där endast strukturen – t.ex. element, kommentarer, processinstruktioner, CDATA‑sektioner och entitetsreferenser – separerar Text‑noder, dvs. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer såsom XPointer‑uppslag som beror på en specifik dokumentträdstruktur ska användas. Om parametern normalize-characters för DOMConfiguration‑objektet som är kopplat till Node.ownerDocument är sann, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna."
type: docs

url: /sv/java/com.aspose.html.dom/node/normalize/
---
## Node.Normalize method

Placera alla [`Text`](../../text/)‑noder i hela djupet av underträdet under denna Node, inklusive attributnoder, i ett \"normalt\" format där endast strukturen (t.ex. [`elements`](../../element/), [`comments`](../../comment/), [`processing instructions`](../../processinginstruction/), [`CDATA sections`](../../cdatasection/), och [`entity references`](../../entityreference/)) separerar [`Text`](../../text/)‑noder, d.v.s. det finns varken intilliggande Text‑noder eller tomma Text‑noder. Detta kan användas för att säkerställa att DOM‑vyn av ett dokument är densamma som om det sparades och laddades om, och är användbart när operationer (såsom XPointer‑uppslag) som beror på en specifik dokumentträdstruktur ska användas. Om parametern \"normalize-characters\" för [`DOMConfiguration`](../../../com.aspose.html/configuration/)‑objektet som är kopplat till [`Node.ownerDocument`](../ownerdocument/) är sann, kommer denna metod också att fullt ut normalisera tecknen i Text‑noderna.

```java
public void Normalize()
```

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
