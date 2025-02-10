---
title: Configuration Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Configuration class. Represents the configuration context object that is used to set up the environment settings for the application. Managing configuration you can override document style applying a custom user stylesheet or handle any web requests from the application as well as to configure scripts policy. Details are in Environment Configuration guide
type: docs
weight: 220
url: /java/com.aspose.html/configuration/
---
## Configuration class

Represents the configuration context object that is used to set up the environment settings for the application. Managing configuration you can override document style applying a custom user stylesheet, or handle any web requests from the application as well as to configure scripts policy. Details are in [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```java
public class Configuration : IDisposable, IServiceProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Configuration](configuration/)() | Initializes a new instance of the `class`. |

## Properties

| Name | Description |
| --- | --- |
[getSecurity]
[setSecurity] Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../com.aspose.html/configuration/create/#create)() | Create and configure the instance of Configuration object. |
| static [Create](../../com.aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Create and configure the instance of Configuration object. |
| [dispose](../../com.aspose.html/configuration/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [getService](../../com.aspose.html/configuration/getservice/#getservice)(Type) | Gets the requested service. |
| [GetService&lt;T&gt;](../../com.aspose.html/configuration/getservice/#getservice_1)() | Gets the requested service. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```java
import System;
import System.Diagnostics;
import System.IO;
import Aspose.Html;
import com.aspose.html.net;
import com.aspose.html.services;

    // This message handler prints a message about start and finish processing request
    public class LogMessageHandler : MessageHandler
    {
      // Override the Invoke() method
      public void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Invoke the next message handler in the chain
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```java
    public void CreateACustomMessageHandlerTest()
    {
      // Create an instance of the Configuration class
      using var configuration = new Configuration();

      // Add the LogMessageHandler to the chain of existing message handlers
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Prepare path to a source document file
      String documentPath = Path.Combine(DataDir, "input.htm");

      // Initialize an HTML document with specified configuration
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
      // Prepare HTML code and save it to a file
      var code = "<span>Hello World!!</span> " +
            "<script>document.write('Have a nice day!');</script>";

      File.WriteAllText(Path.Combine(OutputDir, "sandboxing.html"), code);

      // Create an instance of Configuration
      using (var configuration = new Configuration())
      {
        // Mark 'scripts' as an untrusted resource
        configuration.Security |= Sandbox.Scripts;

        // Initialize an HTML document with specified configuration
        using (var document = new HTMLDocument(Path.Combine(OutputDir, "sandboxing.html"), configuration))
        {
          // Convert HTML to PDF
          Converter.ConvertHTML(document, new PdfSaveOptions(), Path.Combine(OutputDir, "sandboxing_out.pdf"));
        }
      }       
    }
```

*OutputDir - user output folder path.

### See Also

* package [com.aspose.html](../../com.aspose.html/)
* package [Aspose.HTML](../../)
