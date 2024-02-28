---
title: Resource Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.Resource class. This class describes a resource and provides methods for processing it
type: docs
weight: 4810
url: /net/aspose.html.saving/resource/
---
## Resource class

This class describes a resource and provides methods for processing it.

```csharp
public class Resource
```

## Properties

| Name | Description |
| --- | --- |
| [MimeType](../../aspose.html.saving/resource/mimetype/) { get; } | Returns the [`MimeType`](../../aspose.html/mimetype/) of this resource. Can be `null` if the resource was not found. |
| [OriginalReference](../../aspose.html.saving/resource/originalreference/) { get; } | Returns a string containing the original reference to this resource. |
| [OriginalUrl](../../aspose.html.saving/resource/originalurl/) { get; } | Returns a URL indicating where this resource was located. |
| [OutputUrl](../../aspose.html.saving/resource/outputurl/) { get; set; } | Gets or sets the URL indicating where the resource will be located after processing. |
| [Status](../../aspose.html.saving/resource/status/) { get; } | Returns the current status of the resource. |

## Methods

| Name | Description |
| --- | --- |
| [Embed](../../aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Embeds this resource within its parent by encoding it as Base64. The encoding result will be written to [`OutputUrl`](./outputurl/). |
| [Save](../../aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Saves the resource to the provided stream. |
| [WithOutputUrl](../../aspose.html.saving/resource/withoutputurl/)(Url) | Specifies the new URL indicating where the resource will be located after processing. |

### See Also

* namespace [Aspose.Html.Saving](../../aspose.html.saving/)
* assembly [Aspose.HTML](../../)
