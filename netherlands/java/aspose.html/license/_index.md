---
title: "License Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.License class. Biedt methoden om het component te licentiëren"
type: docs

url: /nl/java/com.aspose.html/license/
---
## License class

Biedt methoden om het component te licentiëren.

```java
public class License
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [License](license/)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licentieert het component. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licentieert het component. |

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

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
