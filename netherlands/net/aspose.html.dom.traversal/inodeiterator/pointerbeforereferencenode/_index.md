---
title: INodeIterator.PointerBeforeReferenceNode
second_title: Aspose.HTML voor .NET API-referentie
description: INodeIterator eigendom. De waarde van deze vlag bepaalt of de kinderen van entiteit referentieknooppunten zichtbaar zijn voor de iterator. Indien onwaar zullen zij en hun afstammelingen worden afgewezen. Merk op dat deze weigering voorrang heeft op whatToShow en het filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen verwerpen in plaats van afzonderlijke knooppunten overslaan. Om een weergave te maken van het document met entiteitsreferenties uitgebreid en het entiteitsreferentieknooppunt zelf niet bloot te leggen use de whatToShowvlaggen naar verberg de entiteitsreferentie node en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave te maken van het document met entiteitsreferentie knooppunten maar zonder entiteitsuitbreiding gebruikt u de whatToShowvlaggen om het entiteitsreferentieknooppunt weer te geven en set expandEntityReferences naar false.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/
---
## INodeIterator.PointerBeforeReferenceNode property

De waarde van deze vlag bepaalt of de kinderen van entiteit referentieknooppunten zichtbaar zijn voor de iterator. Indien onwaar, zullen zij en hun afstammelingen worden afgewezen. Merk op dat deze weigering voorrang heeft op whatToShow en het filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen verwerpen in plaats van afzonderlijke knooppunten overslaan. Om een weergave te maken van het document met entiteitsreferenties uitgebreid en het entiteitsreferentieknooppunt zelf niet bloot te leggen, use de whatToShow-vlaggen naar verberg de entiteitsreferentie node en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave te maken van het document met entiteitsreferentie -knooppunten maar zonder entiteitsuitbreiding, gebruikt u de whatToShow-vlaggen om het entiteitsreferentieknooppunt weer te geven en set expandEntityReferences naar false.

```csharp
public bool PointerBeforeReferenceNode { get; }
```

### Eigendoms-waarde

`WAAR`if [entiteitsreferenties uitvouwen]; anders,`vals` .

### Zie ook

* interface [INodeIterator](../)
* naamruimte [Aspose.Html.Dom.Traversal](../../inodeiterator/)
* montage [Aspose.HTML](../../../)


