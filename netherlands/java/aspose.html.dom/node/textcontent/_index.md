---
title: "Node.TextContent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Node eigenschap. De textContent‑eigenschap van de Node‑interface vertegenwoordigt de tekstinhoud van het knooppunt en zijn afstammelingen"
type: docs

url: /nl/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

De textContent‑eigenschap van de [`Node`](../)‑interface vertegenwoordigt de tekstinhoud van het knooppunt en zijn afstammelingen.

```java
public String TextContent { get; set; }
```

### Property Value

Een String, of null. De waarde hangt af van de situatie:

Als het knooppunt een document of een doctype is, geeft textContent null terug. Opmerking: om alle tekst en CDATA-gegevens van het hele document te verkrijgen, gebruik document.documentElement.textContent. Als het knooppunt een CDATA‑sectie, een commentaar, een verwerkingsinstructie of een tekstknooppunt is, geeft textContent de tekst binnen het knooppunt terug of stelt deze in, d.w.z. de [`Node.nodeValue`](../nodevalue/). Voor andere knooppunttypen geeft textContent de concatenatie van de textContent van elk kindknooppunt terug, met uitzondering van commentaren en verwerkingsinstructies.

## Opmerkingen

Referentie:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Zie ook

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
