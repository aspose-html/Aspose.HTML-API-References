---
title: "Metered-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.Metered-klass. Tillhandahåller metoder för att sätta metrad nyckel"
type: docs

url: /sv/java/com.aspose.html/metered/
---
## Metered class

Tillhandahåller metoder för att ställa in mätad nyckel.

```java
public class Metered
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Metered](metered/)() | Initierar en ny instans av denna klass. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Ställer in metrad offentlig och privat nyckel. Om du köper en metrad licens, bör detta API anropas när applikationen startas; normalt räcker detta. Men om uppladdning av förbrukningsdata ständigt misslyckas och överskrider 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen; om den är i utvärderingsstatus, anropa detta API igen. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Hämtar förbrukningskredit |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Hämtar förbrukningsfilens storlek |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Kontrollera om metered är licensierad |

## Exempel

I det här exemplet kommer ett försök att ställa in den offentliga och privata nyckeln för metered att göras

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

komponent‑jar‑filen:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
