---
title: "Node.TextContent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Node-Eigenschaft. Die textContent‑Eigenschaft der Node‑Schnittstelle stellt den Textinhalt des Knotens und seiner Nachkommen dar"
type: docs

url: /de/java/com.aspose.html.dom/node/textcontent/
---
## Node.TextContent property

Die textContent‑Eigenschaft der [`Node`](../)‑Schnittstelle stellt den Textinhalt des Knotens und seiner Nachkommen dar.

```java
public String TextContent { get; set; }
```

### Property Value

Ein String oder null. Sein Wert hängt von der Situation ab:

Wenn der Knoten ein Dokument oder ein Doctype ist, gibt textContent null zurück. Hinweis: Um den gesamten Text und CDATA-Daten des gesamten Dokuments zu erhalten, verwenden Sie document.documentElement.textContent. Wenn der Knoten ein CDATA-Abschnitt, ein Kommentar, eine Verarbeitungsanweisung oder ein Textknoten ist, gibt textContent den Text im Knoten zurück oder setzt ihn, d. h. das [`Node.nodeValue`](../nodevalue/). Für andere Knotentypen gibt textContent die Verkettung des textContent aller Kindknoten zurück, wobei Kommentare und Verarbeitungsanweisungen ausgeschlossen werden.

## Hinweise

Referenz:

[DOM Standard](https://dom.spec.whatwg.org/) - defines a platform-neutral model for events, aborting activities, and node trees.[DOM Standard (DOM) # dom-node-textcontent](https://dom.spec.whatwg.org/#dom-node-textcontent).[GitHub](https://github.com/whatwg/dom) - repository hosts the DOM Standard.

### Siehe auch

* class [Node](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
