---
title: Configuration Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Configuration class. Represents the configuration context object that is used to set up the environment settings for the application
type: docs
weight: 220
url: /net/aspose.html/configuration/
---
## Configuration class

Represents the configuration context object that is used to set up the environment settings for the application.

```csharp
public class Configuration : IDisposable, IServiceProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Configuration](configuration/)() | Initializes a new instance of the `Configuration` class. |

## Properties

| Name | Description |
| --- | --- |
| [Security](../../aspose.html/configuration/security/) { get; set; } | This property allows you to set a number of restrictions on the content loaded in the frame, for example, block forms and scripts. Refer to article about [sandboxing](https://docs.aspose.com/html/net/environment-configuration/#sandboxing). |

## Methods

| Name | Description |
| --- | --- |
| static [Create](../../aspose.html/configuration/create/#create)() | Create and configure the instance of Configuration object. |
| static [Create](../../aspose.html/configuration/create/#create_1)(*Action&lt;IConfigurationBuilder&gt;*) | Create and configure the instance of Configuration object. |
| [Dispose](../../aspose.html/configuration/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [GetService](../../aspose.html/configuration/getservice/#getservice)(*Type*) | Gets the requested service. |
| [GetService<T>](../../aspose.html/configuration/getservice/#getservice_1)() | Gets the requested service. |

### See Also

* namespace [Aspose.Html](../../aspose.html/)
* assembly [Aspose.HTML](../../)
