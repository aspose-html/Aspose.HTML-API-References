---
title: License.SetLicense
second_title: Aspose.HTML für .NET-API-Referenz
description: License methode. Lizenziert die Komponente.
type: docs
weight: 20
url: /de/net/aspose.html/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein vollständiger oder kurzer Dateiname sein oder Name einer eingebetteten Ressource. Verwenden Sie einen leeren String, um in den Bewertungsmodus zu wechseln. |

### Bemerkungen

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Explizite Pfad.

2. Der Ordner, der die Aspose-Komponentenbaugruppe enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der den Eintrag (Startup) Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Notiz:**Versucht in .NET Compact Framework, die Lizenz nur an diesen Speicherorten zu finden:

1. Explizite Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

2. Der Ordner, der die JAR-Datei der Aspose-Komponente enthält.

3. Der Ordner, der die aufrufende JAR-Datei des Clients enthält.

### Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei namens MyLicense.lic in dem Ordner zu finden, der enthält. die Komponente, in dem Ordner, der die aufrufende Assembly enthält, im Ordner der Eintragsassembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");
```

die Komponenten-JAR-Datei:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Siehe auch

* class [License](../)
* namensraum [Aspose.Html](../../license/)
* Montage [Aspose.HTML](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

### Bemerkungen

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

### Beispiele

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);
```

### Siehe auch

* class [License](../)
* namensraum [Aspose.Html](../../license/)
* Montage [Aspose.HTML](../../../)


