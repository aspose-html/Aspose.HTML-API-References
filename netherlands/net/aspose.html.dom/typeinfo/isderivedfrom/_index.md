---
title: TypeInfo.IsDerivedFrom
second_title: Aspose.HTML voor .NET API-referentie
description: TypeInfo methode. Deze methode retourneert als er een afleiding is tussen de definitie van het referentietype dwz de TypeInfo waarop de methode wordt aangeroepen en de andere typedefinitie dwz degene die is doorgegeven als parameters.
type: docs
weight: 30
url: /nl/net/aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Deze methode retourneert als er een afleiding is tussen de definitie van het referentietype, dwz de TypeInfo waarop de methode wordt aangeroepen, en de andere typedefinitie, dwz degene die is doorgegeven als parameters.

```csharp
public bool IsDerivedFrom(string typeNamespaceArg, string typeNameArg, ulong derivationMethod)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeNamespaceArg | String | de naamruimte van de andere typedefinitie |
| typeNameArg | String | de naam van de andere typedefinitie. |
| derivationMethod | UInt64 | het type afleiding en toegepaste voorwaarden tussen twee typen, zoals beschreven in de lijst met constanten in deze interface. |

### Winstwaarde

Als het schema van het document een DTD is of als er geen schema aan het document is gekoppeld, zal deze methode altijd false retourneren. Als het schema van het document een XML-schema is, is de methode waar als de referentietypedefinitie is afgeleid van de andere typedefinitie volgens de afleidingsparameter. Als de waarde van de parameter 0 is (er is geen bit ingesteld op 1 voor de parameter derivationMethod), retourneert de methode true als de andere typedefinitie kan worden bereikt door elke combinatie van {basistypedefinitie}, {itemtypedefinitie} te herhalen , of {member type definitions} van de reference type definition.

### Zie ook

* class [TypeInfo](../)
* naamruimte [Aspose.Html.Dom](../../typeinfo/)
* montage [Aspose.HTML](../../../)


