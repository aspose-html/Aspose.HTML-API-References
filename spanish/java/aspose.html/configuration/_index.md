---
title: "Configuration Clase"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.Configuration class. Representa el objeto de contexto de configuración que se utiliza para establecer los ajustes del entorno para la aplicación. Al gestionar la configuración, puede sobrescribir el estilo del documento aplicando una hoja de estilo de usuario personalizada o manejar cualquier solicitud web de la aplicación, así como configurar la política de scripts. Los detalles están en la guía de Configuración del Entorno"
type: docs

url: /es/java/com.aspose.html/configuration/
---
## Configuration class

Representa el objeto de contexto de configuración que se usa para establecer los ajustes del entorno para la aplicación. Al gestionar la configuración puedes sobrescribir el estilo del documento aplicando una hoja de estilo de usuario personalizada, o manejar cualquier solicitud web de la aplicación, así como configurar la política de scripts. Los detalles están en [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Configuration](configuration/)() | Inicializa una nueva instancia de la `class`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Cree y configure la instancia del objeto Configuration. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Cree y configure la instancia del objeto Configuration. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el desbloqueo o el restablecimiento de recursos no administrados. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Obtiene el servicio solicitado. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Obtiene el servicio solicitado. |

## Observaciones

Puedes descargar los ejemplos completos y los archivos de datos desde [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Ejemplos

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // Este manejador de mensajes imprime un mensaje sobre el inicio y la finalización del procesamiento de la solicitud
    public class LogMessageHandler : MessageHandler
    {
      // Sobrescriba el método Invoke()
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Invoca el siguiente manejador de mensajes en la cadena
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Crea una instancia de la clase Configuration
      using var configuration = new Configuration();

      // Agrega el LogMessageHandler a la cadena de manejadores de mensajes existentes
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Prepara la ruta a un archivo de documento fuente
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Inicializa un documento HTML con la configuración especificada
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
      // Prepara código HTML y guárdalo en un archivo
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Crea una instancia de Configuration
      using (var configuration = new Configuration())
      {
        // Marca 'scripts' como un recurso no confiable
        configuration.Security |= Sandbox.Scripts;

        // Inicializa un documento HTML con la configuración especificada
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Convertir HTML a PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### Ver también

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
