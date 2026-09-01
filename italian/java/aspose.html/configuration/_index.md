---
title: "Classe Configuration"
second_title: "Aspose.HTML per Java Riferimento API"
description: "classe com.aspose.html.Configuration. Rappresenta l'oggetto di contesto di configurazione utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. Gestendo la configurazione è possibile sovrascrivere lo stile del documento applicando un foglio di stile utente personalizzato o gestire qualsiasi richiesta web dall'applicazione, nonché configurare la politica degli script. I dettagli sono nella guida Environment Configuration."
type: docs

url: /it/java/com.aspose.html/configuration/
---
## Configuration class

Rappresenta l'oggetto contesto di configurazione utilizzato per impostare le impostazioni dell'ambiente per l'applicazione. Gestendo la configurazione è possibile sovrascrivere lo stile del documento applicando un foglio di stile utente personalizzato, o gestire qualsiasi richiesta web dall'applicazione così come configurare la politica degli script. I dettagli sono nella [Guida alla configurazione dell'ambiente](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Configuration](configuration/)() | Inizializza una nuova istanza della `class`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Crea e configura l'istanza dell'oggetto Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Crea e configura l'istanza dell'oggetto Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Esegue attività definite dall'applicazione associate al rilascio, alla liberazione o al reset di risorse non gestite. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Ottiene il servizio richiesto. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Ottiene il servizio richiesto. |

## Osservazioni

Puoi scaricare gli esempi completi e i file di dati da [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Esempi

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Questo gestore di messaggi stampa un messaggio sull'inizio e la fine dell'elaborazione della richiesta
    public class LogMessageHandler : MessageHandler
    {
      // Sovrascrivi il metodo Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Invoca il prossimo gestore di messaggi nella catena
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Crea un'istanza della classe Configuration
      using var configuration = new Configuration();

      // Aggiungi il LogMessageHandler alla catena dei gestori di messaggi esistenti
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Prepara il percorso a un file di documento sorgente
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Inizializza un documento HTML con la configurazione specificata
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
      // Prepara il codice HTML e salvalo in un file
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Crea un'istanza di Configuration
      using (var configuration = new Configuration())
      {
        // Contrassegna 'scripts' come risorsa non attendibile
        configuration.Security |= Sandbox.Scripts;

        // Inizializza un documento HTML con la configurazione specificata
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Converti HTML in PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Vedi anche

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
