---
title: "Element.AttachShadow"
second_title: "Aspose.HTML för Java API-referens"
description: "Element-metod. Skapar ett shadow root och fäster det till det aktuella elementet"
type: docs

url: /sv/java/com.aspose.html.dom/element/attachshadow/
---
## Element.AttachShadow method

Skapar ett skuggrot och fäster det på det aktuella elementet.

```java
public ShadowRoot AttachShadow(ShadowRootMode mode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| läge | ShadowRootMode | Läge i vilket shadow root kommer att skapas. |

### Returvärde

Skapad [`ShadowRoot`](../../shadowroot/).

### Undantag

| undantag | villkor |
| --- | --- |
| Fel | NotSupportedError: Element stöder inte shadow tree. |
| Fel | InvalidStateError: Element har redan ett shadow tree. |

### Se även

* class [ShadowRoot](../../shadowroot/)
* enum [ShadowRootMode](../../shadowrootmode/)
* class [Element](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
