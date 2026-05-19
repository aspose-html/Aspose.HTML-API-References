---
title: "TypeInfo.IsDerivedFrom"
second_title: "Aspose.HTML voor Java API-referentie"
description: "TypeInfo-methode. Deze methode geeft terug of er een afleiding bestaat tussen de referentietype-definitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere type-definitie, d.w.z. degene die als parameter wordt doorgegeven"
type: docs

url: /nl/java/com.aspose.html.dom/typeinfo/isderivedfrom/
---
## TypeInfo.IsDerivedFrom method

Deze methode retourneert of er een afleiding bestaat tussen de referentietype-definitie, d.w.z. de TypeInfo waarop de methode wordt aangeroepen, en de andere type-definitie, d.w.z. die welke als parameter wordt doorgegeven.

```java
public bool IsDerivedFrom(String typeNamespaceArg, String typeNameArg, ulong derivationMethod)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeNamespaceArg | String | het pakket van de andere type-definitie |
| typeNameArg | String | de naam van de andere type-definitie. |
| derivationMethod | UInt64 | het type afleiding en de voorwaarden die tussen twee types worden toegepast, zoals beschreven in de lijst met constanten die in deze interface wordt geleverd. |

### Retourwaarde

Als het schema van het document een DTD is of er geen schema aan het document is gekoppeld, zal deze methode altijd false teruggeven. Als het schema van het document een XML Schema is, zal de methode true teruggeven als de referentietype-definitie is afgeleid van de andere type-definitie volgens de afleidingsparameter. Als de waarde van de parameter 0 is (er is geen bit op 1 gezet voor de derivationMethod-parameter), zal de methode true teruggeven als de andere type-definitie kan worden bereikt door recursief elke combinatie van {basistype-definitie}, {itemtype-definitie} of {membertype-definities} vanuit de referentietype-definitie te doorlopen.

### Zie ook

* class [TypeInfo](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
