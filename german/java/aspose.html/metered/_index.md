---
title: "Metered‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.Metered‑Klasse. Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit."
type: docs

url: /de/java/com.aspose.html/metered/
---
## Metered class

Stellt Methoden bereit, um den metered key zu setzen.

```java
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [setMeteredKey](../../com.aspose.html/metered/setmeteredkey/)(String, String) | Setzt den öffentlichen und privaten Metered‑Schlüssel. Wenn Sie eine Metered‑Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz in den Evaluierungs‑Status gesetzt. Um diesen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungs‑Status, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../com.aspose.html/metered/getconsumptioncredit/)() | Gibt das Verbrauchsguthaben zurück |
| static [GetConsumptionQuantity](../../com.aspose.html/metered/getconsumptionquantity/)() | Gibt die Dateigröße des Verbrauchs zurück |
| static [IsMeteredLicensed](../../com.aspose.html/metered/ismeteredlicensed/)() | Überprüfen, ob Metered lizenziert ist |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten Schlüssel von Metered zu setzen

```java
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten‑JAR‑Datei:

```java
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
