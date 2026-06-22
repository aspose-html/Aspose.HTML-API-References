---
title: "INodeIterator.PointerBeforeReferenceNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "INodeIterator-eigenschap. De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentieknooppunten zichtbaar zijn voor de iterator. Als false worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft op whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knopen over te slaan. Om een weergave van het document te produceren waarbij entiteitsreferenties zijn uitgeklapt en de entiteitsreferentieknoop zelf niet wordt blootgesteld, gebruik je de whatToShow-vlaggen om de entiteitsreferentieknoop te verbergen en stel je expandEntityReferences in op true bij het aanmaken van de iterator. Om een weergave van het document te produceren met entiteitsreferentieknooppunten maar zonder entiteitsexpansie, gebruik je de whatToShow-vlaggen om de entiteitsreferentieknoop te tonen en stel je expandEntityReferences in op false."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentieknooppunten zichtbaar zijn voor de iterator. Als false worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft op whatToShow en de filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knopen over te slaan. Om een weergave van het document te produceren waarbij entiteitsreferenties zijn uitgeklapt en de entiteitsreferentieknoop zelf niet wordt blootgesteld, gebruik je de whatToShow-vlaggen om de entiteitsreferentieknoop te verbergen en stel je expandEntityReferences in op true bij het aanmaken van de iterator. Om een weergave van het document te produceren met entiteitsreferentieknooppunten maar zonder entiteitsexpansie, gebruik je de whatToShow-vlaggen om de entiteitsreferentieknoop te tonen en stel je expandEntityReferences in op false.

```java
public bool PointerBeforeReferenceNode { get; }
```

### Property Value

`true` als [expand entity references]; anders `false`.

### Zie ook

* interface [INodeIterator](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
