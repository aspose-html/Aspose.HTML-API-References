---
title: FileSystemResourceHandler Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.ResourceHandlers.FileSystemResourceHandler class. This class is an implementation of the ResourceHandler class designed to save resources to the local file system
type: docs
weight: 4900
url: /net/aspose.html.saving.resourcehandlers/filesystemresourcehandler/
---
## FileSystemResourceHandler class

This class is an implementation of the [`ResourceHandler`](../resourcehandler/) class designed to save resources to the local file system.

```csharp
public class FileSystemResourceHandler : ResourceHandler
```

## Public Members
## Constructors

| Name | Description |
| --- | --- |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor_1)(*string*) | Initializes a new instance of the `FileSystemResourceHandler` class. |
| [FileSystemResourceHandler](filesystemresourcehandler/#constructor)(*[Url](../../aspose.html/url/)*) | Initializes a new instance of the `FileSystemResourceHandler` class. |

## Public Members
## Methods

| Name | Description |
| --- | --- |
| override [HandleResource](../../aspose.html.saving.resourcehandlers/filesystemresourcehandler/handleresource/)(*[Resource](../../aspose.html.saving/resource/), [ResourceHandlingContext](../../aspose.html.saving/resourcehandlingcontext/)*) | This method is responsible for handling the resource. In it you can save the [`Resource`](../../aspose.html.saving/resource/) to the stream or embed it into the parent resource. |
| virtual [HandleResourceReference](../../aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.html.saving/resource/), [ResourceHandlingContext](../../aspose.html.saving/resourcehandlingcontext/)*) | This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like. |

### See Also

* class [ResourceHandler](../resourcehandler/)
* namespace [Aspose.Html.Saving.ResourceHandlers](../../aspose.html.saving.resourcehandlers/)
* assembly [Aspose.HTML](../../)
