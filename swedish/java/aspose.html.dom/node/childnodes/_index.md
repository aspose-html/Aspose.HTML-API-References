---
title: "Node.ChildNodes"
second_title: "Aspose.HTML för Java API-referens"
description: "Node‑egenskap. Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande NodeList med barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer."
type: docs

url: /sv/java/com.aspose.html.dom/node/childnodes/
---
## Node.ChildNodes property

Den skrivskyddade childNodes‑egenskapen i Node‑gränssnittet returnerar en levande [`NodeList`](../../../com.aspose.html.collections/nodelist/) med barnnoder för det angivna elementet där den första barnnoden får index 0. Barnnoder inkluderar element, text och kommentarer.

Obs: Att [`NodeList`](../../../com.aspose.html.collections/nodelist/) är levande betyder att dess innehåll ändras varje gång nya barn läggs till eller tas bort.

```java
public NodeList ChildNodes { get; }
```

### Property Value

En levande [`NodeList`](../../../com.aspose.html.collections/nodelist/) som innehåller nodens barn.

Obs: Flera anrop till childNodes returnerar samma [`NodeList`](../../../com.aspose.html.collections/nodelist/).

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-childnodes](https://dom.spec.whatwg.org/#dom-node-childnodes).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [NodeList](../../../com.aspose.html.collections/nodelist/)
* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
