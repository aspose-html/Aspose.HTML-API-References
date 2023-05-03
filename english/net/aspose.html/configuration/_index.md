---
title: Configuration Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Configuration class. Represents the configuration context object that is used to set up the environment settings for the application. Managing configuration you can override document style applying a custom user stylesheet or handle any web requests from the application as well as to configure scripts policy. Details are in Environment Configuration guide
type: docs
weight: 60
url: /net/aspose.html/configuration/
---
## Configuration class

Represents the configuration context object that is used to set up the environment settings for the application. Managing configuration you can override document style applying a custom user stylesheet, or handle any web requests from the application as well as to configure scripts policy. Details are in [Environment Configuration guide](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/).

```csharp
public class Configuration : IDisposable, IServiceProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Configuration](configuration/)() | Initializes a new instance of the `class`. |

## Properties

| Name | Description |
| --- | --- |
| [Security](../../aspose.html/configuration/security/) { get; set; } | Gets or sets the sandboxing flag of the configuration. Refer to article about [sandboxing](https://docs.aspose.com/html/net/working-with-documents/environment-configuration/#sandboxing). |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.html/configuration/create/#create)() | Create and configure the instance of Configuration object. |
| static [Create](../../aspose.html/configuration/create/#create_1)(Action&lt;IConfigurationBuilder&gt;) | Create and configure the instance of Configuration object. |
| [Dispose](../../aspose.html/configuration/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetService](../../aspose.html/configuration/getservice/#getservice)(Type) | Gets the requested service. |
| [GetService&lt;T&gt;](../../aspose.html/configuration/getservice/#getservice_1)() | Gets the requested service. |

## Remarks

You can download the complete examples and data files from [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation).

## Examples

```csharp
using System;
using System.Diagnostics;
using System.IO;
using Aspose.Html;
using Aspose.Html.Net;
using Aspose.Html.Services;

    // This message handler prints a message about start and finish processing request
    public class LogMessageHandler : MessageHandler
    {
      // Override the Invoke() method
      public override void Invoke(INetworkOperationContext context)
      {
        Debug.WriteLine("Start processing request: " + context.Request.RequestUri);

        // Invoke the next message handler in the chain
        Next(context);

        Debug.WriteLine("Finish processing request: " + context.Request.RequestUri);
      }
    }
```

```csharp
    public void CreateACustomMessageHandlerTest()
    {
      // Create an instance of the Configuration class
      using var configuration = new Configuration();

      // Add the LogMessageHandler to the chain of existing message handlers
      var service = configuration.GetService<INetworkService>();
      var handlers = service.MessageHandlers;
           
      handlers.Insert(0, new LogMessageHandler());

      // Prepare path to a source document file
      string documentPath = Path.Combine(DataDir, "input.htm");

      // Initialize an HTML document with specified configuration
      using var document = new HTMLDocument(documentPath, configuration);
    }
```

```csharp
using Aspose.Html;
using Aspose.Html.Converters;
using Aspose.Html.Net;
using Aspose.Html.Saving;
using Aspose.Html.Services;
using System;
using System.Collections.Generic;
using System.IO;
using System.Net;
using System.Text;

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

* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
