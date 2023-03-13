---
title: Class Metered
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Metered klas. Biedt methoden om gemeten sleutel in te stellen.
type: docs
weight: 3830
url: /nl/net/aspose.html/metered/
---
## Metered class

Biedt methoden om gemeten sleutel in te stellen.

```csharp
public class Metered
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered/)() | Initialiseert een nieuwe instantie van deze klasse. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [SetMeteredKey](../../aspose.html/metered/setmeteredkey/)(string, string) | Stelt gemeten publieke en private sleutel in. Als u een gemeten licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen, normaal gesproken is dit voldoende. Als het echter altijd niet lukt om verbruiksgegevens te uploaden en de 24 uur overschrijdt, wordt de licentie ingesteld op de evaluatiestatus, om een dergelijk geval te voorkomen, moet u regelmatig de licentiestatus controleren. Als het de evaluatiestatus is, roept u deze API opnieuw op. |
| static [GetConsumptionCredit](../../aspose.html/metered/getconsumptioncredit/)() | Krijgt consumptietegoed |
| static [GetConsumptionQuantity](../../aspose.html/metered/getconsumptionquantity/)() | Krijgt verbruiksbestandsgrootte |

### Voorbeelden

In dit voorbeeld wordt geprobeerd een gemeten openbare en privésleutel in te stellen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

het component jar-bestand:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Zie ook

* naamruimte [Aspose.Html](../../aspose.html/)
* montage [Aspose.HTML](../../)


