---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "INodeIterator property. De waarde van deze vlag bepaalt of de kinderen van entiteit-referentieknooppunten zichtbaar zijn voor de iterator. Als false worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knopen over te slaan. Om een weergave van het document te produceren waarin entiteit-referenties zijn uitgeklapt en de entiteit-referentieknoop zelf niet wordt blootgesteld, gebruik je de whatToShow‑vlaggen om de entiteit-referentieknoop te verbergen en stel je expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteit-referentieknooppunten maar zonder entiteit-uitbreiding, gebruik je de whatToShow‑vlaggen om de entiteit-referentieknoop te tonen en stel je expandEntityReferences in op false."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

De waarde van deze vlag bepaalt of de kinderen van entiteit-referentieknooppunten zichtbaar zijn voor de iterator. Als false worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knopen over te slaan. Om een weergave van het document te produceren waarin entiteit-referenties zijn uitgeklapt en de entiteit-referentieknoop zelf niet wordt blootgesteld, gebruik je de whatToShow‑vlaggen om de entiteit-referentieknoop te verbergen en stel je expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteit-referentieknooppunten maar zonder entiteit-uitbreiding, gebruik je de whatToShow‑vlaggen om de entiteit-referentieknoop te tonen en stel je expandEntityReferences in op false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` als [expand entity references]; anders `false`.

### Zie ook

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
