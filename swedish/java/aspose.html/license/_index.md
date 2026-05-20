---
title: "License-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.License-klass. Tillhandahåller metoder för att licensiera komponenten"
type: docs

url: /sv/java/com.aspose.html/license/
---
## License class

Tillhandahåller metoder för att licensiera komponenten.

```java
public class License
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [License](license/)() | Initierar en ny instans av denna klass. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Licensierar komponenten. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Licensierar komponenten. |

## Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic att göras i mappen som innehåller komponenten, i mappen som innehåller den anropande samlingen, i mappen för startsamlingen och sedan i de inbäddade resurserna i den anropande samlingen.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

komponent‑jar‑filen:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
