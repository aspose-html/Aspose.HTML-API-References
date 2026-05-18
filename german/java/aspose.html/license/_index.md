---
title: "License Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.License Klasse. Stellt Methoden zum Lizenzieren der Komponente bereit"
type: docs

url: /de/java/com.aspose.html/license/
---
## License class

Stellt Methoden bereit, um die Komponente zu lizenzieren.

```java
public class License
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [License](license/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense)(Stream) | Lizenziert die Komponente. |
| [setLicense](../../com.aspose.html/license/setlicense/#setlicense_1)(String) | Lizenziert die Komponente. |

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg‑Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```java
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

die Komponenten‑JAR‑Datei:

```java
License license = new License();
license.setLicense("MyLicense.lic");
```

### Siehe auch

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
