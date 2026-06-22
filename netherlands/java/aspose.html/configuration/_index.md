---
title: "Configuration Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.Configuration class. Vertegenwoordigt het configuratie‑contextobject dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. Door de configuratie te beheren kun je de documentstijl overschrijven door een aangepast gebruikers‑stylesheet toe te passen of webverzoeken van de toepassing afhandelen, evenals het configureren van het scriptbeleid. Details staan in de Environment Configuration guide"
type: docs

url: /nl/java/com.aspose.html/configuration/
---
## Configuration class

Stelt het configuratie‑contextobject voor dat wordt gebruikt om de omgevingsinstellingen voor de toepassing in te stellen. Bij het beheren van configuratie kunt u de documentstijl overschrijven door een aangepast gebruikers‑stylesheet toe te passen, of webverzoeken van de toepassing afhandelen, evenals het configureren van het script‑beleid. Details staan in [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Configuration](configuration/)() | Initialiseert een nieuwe instantie van de `class`. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Maak en configureer de instantie van het Configuration‑object. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Maak en configureer de instantie van het Configuration‑object. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Voert toepassingsspecifieke taken uit die verband houden met het vrijgeven, loslaten of opnieuw instellen van niet‑beheerde bronnen. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Haalt de gevraagde service op. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Haalt de gevraagde service op. |

## Opmerkingen

Je kunt de volledige voorbeelden en gegevensbestanden downloaden van [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Voorbeelden

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Deze berichtverwerker drukt een bericht af over het starten en voltooien van de verwerking van een verzoek
    public class LogMessageHandler : MessageHandler
    {
      // Overschrijf de Invoke()-methode
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Roep de volgende berichtverwerker in de keten aan
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Maak een instantie van de Configuration-klasse
      using var configuration = new Configuration();

      // Voeg de LogMessageHandler toe aan de keten van bestaande berichtafhandelaars
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Bereid het pad naar een bron documentbestand voor
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Initialiseer een HTML-document met de opgegeven configuratie
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
      // Bereid HTML‑code voor en sla deze op in een bestand
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Maak een instantie van Configuration
      using (var configuration = new Configuration())
      {
        // Markeer 'scripts' als een niet‑vertrouwde bron
        configuration.Security |= Sandbox.Scripts;

        // Initialiseer een HTML-document met de opgegeven configuratie
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // HTML naar PDF converteren
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Zie ook

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
