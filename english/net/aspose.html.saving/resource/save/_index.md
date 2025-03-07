---
title: Resource.Save
second_title: Aspose.HTML for .NET API Reference
description: Resource Save method. Saves the resource to the provided stream
type: docs
weight: 70
url: /net/aspose.html.saving/resource/save/
---
## Resource.Save method

Saves the resource to the provided stream.

```csharp
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which the resource will be saved. |
| context | ResourceHandlingContext | Resource handling context. |

### Return Value

This resource so that you can chain calls.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Raised if [`OutputUrl`](../outputurl/) is `null`. [`OutputUrl`](../outputurl/) should be specified before saving the resource because otherwise it is impossible to specify the correct reference in the resources referencing this one. |

### See Also

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* namespace [Aspose.Html.Saving](../../../aspose.html.saving/)
* assembly [Aspose.HTML](../../../)
