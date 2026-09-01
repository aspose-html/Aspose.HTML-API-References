---
title: "Classe Metered"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.Metered. Fornisce metodi per impostare la chiave metered"
type: docs

url: /it/java/com.aspose.html/metered/
---
## Metered class

Fornisce metodi per impostare la chiave a consumo.

```java
public class Metered
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Metered](metered/)() | Inizializza una nuova istanza di questa classe. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Imposta la chiave pubblica e privata metered. Se acquisti una licenza metered, all'avvio dell'applicazione questa API deve essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata in stato di valutazione; per evitare questo caso, dovresti controllare regolarmente lo stato della licenza e, se è in stato di valutazione, chiamare nuovamente questa API. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Ottiene il credito di consumo |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Ottiene la dimensione del file di consumo |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Verifica se il metered è licenziato |

## Esempi

In questo esempio, verrà tentato di impostare la chiave pubblica e privata di metered

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

il file jar del componente:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Vedi anche

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
