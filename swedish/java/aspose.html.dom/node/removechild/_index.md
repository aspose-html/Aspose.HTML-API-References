---
title: "Node.RemoveChild"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑metod. removeChild‑metoden i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden."
type: docs

url: /sv/java/com.aspose.html.dom/node/removechild/
---
## Node.RemoveChild method

Metoden removeChild() i Node‑gränssnittet tar bort en barnnod från DOM och returnerar den borttagna noden.

Obs: Så länge en referens hålls till den borttagna barnet finns den fortfarande i minnet, men är inte längre en del av DOM. Den kan fortfarande återanvändas senare i koden. Om returvärdet från removeChild() inte lagras och ingen annan referens hålls, kommer det automatiskt att raderas från minnet efter en kort tid.

```java
public Node RemoveChild(Node child)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| child | Node | En [`Node`](../) som är barnnoden som ska tas bort från DOM. |

### Returvärde

Till skillnad från [`Node.cloneNode()`](../clonenode/) bevarar returvärdet de [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/)‑objekt som är associerade med det.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
