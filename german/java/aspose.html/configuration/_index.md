---
title: "Configuration Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.Configuration Klasse. Stellt das Konfigurationskontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung einzurichten. Durch die Verwaltung der Konfiguration können Sie den Dokumentstil überschreiben, indem Sie ein benutzerdefiniertes Stylesheet anwenden, oder Webanfragen der Anwendung behandeln sowie die Skript-Richtlinie konfigurieren. Details finden Sie im Leitfaden zur Umgebungskonfiguration."
type: docs

url: /de/java/com.aspose.html/configuration/
---
## Configuration class

Stellt das Konfigurations‑Kontextobjekt dar, das verwendet wird, um die Umgebungseinstellungen für die Anwendung einzurichten. Durch die Verwaltung der Konfiguration können Sie den Dokumentstil überschreiben, indem Sie ein benutzerdefiniertes Stylesheet anwenden, oder Web‑Anfragen der Anwendung behandeln sowie die Skript‑Richtlinie konfigurieren. Details finden Sie im [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Configuration](configuration/)() | Initialisiert eine neue Instanz der `class`. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Erstellen und konfigurieren Sie die Instanz des Configuration-Objekts. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Erstellen und konfigurieren Sie die Instanz des Configuration-Objekts. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen nicht verwalteter Ressourcen verbunden sind. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Ruft den angeforderten Dienst ab. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Ruft den angeforderten Dienst ab. |

## Hinweise

Sie können die vollständigen Beispiele und Datendateien von [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation) herunterladen.

## Beispiele

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Dieser Nachrichten-Handler gibt eine Meldung über den Start und das Ende der Anforderungsbearbeitung aus.
    public class LogMessageHandler : MessageHandler
    {
      // Überschreiben Sie die Invoke()-Methode
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Rufen Sie den nächsten Nachrichten-Handler in der Kette auf
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Erstellen Sie eine Instanz der Klasse Configuration
      using var configuration = new Configuration();

      // Fügen Sie den LogMessageHandler zur Kette der vorhandenen Nachrichten-Handler hinzu
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Bereiten Sie den Pfad zu einer Quelldokumentdatei vor
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Initialisieren Sie ein HTML-Dokument mit der angegebenen Konfiguration
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.net;
import com.aspose.html.saving;
import com.aspose.html.services;
import System;
import System.Collections.Generic;
import System.IO;
import System.Net;
import System.Text;

public void SandboxingSample()
    {
      // Bereiten Sie HTML‑Code vor und speichern Sie ihn in einer Datei
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Erstellen Sie eine Instanz von Configuration
      using (var configuration = new Configuration())
      {
        // Markieren Sie 'scripts' als nicht vertrauenswürdige Ressource
        configuration.Security |= Sandbox.Scripts;

        // Initialisieren Sie ein HTML-Dokument mit der angegebenen Konfiguration
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // HTML zu PDF konvertieren
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Siehe auch

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
