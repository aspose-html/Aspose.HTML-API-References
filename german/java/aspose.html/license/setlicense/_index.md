---
title: "License.SetLicense"
second_title: "Aspose.HTML für Java API-Referenz"
description: "License-Methode. Lizenziert die Komponente"
type: docs

url: /de/java/com.aspose.html/license/setlicense/
---
## SetLicense(String) {#setlicense_1}

Lizenziert die Komponente.

```java
public void SetLicense(String licenseName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie einen leeren String, um in den Evaluierungsmodus zu wechseln. |

## Hinweise

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose-Komponenten-Assembly enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der die Entry-(Start-)Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

2. Der Ordner, der die Aspose-Komponenten-JAR-Datei enthält.

3. Der Ordner, der die aufrufende JAR-Datei des Clients enthält.

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

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```java
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

## Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

## Beispiele

```java
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Siehe auch

* class [License](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
