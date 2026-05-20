---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML för Java API-referens"
description: "INodeIterator‑egenskap. Värdet på denna flagga bestämmer om barnen till entity‑referensnoder är synliga för iteratorn. Om falskt kommer de och deras undernoder att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entity‑referenser är expanderade och inte avslöjar entity‑referensnoden själv, använd whatToShow‑flaggorna för att dölja entity‑referensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet med entity‑referensnoder men utan entity‑expansion, använd whatToShow‑flaggorna för att visa entity‑referensnoden och sätt expandEntityReferences till false."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Värdet på denna flagga bestämmer om barnen till entity‑referensnoder är synliga för iteratorn. Om falskt kommer de och deras undernoder att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entity‑referenser är expanderade och inte avslöjar entity‑referensnoden själv, använd whatToShow‑flaggorna för att dölja entity‑referensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet med entity‑referensnoder men utan entity‑expansion, använd whatToShow‑flaggorna för att visa entity‑referensnoden och sätt expandEntityReferences till false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` om [expandera entity references]; annars, `false`.

### Se även

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
