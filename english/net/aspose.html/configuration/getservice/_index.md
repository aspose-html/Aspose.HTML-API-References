---
title: Configuration.GetService
second_title: Aspose.HTML for .NET API Reference
description: Configuration method. Gets the requested service
type: docs
weight: 50
url: /net/aspose.html/configuration/getservice/
---
## Configuration.GetService&lt;TService&gt; method

Gets the requested service.

```csharp
public TService GetService<TService>()
    where TService : class, IService
```

| Parameter | Description |
| --- | --- |
| TService | The type of service to retrieve. |

### Return Value

An instance of the service if it could be found, or null if it could not be found

### See Also

* interface [IService](../../../aspose.html.services/iservice/)
* class [Configuration](../)
* namespace [Aspose.Html](../../configuration/)
* assembly [Aspose.HTML](../../../)
