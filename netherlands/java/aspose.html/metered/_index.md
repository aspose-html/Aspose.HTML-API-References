---
title: "Metered‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.Metered‑klasse. Biedt methoden om een metered‑sleutel in te stellen"
type: docs

url: /nl/java/com.aspose.html/metered/
---
## Metered class

Biedt methoden om een gemeten sleutel in te stellen.

```java
public class Metered
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered/)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Stelt de openbare en private metered‑sleutel in. Als u een metered‑licentie aanschaft, moet deze API worden aangeroepen bij het starten van de applicatie; normaal gesproken is dat voldoende. Echter, als het uploaden van consumptiegegevens steeds mislukt en de 24‑uurgrens wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Haalt consumptie‑credit op |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Haalt consumptie‑bestandsomvang op |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Controleer of metered is gelicentieerd |

## Voorbeelden

In dit voorbeeld wordt geprobeerd om de openbare en privésleutel van metered in te stellen

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

het component‑jar‑bestand:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Zie ook

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
