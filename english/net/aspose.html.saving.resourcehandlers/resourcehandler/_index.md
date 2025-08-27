---
title: ResourceHandler Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Saving.ResourceHandlers.ResourceHandler class. This class is responsible for handling resources. It provides methods that allow you to control what will be done with the Resource as well as what reference will be written to the parent Resource
type: docs
weight: 4920
url: /net/aspose.html.saving.resourcehandlers/resourcehandler/
---
## ResourceHandler class

This class is responsible for handling resources. It provides methods that allow you to control what will be done with the [`Resource`](../../aspose.html.saving/resource/), as well as what reference will be written to the parent [`Resource`](../../aspose.html.saving/resource/).

```csharp
public abstract class ResourceHandler
```

## Methods

| Name | Description |
| --- | --- |
| abstract [HandleResource](../../aspose.html.saving.resourcehandlers/resourcehandler/handleresource/)(*[Resource](../../aspose.html.saving/resource/), [ResourceHandlingContext](../../aspose.html.saving/resourcehandlingcontext/)*) | This method is responsible for handling the resource. In it you can save the [`Resource`](../../aspose.html.saving/resource/) to the stream or embed it into the parent resource. |
| virtual [HandleResourceReference](../../aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/)(*[Resource](../../aspose.html.saving/resource/), [ResourceHandlingContext](../../aspose.html.saving/resourcehandlingcontext/)*) | This method is responsible for handling the resource reference. In this method, you can set what the reference to the resource being handled will look like. |

### See Also

* namespace [Aspose.Html.Saving.ResourceHandlers](../../aspose.html.saving.resourcehandlers/)
* assembly [Aspose.HTML](../../)
