---
title: "Configuration-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.Configuration-klass. Representerar konfigurationskontextobjektet som används för att ställa in miljöinställningarna för applikationen. Genom att hantera konfiguration kan du åsidosätta dokumentstilen genom att tillämpa en anpassad användar‑stylesheet eller hantera alla webb‑förfrågningar från applikationen samt konfigurera skriptpolicy. Detaljer finns i guiden Environment Configuration."
type: docs

url: /sv/java/com.aspose.html/configuration/
---
## Configuration class

Representerar konfigurationskontext‑objektet som används för att ställa in miljöinställningarna för applikationen. Genom att hantera konfiguration kan du åsidosätta dokumentstil genom att tillämpa ett anpassat användar‑stylesheet, eller hantera alla webb‑förfrågningar från applikationen samt konfigurera skriptpolicy. Detaljer finns i [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Configuration](configuration/)() | Initierar en ny instans av `class`. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Skapa och konfigurera instansen av Configuration‑objektet. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Skapa och konfigurera instansen av Configuration‑objektet. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Hämtar den begärda tjänsten. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Hämtar den begärda tjänsten. |

## Anmärkningar

Du kan ladda ner de kompletta exemplen och datafilerna från [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Exempel

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Denna meddelandehanterare skriver ut ett meddelande om start och avslut av begäran.
    public class LogMessageHandler : MessageHandler
    {
      // Åsidosätt Invoke()-metoden
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Anropa nästa meddelandehanterare i kedjan
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Skapa en instans av Configuration-klassen
      using var configuration = new Configuration();

      // Lägg till LogMessageHandler i kedjan av befintliga meddelandehanterare
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Förbered sökväg till en källdokumentfil
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Initiera ett HTML-dokument med angiven konfiguration
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
      // Förbered HTML-kod och spara den till en fil
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Skapa en instans av Configuration
      using (var configuration = new Configuration())
      {
        // Markera 'scripts' som en opålitlig resurs
        configuration.Security |= Sandbox.Scripts;

        // Initiera ett HTML-dokument med angiven konfiguration
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Konvertera HTML till PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Se även

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
