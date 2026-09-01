---
title: "Node.TextContent"
second_title: "Aspose.HTML för Java API-referens"
description: "Node egenskap. textContent-egenskapen i Node-gränssnittet representerar textinnehållet för noden och dess efterföljare"
type: docs

url: /sv/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

textContent-egenskapen i [`Node`](../)-gränssnittet representerar textinnehållet för noden och dess efterföljare.

```java
public String TextContent { get; set; }
```

### Property Value

En sträng, eller null. Dess värde beror på situationen:

Om noden är ett dokument eller en doctype, returnerar textContent null. Obs: För att hämta all text och CDATA‑data för hela dokumentet, använd document.documentElement.textContent. Om noden är en CDATA‑sektion, en kommentar, en bearbetningsinstruktion eller en textnod, returnerar textContent, eller sätter, texten i noden, d.v.s. [`Node.nodeValue`](../nodevalue/). För andra nodtyper returnerar textContent sammansättningen av textContent för varje barnnod, exklusive kommentarer och bearbetningsinstruktioner.

## Anmärkningar

Referens:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Se även

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
