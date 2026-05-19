---
title: "License.SetLicense"
second_title: "Aspose.HTML voor Java API-referentie"
description: "License‑methode. Licentieert het component"
type: docs

url: /nl/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Licentieert het component.

```java
public void SetLicense(String licenseName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege String om over te schakelen naar evaluatiemodus. |

## Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map die de Aspose‑component‑assembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry (startup)‑assembly bevat.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

2. De map die het Aspose‑component‑JAR‑bestand bevat.

3. De map die het aanroepende JAR‑bestand van de client bevat.

## Voorbeelden

In dit voorbeeld wordt geprobeerd een licentiebestand met de naam MyLicense.lic te vinden in de map die het component bevat, in de map die de aanroepende assembly bevat, in de map van de entry-assembly en vervolgens in de ingesloten resources van de aanroepende assembly.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

het component‑jar‑bestand:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Zie ook

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Licentieert het component.

```java
public void SetLicense(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stream | Een stream die de licentie bevat. |

## Opmerkingen

Gebruik deze methode om een licentie uit een stream te laden.

## Voorbeelden

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Zie ook

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
