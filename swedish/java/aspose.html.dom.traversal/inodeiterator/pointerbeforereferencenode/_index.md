---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML för Java API-referens"
description: "INodeIterator-egenskap. Värdet på denna flagga bestämmer om barn till entity reference‑noder är synliga för iteratorn. Om falskt kommer de och deras undernoder att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd snarare än att hoppa över enskilda noder. För att skapa en vy av dokumentet där entity references är expanderade och inte avslöjar själva entity reference‑noden, använd whatToShow‑flaggorna för att dölja entity reference‑noden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entity reference‑noder men ingen entity‑expansion, använd whatToShow‑flaggorna för att visa entity reference‑noden och sätt expandEntityReferences till false."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

Värdet på denna flagga bestämmer om barn till entity reference‑noder är synliga för iteratorn. Om falskt kommer de och deras undernoder att avvisas. Observera att detta avvisande har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt underträd snarare än att hoppa över enskilda noder. För att skapa en vy av dokumentet där entity references är expanderade och inte avslöjar själva entity reference‑noden, använd whatToShow‑flaggorna för att dölja entity reference‑noden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entity reference‑noder men ingen entity‑expansion, använd whatToShow‑flaggorna för att visa entity reference‑noden och sätt expandEntityReferences till false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` om [expand entity references]; annars, `false`.

### Se även

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
